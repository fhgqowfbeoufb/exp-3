Aim:
To study the concept of tuples in Python and perform various operations on them.

Theory:
A tuple is a built-in collection data type in Python used to store multiple items in a single variable. Tuples are ordered, allow duplicate values, and are immutable, meaning their elements cannot be modified after creation. Elements of a tuple can be accessed using indexing and slicing techniques. Python also provides the feature of tuple unpacking, which allows assigning tuple elements to multiple variables in a single statement. Additionally, tuples support basic built-in methods such as count() and index() for performing simple operations and analysis.

Algorithm 1: Tuple Unpacking and Distinction Check

Start

Create a tuple named result containing Subject, Marks, and Grade.

Unpack the tuple into three variables: Subject, Marks, and Grade.

Display Subject.

Display Marks.

Display Grade.

If Marks (i.e., result[1]) is greater than or equal to 75, print “Distinction”.

Stop

Algorithm 2: Attendance Count and Absence Check

Start

Create a tuple named attendance containing attendance status (‘P’ for Present, ‘A’ for Absent).

Count the number of ‘P’ using attendance.count('P') and display total present days.

Count the number of ‘A’ using attendance.count('A') and display total absent days.

If total absent days are greater than or equal to 1, print “Employee was absent at least once”.

Stop

Conclusion:
Thus, we successfully studied tuples in Python and performed various operations such as indexing, slicing, unpacking, and counting elements. We also learned that tuples are immutable in nature and are particularly useful when the stored data should remain constant and unaltered.
