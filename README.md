# Magic Eight Ball Project

This project is a simple implementation of a **Magic Eight Ball** using JavaScript. The program simulates a magic eight ball that answers any yes-or-no question posed by the user.

## Description

The code was created as part of a Codecademy exercise to practice basic JavaScript concepts such as:
- **Variables**
- **Conditional (ternary) operators**
- **Switch statements**
- **Random number generation**

The program allows the user to input their name and a yes-or-no question. Based on a randomly generated number, the program provides an answer from the magic eight ball.

## Code Breakdown

1. **User Information**:
   - The `userName` variable stores the name of the user.
   - The `userQuestion` stores the question asked by the user.
   - If a user name is provided, the program greets the user personally, otherwise, it gives a generic greeting.

2. **Random Answer Generation**:
   - A random number between 0 and 7 is generated using `Math.random()` and `Math.floor()`. 
   - This number is then mapped to one of eight predefined answers using a `switch` statement.

3. **Eight Ball Responses**:
   - Depending on the value of `randomNumber`, the `eightBall` variable is set to one of the possible magic eight ball responses:
     - "It is certain"
     - "It is decidedly so"
     - "Reply hazy try again"
     - "Cannot predict now"
     - "Do not count on it"
     - "My sources say no"
     - "Outlook not so good"
     - "Signs point to yes"

4. **Output**:
   - The program prints a greeting and then displays the user's question.
   - It then provides the answer from the magic eight ball.

## Example Output

Here’s an example of what the program might output when run:

```bash
Hello, Pedro!
Pedro has asked - I'm ugly?
The magic eight ball says, My sources say no
