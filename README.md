### if.05.01 TINF Operting Systems

# Assignment 3: NoBeard Assembler
## Objective
The goal of this week's assignment is to make you familiar with assembler programming.

## Materials
- Chapters 2 and 4 of the NoBeard Report.
- A text editor (take care that the line ending is set to UNIX format, i.e., line feed (LF) only).
- `nba-`[`win`|`macos`] (depends on your platform) to assemble your programs.
- `nbmgui-`[`win`|`macos`] (depends on your platform) to run and debug your programs.

## Example
Lets assume a NoBeard assembler file `first_test.na`. To assemble and run the program the following steps have to be done:

1. Assemble the program to translate the NoBeard assembler file into a NoBeard object (file extension `.no`) file
1. Start the NoBeard machine
1. Load the `.no` file into the machine and start it

The commands are as follows:
### On a Windows Machine
```
nba-win first_test.na // assemble
nbmgui-win // start the machine
```
### On macos
```
nba-macos first_test.na // assemble
nbmgui-macos // start the machine
```

## Required Tasks
1. Create a folder `Solutions` to your repository. Place all assembler files you create for the next tasks into this directory.
1. **Percentage calculator:** Write an assembler program `percentage_calculator.na` which is asking the user for the maximum number of points to be achieved and the points actually achieved. The program then outputs how many percent the user got.
2. **Counter:** Write an assembler program `counter.na` which prints the numbers from 1 to n in a loop. n is entered by the user.
3. **Prime factors:** Write an assembler program `prime_factors.na` which calculates the prime factors of a given integer: The user can enter a positive integer. If the entered value is negative an error shall be printed. If the entered value is positive the prime factors are printed.
3. Test your programs thoroughly
3. Commit and push the newly created files.
