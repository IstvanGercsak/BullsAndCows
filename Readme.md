# Bulls and Cows

## Description

There are two players: the first writes a secret 4-digit code using different digits, and the second has to guess it. At each turn, the second player writes a 4-digit number that they think might be the correct answer. Then, the first player grades that answer using bulls and cows as a notation. If a digit in the given answer matches a digit and its position in the code, it's called a "bull." If a given digit appears in the code but its position doesn't match, then it's called a "cow." The first player reveals how many bulls and cows there are. The information is general; in other words, it isn't bound to any particular digit.

[Project task link](https://hyperskill.org/projects/53?track=8)

## Implementation stages

### 1/5 - Take position!

#### Description:

Let's start by reminding ourselves how the game goes. There are two players: the first writes a secret 4-digit code using different digits, and the second has to guess it. At each turn, the second player writes a 4-digit number that they think might be the correct answer. Then, the first player grades that answer using bulls and cows as a notation. If a digit in the given answer matches a digit and its position in the code, it's called a "bull." If a given digit appears in the code but its position doesn't match, then it's called a "cow." The first player reveals how many bulls and cows there are. The information is general; in other words, it isn't bound to any particular digit. For example:

The code is 4931.
The answer is 1234.
The grade is 1 bull and 2 cows.

Here, 3 is a bull, 1 and 4 are cows. If all the digits are bulls, the secret code has been guessed and the game ends. If not, the game continues and the second player tries again.

This may sound rather complicated, but don't worry, we will take it very gradually. In this stage, you will not even have to implement the gameplay: all you need to do now is output the text that could be in the game. In other words, you don't have to worry about handling any requests or processing data: your goal is to display an example text of the game.

#### Objectives:

In this stage, your program should:

- Print a predefined game log that contains at least two turns.
- The output to be graded is a 4-digit code consisting of unique digits.
- The last line of your output contains a secret number.

### 1/7 - Game log

#### Description:

#### Objectives:

### 2/7 - Grader

#### Description:

#### Objectives:

### 3/7 - Secret code

#### Description:

#### Objectives:

### 4/7 - Game time!

#### Description:

#### Objectives:

### 5/7 - Improve the code generator

#### Description:

#### Objectives:

### 6/7 - New level

#### Description:

#### Objectives:

### 7/7 - Error!

#### Description:

#### Objectives:

# Used technology
- Java
- IntelliJ IDEA