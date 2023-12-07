# university_courses_management_system
An IT university desires to develop a course management system. Courses have fixed capacities and students can only be enrolled in a limited number of courses if their capacity allows for it.

INPUT:
The inputs are represented by standard input. The program should read the input line by line. It checks the correctness of the input line, if it is correct, it waits for the next line, otherwise it prints an error message and terminates the program. Whenever the empty line is met, the program should stop its execution. There can be multiple commands.

The input should be in the following format:
_____________________________________________________________________________________________________________________________
Command	            |  Input_format
_____________________________________________________________________________________________________________________________
Add course	        |  course
                    |  courseName
                    |  courseLevel
_____________________________________________________________________________________________________________________________
Add student	        |  student
                    |  memberName
_____________________________________________________________________________________________________________________________
Add professor	      |  professor
                    |  memberName
_____________________________________________________________________________________________________________________________
Enroll to course	  |  enroll
                    |  memberId
                    |  courseId
_____________________________________________________________________________________________________________________________
Drop from course	  |  drop
                    |  memberId
                    |  courseId
_____________________________________________________________________________________________________________________________
Assign to course	  |  teach
                    |  memberId
                    |  courseId
_____________________________________________________________________________________________________________________________
Exempt from course	|  exempt
                    |  memberId
                    |  courseId
____________________________________________________________________________________________________________________________
