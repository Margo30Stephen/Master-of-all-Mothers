# Master-of-all-Mothers
A raspberry pi based project which helps you with scheduling your tasks. Just upload your timetable in an excel sheet with start time and end time of a task, and you are set.
To program the raspberry pi 4 model B, i have used the SSH protocol.
The raspberry pi is attached to a speaker through an Audio Jack cable.
The idea behind this project was to help me keep up with the 'less important' or else the tasks which take a back seat while we are busy with assignments, homework or just meeting deadlines.
My list of tasks which take a backseat are:
1. Exercise
2. Skincare
3. Eating healthy food
4. Sleep

To help me keep up with these tasks this MOM bot is of huge help.
Features of this robot:
1. You can customize your timetable every hour, every day, every week, or every month. Just write your timetable in an excel sheet with 3 columns 'Start Time', 'End Time' and 'Task'. Sample is given in the repository by the name TimeTable.xlsx.

2. Once you upload the excel file, the 'Schedule' library will set up all the necessary voice commands for the required time as per the tasks. For example, if as per your timetable, at 5:30 am your day starts with doing exercise till 6:00am. The voice command will be set up at 5:30 am every day to wake up and exercise. The voice command will be what you have written in your 'Task' column of the excel sheet.

3. You can give feedback on all your tasks. If you complete the task, press the done button, if not done dont press anything. By default, the feedback is set as 'Not Done'. This feedback is saved in a dataframe. You can keep a watch on your progress by visualizing the data in the form of a bar graph. For example, the feedback.xlsx file shows my progress for the past 7 days.

4. The 'I am stressed' button helps with de-stressing. I destress by a song which my mother and grandfather used to sing to me when i was a baby. So, if i press that button, the speaker will play that song.

5. The 'I am going out' button helps me remember all the stuff that needs to be taken care of when i am going out. Such as taking my keys, card, water etc. So when i m heading out, after pushing the button, it will recite all the important stuff that i need to do when i am heading out.


