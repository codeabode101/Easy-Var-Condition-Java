🤖 5-Day Java Project: Decision Helper Bot
Build a simple program that helps make small decisions based on user input!
---
### Day 1: Hello, Helper!
1. Create a Java file named `HelperBot.java`.
2. Use `Scanner` to ask the user for their name.
3. Print a welcome message using `System.out.println()`.
4. Example:
   ```
   What's your name?
   [User types] Alex
   Hello, Alex! I'm your Decision Helper Bot.
   ```
---
### Day 2: Yes or No?
1. Ask the user a simple yes/no question, e.g., "Is it sunny outside? (yes/no)". Use `System.out.print()` to ask the question on the same line as the input.
2. Read the user's answer using `Scanner`.
3. Use an `if` statement to check if the answer is "yes". If it is, print "Great, enjoy the day!".
4. Use an `else` statement if the answer is anything else, print "Okay, hope it clears up soon!".
5. Example:
   ```
   Is it sunny outside? (yes/no) [User types] yes
   Great, enjoy the day!
   ```
---
### Day 3: Pick a Number!
1. Ask the user to pick a number between 1 and 3.
2. Read their choice using `Scanner`.
3. Use `if`, `else if`, and `else` statements to respond:
   - If 1, print "You picked one!"
   - If 2, print "Two is a good choice!"
   - If 3, print "Three it is!"
   - Otherwise, print "That's not 1, 2, or 3."
4. Use `System.out.printf()` to say: "Your choice was %d. Thanks for playing!" at the end, replacing `%d` with the number.
5. (After core) Add a new response if the user picks the number 4.
6. Example:
   ```
   Pick a number between 1 and 3: [User types] 2
   Two is a good choice!
   Your choice was 2. Thanks for playing!
   ```
---
### Day 4: Double Check!
1. Ask the user if they need help with homework today (yes/no).
2. If the answer is "yes":
   - Ask: "Which subject? (math/reading)"
   - If "math", print "Let's review multiplication."
   - If "reading", print "Let's find a story to read."
   - Otherwise, print "Okay, let me know if you pick a subject."
3. If the first answer was "no", print "Alright, enjoy your free time!".
4. Example:
   ```
   Need help with homework today? (yes/no) [User types] yes
   Which subject? (math/reading) [User types] math
   Let's review multiplication.
   ```
---
### Day 5: Your Own Decision!
1. Add a new question to your Helper Bot. This question should have at least two possible answers.
2. Implement `if`/`else` or `if`/`else if`/`else` statements to respond differently to each answer.
3. Make sure to use `Scanner` to read input and at least two of the printing methods (`print`, `println`, `printf`).
4. (Open) Add your own simple question and two unique responses to the bot's conversation flow.
