Makefiles
This repository contains a series of Makefiles for different tasks related to low-level programming. Below is an overview of each task:

Task 0: 0-Makefile
Objective: Create your first Makefile.
Requirements:
Name of the executable: school
Rules: all
The all rule builds your executable
Variables: none
Example Usage:
 
  
make -f 0-Makefile
Task 1: 1-Makefile
Objective: Enhance the Makefile with compiler and source file variables.
Requirements:
Name of the executable: school
Rules: all
The all rule builds your executable
Variables: CC (compiler), SRC (.c files)
Example Usage:
 
  
make -f 1-Makefile
Task 2: 2-Makefile
Objective: Create a more useful Makefile with additional variables for object files and executable name.
Requirements:
Name of the executable: school
Rules: all
The all rule builds your executable
Variables: CC (compiler), SRC (.c files), OBJ (.o files), NAME (executable name)
Example Usage:
 
  
make -f 2-Makefile
Task 3: 3-Makefile
Objective: Build upon the previous Makefile by adding rules for cleaning and recompiling.
Requirements:
Name of the executable: school
Rules: all, clean, oclean, fclean, re
Variables: CC (compiler), SRC (.c files), OBJ (.o files), NAME (executable name), RM (file deletion program)
Example Usage:
 
  
make -f 3-Makefile
make clean -f 3-Makefile
make fclean -f 3-Makefile
make re -f 3-Makefile
Task 4: 4-Makefile
Objective: Create a complete Makefile with additional compiler flags.
Requirements:
Name of the executable: school
Rules: all, clean, fclean, oclean, re
Variables: CC (compiler), SRC (.c files), OBJ (.o files), NAME (executable name), RM (file deletion program), CFLAGS (compiler flags)
Example Usage:
 
  
make all -f 4-Makefile
Task 5: 5-island_perimeter.py
Objective: Implement a   function to calculate the perimeter of an island in a grid.
Requirements:
Function: def island_perimeter(grid)
No module imports allowed
Documented module and function
Example Usage:
 
  
island_perimeter(grid)
Task 6: 100-Makefile
Objective: Advanced Makefile with specific constraints.
Requirements:
Name of the executable: school
Rules: all, clean, fclean, oclean, re
Variables: CC (compiler), SRC (.c files), OBJ (.o files), NAME (executable name), RM (file deletion program), CFLAGS (compiler flags)
Additional constraints on variable usage and Makefile behavior.
Example Usage:
 
  
make all -f 100-Makefile

