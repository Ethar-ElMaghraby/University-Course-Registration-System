University Course Registration System

This project is a simple Course Registration System using linked lists (and stacks for undo/redo as bonus).
It manages students, courses, and their enrollments in a dynamic way.

Objectives

Store only needed enrollments using linked lists.
Add/Remove students and courses easily.
Enroll/Remove students from courses.
Show courses by student or students by course.
Sort students and courses by ID.
Undo/Redo enrollment actions.

Functions Implemented
addStudent(int studentID)
addCourse(int courseID)
removeStudent(int studentID)
removeCourse(int courseID)
getLastStudentAdded()
getLastCourseAdded()
enrollStudent(int studentID, int courseID)
removeEnrollment(int studentID, int courseID)
listCoursesByStudent(int studentID)
listStudentsByCourse(int courseID)
sortStudentsByID(int courseID)
sortCoursesByID(int studentID)
isfullCourse(int courseID)

isnormalstudent(int studentID)
