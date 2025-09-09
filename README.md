# Personal Calculator Activity
## DUE: 9:30AM September 11, 2025

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

## Your Task

Create a **Personal Calculator** by completing the `main.py` file. Replace all TODO comments with working code to:

1. **Get user information**: Ask for their name and store it
2. **Get calculator inputs**: Ask for two numbers  
3. **Perform calculations**: Do all arithmetic operations (+, -, *, /, //, %, **)
4. **Display results**: Show calculations in a formatted way with the user's name

## Testing Your Program

Run your program to make sure it works:

```bash
python main.py
```

### Example Output
```
Welcome to the Personal Calculator!
What's your name? Amir
Hello Amir! Let's do some math.

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
Thanks for using the calculator, Amir!
```

## Submission

**Submit your work**:
```bash
# Add your completed main.py file
git add main.py

# Commit your changes
git commit -m "Complete activity 1"

# Push to GitHub
git push origin main
```

**Verify your submission**: Go to your repository on GitHub and make sure your completed `main.py` file is visible.

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
