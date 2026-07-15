
# HCP Interaction 

This application is an AI-assisted HCP (Healthcare Professional) Interaction Logging Form. Users can describe an interaction in natural language, and the system automatically extracts important details and fills the form.



## Technologies Used

HTML – Creates the form and chat interface.

CSS – Provides the responsive UI, glassmorphism design, animations, and styling.

JavaScript (Vanilla JS) – Handles all business logic, event handling, parsing, and auto-fill functionality.

Regular Expressions (Regex) – Extracts structured information like HCP name, date, time, topics, and sentiment from user input.

DOM Manipulation – Dynamically updates form fields, chips, follow-up actions, and chat messages.


## Working
*How It Works*

User enters a description in the AI chat.

Example: "Met Dr. Suji today at 3 PM, discussed Prodo-X efficacy, shared brochure, positive response."

The handleSend() function receives the input.

*The parse() function analyzes the text using Regex and keyword matching to identify:*

*HCP Name

*Interaction Type

*Date & Time

*Topics Discussed

*Materials Shared

*Samples Distributed

*Sentiment

*Outcomes

*Follow-up Actions

The extracted data is returned as a JavaScript object (JSON-like structure).

The apply() function automatically fills the corresponding form fields, highlights updated fields, and displays a confirmation message.
## Screenshots


![3](https://github.com/user-attachments/assets/4e7e2989-bd7f-4a7e-83e9-bf8346921003)
![2](https://github.com/user-attachments/assets/4ebab0e5-a5d3-44d7-b332-ef18eddbf02b)
![1](https://github.com/user-attachments/assets/9d1bbffe-987e-4438-a8df-6b6140d631b9)

## Demo

![4](https://github.com/user-attachments/assets/f37e248b-0e6d-4781-9e42-d8fe4c5d14a3)
