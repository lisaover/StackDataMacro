# StackDataMacro
Generalized SAS macro that automatically converts a longitudinal dataset into a vertical dataset.

During my internship, I created two SAS macros to convert a longitudinal dataset into a vertical dataset. The _stackMacro.sas_ script is for a dataset with a single key, and the _stackMacroV2.sas_ script is for a dataset with a two-component key. The macros are completely generalized and require three parameters: the name of the dataset to be converted, the key(s) for that dataset, and the name of the new key for the transformed dataset. The macros also accept a list of variables to copy to the new dataset that would be lost in the transformation.

My goal is eventually to combine the macros into one macro that accepts a list of keys, so it will work with datasets with any number of keys.
