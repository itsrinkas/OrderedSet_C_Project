# Ordered Set Manipulation in C

A text menu-driven application for managing Ordered Sets using a custom double linked list implementation in C.

## Features

- Implementation of a dynamic data structure: double linked list
- Ordered integer sets that:
  - Store values in ascending order
  - Prevent duplicate entries
  - Track the number of stored elements
- Support for key set operations:
  - Union
  - Intersection
  - Difference
- Menu-driven interaction via terminal
- Input validation and clear structure
- Documented using Doxygen

## Menu

The program provides the following menu options:

1. Create an empty Ordered Set  
2. Delete an Ordered Set  
3. Add Element to Ordered Set  
4. Remove Element from Ordered Set  
5. Set Intersection  
6. Set Union  
7. Set Difference  
8. Terminate Program  

## Instructions

### Create an Ordered Set  
Choose an index (0–9) to create a new, empty set. If a set doesn’t already exist at that index, it will be created.

### Delete an Ordered Set  
Select the index (0–9) of the set to be deleted.

### Add Elements to a Set  
Choose a set and enter positive numbers to add. Enter a negative number to stop the input process. Duplicate values will be ignored.

### Remove Elements from a Set  
Select a set and enter the numbers you want to remove. If the number exists in the set, it will be removed. Enter a negative number to stop.

### Set Operations  
Perform operations on two sets and store the result in a third index:

- **Intersection**: Find common elements between two sets  
- **Union**: Combine two sets, including only unique elements  
- **Difference**: Remove all elements from the first set that are present in the second set

### Exit the Program  
Safely exits the program and deallocates all dynamic memory used by the sets.

## Notes
- All source files are structured and commented  
- Doxygen documentation is included in the project files  
