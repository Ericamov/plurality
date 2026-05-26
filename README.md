# CS50 – Plurality

## Description

This program simulates a plurality election by counting votes for candidates and printing the winner(s).

## How it works

The program:

1. Takes candidate names as command-line arguments
2. Stores each candidate and initializes their vote count to zero
3. Prompts the user for the number of voters
4. Repeatedly asks each voter to enter a candidate’s name
5. Validates each vote
6. Increments the vote count for valid candidates
7. Prints the candidate(s) with the highest number of votes

## Usage

```bash
make plurality
./plurality Alice Bob Charlie
```

## Example

```
./plurality Alice Bob Charlie
Number of voters: 5

Vote: Alice
Vote: Bob
Vote: Alice
Vote: Charlie
Vote: Alice

Alice
```

## Concepts

Command-line arguments
Structs
Arrays
String comparison with strcmp
Loops
Input validation
Vote counting algorithms
Functions and modular programming
