# Homework 10  
This week you'll continue to add new features to the student data repository 
you created last week. One of the most popular features is knowing what classes 
have been completed when signing up for classes for next semester.  However, 
users point out that it would be nice if your system also reported the 
remaining required courses and the student's current Grade Point Average (GPA). 

Your assignment  this week has three components:
  1. Create a GitHub repository to manage your growing software 
    and store your HW09 solution in your repository.

  2. Add a new feature to your Student class to calculate each student's
    cumulative grade point average (GPA) and display the 
    GPA in the Student prettytable.
     
  3. Add a new feature to your solution to update the Student prettytable to 
     show the remaining required and elective courses for each student.  
     This requires information about required courses and 
     electives for each major.
     
## TODO
- [X] Create a GitHub repository for your Student Repository. This requires 
  several steps:
    - [X] Create a free GitHub account on github.com
    - [X] Create a "Student Repository" GitHub repository
    - [X] Rename your HW09_Your_Name.py to 
      [Student_Repository_Your_Name.py](Student_Repository_Jose_Cruz.py) 
      and rename your HW09_Test_Your_Name.py to 
      [Student_Repository_Your_Name.py](Student_Repository_Test_Jose_Cruz.py)
    - [X] Create a new [HW09](https://github.com/jjzcru/student-repository/tree/HW09) 
      branch in your "Student Repository" GitHub repository 
    - [X] Add [Student_Repository_Your_Name.py and Student_Repository_Your_Name.py 
      to the "HW09" branch](https://github.com/jjzcru/student-repository/commit/9e4ee27ec6cc8ceca124ea52fba373c35cabb95f) 
      in your new GitHub repository.
    - [X] Do a [pull request](https://github.com/jjzcru/student-repository/pull/1) 
      from github.com to merge the "HW09" branch into the "Master" branch.  
      Do NOT delete the HW09 branch after the merge.  We'll create separate 
      branches for each of the next few assignments.
    - [X] Create a new ["HW10" branch](https://github.com/jjzcru/student-repository/tree/HW10) 
      for this week's assignment
- [X] Download the new students.txt,  instructors.txt, grades.txt, 
  and majors.txt from Canvas
- [X] Update your HW09 code to use the 
  [new HW10 data files](https://github.com/jjzcru/student-repository/tree/HW10/support)
- [X] Add the new functionality to compute the student's GPA
- [X] Add new functionality to read the majors file and calculate the remaining 
  required and elective classes for each student
- [X] Add a new Majors prettytable
- [X] Update the Student prettytable to include the student's GPA and remaining 
  classes and electives for each student
- [X] Implement [automated tests](https://github.com/jjzcru/student-repository/blob/HW10/Student_Repository_Test_Jose_Cruz.py)
  to verify that the data in the prettytables matches the data from the input 
  data files. 
