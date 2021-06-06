# Attendance-Calculator-for-Teams

Source Code and Application for calculating Attendance of students or people in a MS Teams meeting.

## Files Prep

You require atleast 2 files to calculate the attendance for a Teams meeting.

#### Attendance Calculation – Excel File

* The above file should include the details of all the students or users who are attending or who are scheduled to attend the meeting.

* This file can be reused and updated if the names of the students or users, match with the csv date files of multiple meetings.

Example Filename: attendancecalculation.xlsx

<img src= https://github.com/rajeshwaranravi/Attendance-Calculator-for-Teams/blob/main/Demo/Example1.jpg>

 
#### DD-MM-YYYY – CSV File

* The date files in the above format can be obtained from a Teams meeting by downloading the attendance list. The above files contain the details of the students or users who joined and left the meeting along with the respective timestamps.

Example Filename: 11-09-2020.csv

<img src = https://github.com/rajeshwaranravi/Attendance-Calculator-for-Teams/blob/main/Demo/Example2.jpg>

### NOTE:

* The names in both the files should match and it is preferable that the names in both the files have the same case (UPPER/LOWER).

* Should save the csv file in UTF-8 Format, otherwise the application won’t work.

While saving or downloading the csv file from teams, click on Tools -> Web Options -> Encoding and use the dropdown to save this document as Unicode (UTF-8).

<img src = https://github.com/rajeshwaranravi/Attendance-Calculator-for-Teams/blob/main/Demo/Example3.jpg>


## Running the Application
* After starting the application from start menu, enter the start time and end time of a class meeting as per the specified format.

* Enter the threshold percentage value (0-100). A value of 0 indicates that a student or user need not even attend the meeting to be awarded attendance whereas a value of 100 indicates that the student or user should be present throughout the meeting exactly from the start time till the end time. A value of 75 – 90 is recommended.

* Upload the attendance calculation file and the date csv files in the format discussed earlier. The final calculated attendance results will be stored in the attendance calculation excel file. You can upload multiple date files if they have the same meeting times for attendance calculation.

* After uploading, verify whether the paths displayed are the correct paths of the file.

<img src = https://github.com/rajeshwaranravi/Attendance-Calculator-for-Teams/blob/main/Demo/Example5.jpg>

* After verifying the path, click the Submit button to calculate the meeting attendance. You will be also shown a message in a command window once the process is completed.

* The results can now be viewed in the attendance calculation file.

<img src = https://github.com/rajeshwaranravi/Attendance-Calculator-for-Teams/blob/main/Demo/Example6.jpg>

### NOTE:

* Please verify whether the entered start time and end time along with the time of day (AM/PM) correspond with that of the data in the date csv file obtained from Teams.
