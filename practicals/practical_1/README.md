# SYSTEM DESIGN FOR AUTOMATE GRADING SYTEM

### Overview
Automated Grading for SWE Assignment is to have fair grading process for programming asignment ensuring integrity and efficiency.

**Key Component**
1. Professor sets assignment details 
    * it is the first step of the system to triger the main process

2. Student Submission
    * student must upload assignment to system for grading

3. Automated Grading
    * the system must execute the code and evaluate the result

4. Plagiarism Detection
    * submission should be compared to against other student's code

5. LMS integration 
    * final grade must be exported to university's mainframe 

6. Multiple Attempts 
    * Students should be allowed to submit multiple times before deadline

7. Late Submission
    * late submission must be rejected by the system

8. Manual grading
    * professor can perform maual grading if needed


**Flow of Interaction **
1. The professor initaites the process by assigning the students assignment, setting up the grading details and deadline.

2. User submits the assignment after completion.

3. The system accepts the student's assignment based on the deadline set by the professor. If student submit the assignment after deadline, system rejects the submission.

4. After the accepting the assignment the system proceed with checking plagiarism detection, executing the code and grading based on the criteria set by the professor.

5. Lastly integrating with the LMS after grading process are done, which includes importing the grades of every students.