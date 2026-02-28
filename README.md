
# ELIZA-Style Procrastination Support Chatbot

## 📌 Overview

This project is a rule-based conversational agent implemented in Python, inspired by the classic ELIZA architecture (created by Joseph Weizenbaum). Tailored specifically to address productivity issues, this chatbot acts as a digital companion to help users manage procrastination, overcome creative blocks, and regain focus.

The core logic and dialogue state management methodologies are heavily inspired by the concepts taught in Jurafsky & Martin's renowned textbook, _Speech and Language Processing_.

## ✨ Features

-   **Regex-Based Pattern Matching:** Utilizes Regular Expressions (Regex) to analyze user input, identify key phrases related to procrastination, and determine the structural intent of the sentence.
    
-   **Keyword Transformation:** Implements dynamic perspective-shifting (e.g., transforming "I am" to "you are", "my" to "your") to simulate active listening and empathetic, context-aware responses.
    
-   **Dialogue State Management:** Maintains conversation flow without relying on modern deep learning or LLMs, showcasing a strong understanding of foundational NLP, rule-based systems, and string manipulation.
    
-   **Task-Oriented Responses:** Specifically designed rules to encourage users to break down tasks, reflect on their delaying habits, and take actionable steps.
    

## 🛠️ Technologies Used

-   **Language:** Python 3.x
    
-   **Core Libraries:** `re` (Regular Expressions), `random`
    
-   **Domain:** Natural Language Processing (NLP), Rule-based AI
    

## 🚀 How to Run

1.  Clone this repository to your local machine:
    
    ```
    git clone [https://github.com/dovh11/ELIZA-Style-Procrastination-Support-Chatbot.git](https://github.com/dovh11/ELIZA-Style-Procrastination-Support-Chatbot.git)
    
    ```
    
2.  Navigate to the project directory:
    
    ```
    cd ELIZA-Style-Procrastination-Support-Chatbot
    
    ```
    
3.  Run the python script:
    
    ```
    python3 chatbot.ipynb
    
    ```
    

## 💬 Example Conversation

> **User:** I have a big assignment due tomorrow but I keep watching videos.
> 
> **ELIZA:** Why do you think you keep watching videos instead of working on your big assignment?
> 
> **User:** Because the assignment is too difficult and I am overwhelmed.
> 
> **ELIZA:** I understand. When you feel overwhelmed, what is the smallest first step you can take right now?
> 
> **User:** I guess I could just open the document and write the title.
> 
> **ELIZA:** That sounds like a great start. Tell me more about how you plan to tackle it after writing the title.

## 📚 References

-   Jurafsky, D., & Martin, J. H. _Speech and Language Processing_. (Concepts on rule-based NLP and ELIZA architecture).
    

_Developed by Vu Huy Do as part of an academic exploration into foundational NLP methodologies._
