# CEMS-project
CEMS is an application designed to facilitate efficient management of course examinations and related tasks for students, lecturers, and the head department. The application streamlines various operations and interactions within an educational institution.

# Features
## For Students
*Take exams: Students can access and complete exams online.<br>
*View grades: Students can view their exam grades and overall performance.

## For Lecturers
*Create questions: Lecturers can add and manage a variety of question types for exams.<br>
*Create exams: Lecturers have the ability to create exams with various question types.<br>
*Activate exams for students: Lecturers can activate prepared exams.<br>
*Grade exams: Lecturers can review and grade exams submitted by students.<br>
*Approve exams: Lecturers can submit exam proposals for approval by the head department.<br>
*Request time extension: Lecturers can request additional exam time for specific circumstances.<br>

## For Head Department
*Accept requests from lecturers: Head department members can review and approve/reject exam-related requests from lecturers.<br>
*View system-wide data: The head department can access comprehensive data and reports on the system's performance and activities.<br><br>

# Youtube Video
[See How Our App Works](https://www.youtube.com/watch?v=2MxUqiQuB-c)


#How to run
1. Via Mysql workbench create a schema called cems1 and import into it the contents of the file cems1.sql<br>
2. Run the server jar app via cmd by running <java -jar "path to jar file"><br>
3. Insert your DB username and password and click "Start server", if its not listening for connections check your input (and make sure mysql is open)<br>
4. Run the client jar app via cmd by running <java -jar "path to jar file"><br>
5. Connect to server on the client app <br>
6. Log in using data from DB (e.g. student account username "adan", pass "123". lecturer account "itay", pass "123". head department "dvora", pass "123".) <br>
7. Try the system out! run multiple client apps for the full experience (student, lecturer and head department)

