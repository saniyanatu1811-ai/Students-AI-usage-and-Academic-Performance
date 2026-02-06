# Students-AI-usage-and-Academic-Performance
Using different DAX formulae and creating new measures for the data visualization
1. % Uses AI = DIVIDE([AI Users], [Total Students])
2. Avg grades after AI = AVERAGE(students_ai_usage[grades_after_ai])
3. Avg grades before AI = AVERAGE(students_ai_usage[grades_before_ai])
4. Grade Change = 
AVERAGE([grades_after_ai])
-
AVERAGE([grades_before_ai])
5. Total Students = COUNTROWS('students_ai_usage')
