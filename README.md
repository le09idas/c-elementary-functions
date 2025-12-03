# c-elementary-functions

This repo will contain assignments from the first unit in Introduction To MIPS Assembly Language Programming by Charles W. Kann.

13) Write the functions toUpper and toLower in the HLL of your choice (C/C++, Java, C#, etc.) The toUpper function converts the input parameter string so that all characters are uppercase. The toLower function converts the input parameter string so that all characters are lowercase. Note that the input parameter string to both functions can contain both upper and lower case letters, so you should not attempt to do this using addition.

14) Implement a program in the HLL of your choice that converts an ASCII string of characters to an integer value. You must use the follow pseducode algorithm:
  
```
read numberString
outputNumber = 0
while (moreCharacters) {
    c = getNextCharacter
    num = c - '0';
    outputNumber = outputNumber * 10 + num;
}
print outputNumber;
```

15) Write a program in the HLL of your choice to take a string representing a binary number, and write out the number in hex.

16) Write a program in the HLL of your choice to take an integer and write its value out in hex. You cannot use string formatting characters.
