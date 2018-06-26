Template used for this: https://gist.github.com/PurpleBooth/109311bb0361f32d87a2

Project Title:
Tfl Coding Challenge

Getting Started:
Run "TfL Coding Challenge.exe"

Installation:
Not Required, just run the .exe file.

Running Tests:
1. Click "Browse" and select CSV, should be comma delimited with the following Headers (CSV in the zip file):
Title
Employee First Name
Employee Surname
Employee ID
Employee Location
Employee Age
Employee Role
2. CSV Should have two rows of data.
3. "Site URL" enter the following: https://mancera.sharepoint.com/sites/TfLCodingChallenge
4. "UserID" enter your UserID
5. "Password" enter your password
6. Click "Create"
7. You should get a message box saying "Task Completed"
8. Go to: https://mancera.sharepoint.com/sites/TfLCodingChallenge
9. Left hand side should have the new list "Staff"
10. Go to: https://mancera.sharepoint.com/sites/TfLCodingChallenge/_layouts/15/viewlsts.aspx
11. New "Staff" list should have 10 items at least.
12. Go to: https://mancera.sharepoint.com/sites/TfLCodingChallenge/Lists/Staff/Employee%20Data.aspx
13. "Employee Data" should be the default view.
14. Click the "List" tab > "Modify View" > Scroll down to "Sort" section
15. View should be sorted by "Employee Surname" ascending order.
16. Test down

Testing For Errors:
1. Click "Create" with any empty fields:
No dialog box will appear but instead only highlighted with an error marker.
2. Click "Create" with incorrect Site URL:
Dialog box should appear with "Please make sure Site URL is correct"
And the affected fields are highlighted with an error marker.
3. Click "Create" with incorrect Login Details:
Dialog box should appear with "Please make sure your login details are correct"
And the affected fields are highlighted with an error marker.
4. Click "Create" when list already created:
Dialog box should appear with "List already exists"
5. All errors are logged and saved in the same directory.

Bugs:
GUI assumes that the CSV is correct, so even if it's incorrect it will proceed with the list creation.
List will be created but with default columns.
Work around is to simply delete the list and try again with a working CSV.

