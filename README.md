# IT 145 - Plurality

This project was created for IT 145: Introduction to Programming.

The program simulates a plurality election. Each voter chooses one candidate, and the candidate with the highest number of votes wins.

The program uses an array of candidate structs to store each candidate's name and vote count. The vote function searches for the selected candidate and adds one vote when the name is valid.

The print_winner function first finds the highest number of votes and then checks the candidates again to print every candidate with that total. This allows the program to correctly handle ties.

Invalid votes are ignored and do not change any candidate's vote count.

## Concepts Used

- C programming
- Structs
- Arrays
- Functions
- Loops
- String comparison
- Linear search
- Plurality elections
- Handling ties
