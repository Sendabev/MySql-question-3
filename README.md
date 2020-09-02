# MySql-question-3
Write a MySQL query that will display the number of students per course per institution in the format below.
The code that will display the table as shown in the question is:
SELECT institution.Name AS Instituition Name, course.Name AS Course Name, student.StudentID AS Number of Students FROM institution LEFT JOIN course ON course.Institution = institution.InstitutionID LEFT JOIN student ON student.Course = course.CourseID ORDER BY course.Name DESC, institution.Name DESC
