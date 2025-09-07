# Personal Calculator Activity

## Learning Objectives

By completing this activity, you will practice:
- Working with different Python data types (int, float, str)
- Performing arithmetic operations and using assignment operators
- Working with strings (concatenation and formatting)
- Getting user input and displaying formatted output
- Writing a complete Python program

## Setup

After clicking the GitHub Classroom link and accepting the assignment:

1. **Clone your repository**:
   ```bash
   cd Desktop/cs100/activities    # or wherever you keep course files
   git clone [YOUR_REPOSITORY_URL]
   cd activity01
   ```

2. **Open the project in VS Code**:
   Use VS Code menu: File → Open Folder → select your `activity01` folder

## Activity Instructions

You will create a **Personal Calculator** that:
1. Greets the user by name
2. Takes two numbers from the user
3. Performs various calculations
4. Displays results in a nice format

**Time Estimate: 20-30 minutes**

### Your Task

Complete the `main.py` file by replacing all the TODO comments with working code. The program should:

1. **Get user information**: Ask for their name and store it
2. **Get calculator inputs**: Ask for two numbers
3. **Perform calculations**: Do arithmetic operations on the numbers
4. **Display results**: Show all calculations in a formatted way
5. **Personalize output**: Use the user's name in the messages

## Testing Your Program

Run your program to make sure it works:

```bash
python main.py
```

### Example Output
```
Welcome to the Personal Calculator!
What's your name? Alice
Hello Alice! Let's do some math.

Enter your first number: 10
Enter your second number: 3

Alice, here are your calculation results:
================================
10.0 + 3.0 = 13.0
10.0 - 3.0 = 7.0
10.0 * 3.0 = 30.0
10.0 / 3.0 = 3.33
10.0 // 3.0 = 3.0
10.0 % 3.0 = 1.0
10.0 ** 3.0 = 1000.0
================================
Thanks for using the calculator, Alice!
```

## Submission

### Git Workflow

**Submit your work**:
   ```bash

   # Add your completed main.py file
   git add main.py
   
   # Commit your changes
   git commit -m "Complete activity 1"
   
   # Push to GitHub
   git push origin main
   ```

3. **Verify your submission**:
   - Go to your repository on GitHub
   - Make sure your completed `main.py` file is visible

## Grading Rubric

This activity is assessed on a **pass/fail basis**:

- **1 point**: Awarded if 50% or more of the program functionality is completed
- **0 points**: Awarded if less than 50% of the program functionality is completed

The program functionality includes: user input, arithmetic operations, string formatting, and proper output display.

## Tips for Success

- **Read the TODO comments carefully** - they tell you exactly what to do
- **Test after each step** - run your program frequently to catch errors early
- **Use meaningful variable names** - `user_name` instead of `n`
- **Don't forget to convert input** - use `float()` for numbers
- **Pay attention to spacing** - make your output look nice

## Common Issues

- **Type errors**: Remember `input()` returns a string - convert with `float()`
- **Missing quotes**: String values need quotes around them
- **Indentation**: Make sure your code is properly indented
