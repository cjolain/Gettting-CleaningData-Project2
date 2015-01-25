#Variables
* `x_train`, `y_train`, `x_test`,`y_test`, `subject_train` and `subject_test` correspond to the downloaded files.
* `x_data`, `y_data` and `subject_data` merge the previous datasets for the next steps.
* `features` contains the correct names for the x_data dataset, which are applied to the column names stored in mean_and_std_features, a numeric vector used to extract the desired data.
* A similar approach is taken with activity names through the activities variable.
* `all_data` merges `x_data`, `y_data` and `subject_data`.
* Finally, `averages_data` contains the relevant averages.
