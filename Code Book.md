Code Book

## Dataset Description
The data used in this project comes from the Human Activity Recognition Using Smartphones Dataset.
The dataset contains measurements collected from smartphone sensors while subjects performed
different physical activities.

The final tidy dataset contains the average of each selected measurement for each subject
and each activity.

---

## Variables

### Identifiers
- **subject**: The ID of the subject who performed the activity (integer 1–30)
- **activity**: The type of activity performed  
  (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING)

---

### Measurements
The dataset includes the mean and standard deviation of the following signals:
- Time and frequency domain signals
- Accelerometer and gyroscope measurements
- Magnitude of signals

All measurement variables represent **averages** of the original measurements,
grouped by subject and activity.

---

## Data Cleaning Steps
1. Loaded training and test datasets
2. Merged training and test data into one dataset
3. Extracted only measurements on the mean and standard deviation
4. Replaced activity codes with descriptive activity names
5. Renamed variables to be more descriptive and readable
6. Created a tidy dataset with the average of each variable for each subject and activity

---

## Output File
- **tidy_dataset.txt**: A tidy dataset containing the average of each variable for each activity and each subject
