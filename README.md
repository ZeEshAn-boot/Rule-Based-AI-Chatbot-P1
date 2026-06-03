# AI Chatbot Using Python

## Project Overview

This project is a simple rule-based AI chatbot developed using Python. The chatbot interacts with users through text-based conversation and responds to predefined questions and commands using conditional statements (`if-elif-else`).

The chatbot can greet users, answer basic questions, provide a motivational quote, and give information about different fruits, vegetables, and their benefits. The conversation continues until the user enters the command `bye`.

---

## Objectives

- Learn the basics of chatbot development.
- Practice Python programming concepts.
- Understand user input and output handling.
- Implement decision-making using conditional statements.
- Create a simple conversational application.

---

## Features

### Greetings
The chatbot responds to greetings such as:

- hello
- hi
- hey

### Basic Conversation
The chatbot can answer simple questions such as:

- how are you
- how are you doing
- what is your name
- what can you do
- what's up

### Motivational Quote
Users can request a motivational quote by typing:

- quote

### Fruit and Vegetable Information
The chatbot provides information about:

- Apple
- Banana
- Mango
- Orange
- Grapes
- Watermelon
- Pineapple
- Strawberry
- Blueberry
- Pear
- Peach
- Kiwi
- Avocado
- Lemon
- Carrot
- Spinach
- Cucumber

Users can ask directly:

- apple
- banana
- mango

or ask:

- tell me about apple and its benefits
- tell me about banana and its benefits

### Exit Command
The chatbot closes when the user types:

```
bye
```

---

## Technologies Used

- Python 3
- Visual Studio Code (VS Code)
- GitHub

---

## Project Structure

```text
AI-Chatbot-Python/
│
├── chatbot.py
├── README.md
└── requirements.txt
```

### File Description

#### chatbot.py
Contains the complete chatbot source code and conversation logic.

#### README.md
Contains project documentation, project description, features, and instructions.

#### requirements.txt
Contains project dependencies.

Contents:

```txt
No external packages required.
```

---

## How the Chatbot Works

1. The program starts and displays a welcome message.
2. The chatbot waits for user input.
3. User input is converted to lowercase using:

```python
user = input("You: ").lower()
```

4. The chatbot checks the input using `if-elif-else` conditions.
5. If a matching condition is found, the chatbot displays the corresponding response.
6. If no match is found, the chatbot displays a default message.
7. The conversation continues until the user enters `bye`.

---

## Algorithm

1. Start the program.
2. Display the welcome message.
3. Accept user input.
4. Convert input to lowercase.
5. Compare input with predefined conditions.
6. Display the appropriate response.
7. If the user enters `bye`, terminate the program.
8. Otherwise, repeat from Step 3.

---

## Sample Output

```text
Welcome to AI Chatbot
Type 'bye' to exit

You: hello
Bot: Hi!

You: what is your name
Bot: I am an AI chatbot.

You: apple
Bot: Apples are a popular fruit known for their crisp texture and sweet taste.

You: bye
Bot: Goodbye!
```

---

## Advantages

- Easy to understand and implement
- Beginner-friendly project
- No external libraries required
- Simple and lightweight
- Fast execution

---

## Limitations

- Responds only to predefined inputs
- Cannot learn from users
- Limited conversation capability
- No internet connectivity
- Cannot understand complex sentences

---

## Conclusion

This project demonstrates a basic rule-based chatbot using Python. It allows users to interact through text commands and receive predefined responses. The project helps beginners understand loops, conditional statements, user input handling, and simple chatbot development concepts.

---

## Author

Muhammad Zeeshan

Computer Science Student