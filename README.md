# Chatbot in JavaScript
![Alt text](<Screenshot 2023-07-22 at 5.58.28 PM.png>)

This project is a simple chatbot implemented in JavaScript. The chatbot communicates with users by providing responses generated using the OpenAI GPT-3.5 Turbo language model. It is designed to provide helpful assistance based on the user's input.

## Getting Started

To use the chatbot, follow these instructions:

1. Clone the repository to your local machine.
2. Open the `index.html` file in your web browser.

## How to Use

1. Click on the chatbot icon (speech bubble) at the bottom of the page to open the chat window.
2. Type your message in the text input area and press `Enter` or click the send button (paper plane icon) to send your message to the chatbot.
3. The chatbot will respond to your message after a short delay.

## Code Overview

The JavaScript code in `script.js` is responsible for handling user interactions and generating responses from the chatbot.

1. **Initializing the Elements**: The script initializes variables for various DOM elements like the chatbox, chat input, send button, etc.

2. **Creating Chat Elements**: The function `createChatLi` is used to create chat elements (list items) based on the message content and role (incoming or outgoing).

3. **Generating Chatbot Responses**: The `generateResponse` function sends the user's message to the OpenAI API to generate a response. The response is then displayed in the chatbox.

4. **Handling User Input**: The `handleChat` function is triggered when the user sends a message. It takes the input, appends it as an outgoing message to the chatbox, and then generates a response using the `generateResponse` function.

5. **Event Listeners**: Event listeners are set up to handle user interactions such as typing a message, pressing enter, clicking the send button, opening the chatbot window, and closing the chatbot window.

## Additional Notes

- The chatbot UI is designed with a simple layout, including a chat window, input area, and toggle button.
- The chatbot's responses are generated using the powerful GPT-3.5 Turbo model from OpenAI, making it capable of providing more contextually relevant answers.
