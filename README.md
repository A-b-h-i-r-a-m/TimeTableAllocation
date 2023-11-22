# TimeTableAllocation

This a Constraint Satisfaction Problem where for a given number of sections, time slots and classrooms; allocate classroooms in such a manner that the below constraints are satisfied.
Constraints:
1. The classroom’s requirements should be consistently addressed for five week-days and for the given time slots.
2. All classrooms should be uniformly utilized by the sections.
3. Different sections may get the same classroom, but the same classroom should not be allocated to more than one section within the same time slot, i.e. conflicts must be addressed.

We have done this application using Python , Flask and Jinja2.

Python - logical execution
Flask - Server side programming which is a good match with Python.
Jinja2 - To dynamically intergrate python into html files.

For the logical part, we are using backtracking search and constraint propogation techniques.

If you want to have your own templates , go to the 'templates' folder and add your own html files.

To execute the application , run 'main.py'.
