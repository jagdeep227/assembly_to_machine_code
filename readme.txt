DATE- 27-03-2019																

											README <->  PHASE-I


CONTRIBUTION =>	JAGDEEP SINGH (25%)
		PIYUSH CHECHI (25%)
		ANMOL PUNIA (25%)
		DEEPAK MAHTO (25%)

HOW TO RUN =>	EXTRACT "phase1_s11.zip" FILE
		GO TO ITS DIRECTORY IN TERMINAL
		MAKE ENSURE YOU HAVE COPIED THE ASSEMBLY CODE INTO "assem_code.asm" FILE
		ENTER "g++ ded.cpp" IN TERMINAL
		ENTER "./a.out"
		NOW CHECK "mach_code.mc" FILE FOR MACHINE CODE

THE PROGRAM IS ABLE TO CONVERT ALMOST ALL OF THE ASSEMBLY INSTRUCTION OF 32 BIT THAT ARE SUPPORTED IN VENUS , EXCLUDING PSEUDOINSTRUCTIONS AND SOME OTHER SPECIFIC ONES.	
NOTE: ENTER ASSEMBLY CODE WITHOUT COMMAS .
WE USED BITSET FOR MAKING A MACHINE CODE FOR EACH INSTRUCTION AND CONVERTING IT BACK TO HEXADECIMAL FORM . BITSET MADE IMPLEMENTATION MUCH EASY. 
ONLY INSTRUCTIONS OF ".text" ARE CONVERTED TO MACHINE CODES AS WE DO IN VENUS .

