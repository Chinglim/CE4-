#CE4-Assembly Language Programming
====
## Program A Code Listing-Simple Memory Manipulation
Purpose: To write a program that stores the value $9 in location $B0, $8 in $C4 abd $B in $CB.(Target program end:$11)

Image:![Program A Coding][ProgramACodeListings]




Explanation:First label the respective final memory location as mem1, mem2 and mem3. These will then be used later when keying into the programming wizard.

Then load the respective value within to the respective final memory location.

Verification: Demo carried out and verified by Cpt Sliva.


## Program B Code Listing-Mathematics
Purpose:To retrieve a value from $B0, doubles it, and subtracts 4. Then output value to Port 2.(Target program end:$0C)

Images:



Explanation: As seen in the ProgramBCodeListing diagram, the memory locations have been setted previously by Program A. Use those memory location to access the required information and do the necessary computation required. As shown in this diagram too, the hexadecimal 'E' is finally output at port 2, which further verify that the programme was carried out properly.

ProgramBCodeListing-2 diagram will then explain for the rationale of the steps taken to carry out Program B. 

Verification:Demo carried out and verified by CPT Sliva.


## Program C Code Listing-Loops
Purpose:Reading value from Input port 3, then display on Output Port 0. One less will then be displayed at Port 1 
        and one less than Port 1 to be displayed on Port 2. Program will then decrements what is on Port 0,Port 1 
        and Port2, continue in an infinite loop.(Target program end:$10)
        
Images:

Explanation: As seen in the ProgramCCodeListing diagram, the tracking of the value from Port 3 then displaying the value in Port 0, followed by the decrements of the value that is then subsequentially displayed in Port 1 and 2. As shown in this diagram too, the hexadecimal 'E' ,'D' and 'C' showed the decrement of value, displayed at the necessary output port. This then further verify that the program is carried out smoothly and properly as required.

ProgramCCodeListing-2 diagram will then explain for the rationale of the steps taken to carry out Program B. 


Verification:Demo carried out and verified by Cpt Silva.
