ECE281_CE4
==========

PRISM Assembly Language Programming

Part A : Simple Memory Manipulation
-This functionality of the lab simply storing different values in various locations. The most difficult part of this section was learning how PRISM worked. Once you understand which Mnemonics to use, and how they work, this section was easy. 
_____________________________________________
Part B : Mathematics
-This functionality of the lab was the most difficult portion of the lab. This portion of the lab required us to store data and manipulate it. The most difficult part of the lab was learning how to use new mnemonics. 
______________________________________________
Part C : Loops
-This functionality of the lab was a combination of the skills learned in part A and part B. Because I had jsut learned how to store and manipulate data, this portion of the lab was easier than part B. The most difficult part of the lab was figuring out how to get the loop to work correctly.
______________________________________________
Errors and Debugging
-My first error occured during part A. I ran into an endless loop that kept occuring when I tried storing my first data value. Everyone I asked, including my instructor, could not figure out why the loop was occuring. Eventually, I closed the program and restarted. This fixed the error. 
-My second issue was with part B. I initially attemped to double the given value by rotating right three times. However, I soon figured out that rotating right does not always work. Instead, I decided to store the value and then add it to itself. This ensured that the value was always properly doubled. 
-My third issue occured in part B. I initially began trying to subtract 4 by taking the twos compliment and then adding this to the stored value. However, I found an wasier way to perform the operation by simply adding the two's compliment on my own. I would add C which is the same as subtracting 4. 
-My last debugging issue was part of part C. Initially I thought the loop was supposed to work by taking what was displayed on output 2 and subtracting one then displaying that new value to output 0. However, I was supposed to take the old value from output 0 and subtract one to get the new value for output 0. Output 1 and output 2 would then decrease by one also. After correcting how to decrement the output displays, I ran into the error of my loop not working correctly. My loop initially kept reloading the value of input three. After stepping through the program, I realized I set the location for the loop to jumpt to at the wrong spot. I moved  the new jump location to the step of storing the new value. Therefore, before I jump I needed to add ADDI and a LDAD. Before jumping I would load the value of output 0 and subtract one. This would set up the program for proper decrementation. This worked. 
______________________________________________
Documentaion
- I discussed how the mnemonic code worked for parts A with C2C Agnolutto. C2C Agnolutto and myself discussed how rotating right three times worked. Together we realized that this did not work. No other help was received. 
