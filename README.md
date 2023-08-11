# Silver Chatbot User Interface (Svelte)

Welcome to the Silver Chatbot User Interface built using the Svelte framework. This interface allows users to engage with the Silver Chatbot, powered by OpenAI, in a seamless and interactive manner.

## Overview

The provided Svelte component offers an intuitive and user-friendly chat interface where users can input queries and receive responses from the chatbot. The chatbot's responses are powered by OpenAI's GPT-like model.

## How to Run

1. Clone this repository to your local machine.
2. Navigate to the directory containing the Svelte component (`Chatbot.svelte`).
3. Install the required dependencies using your preferred package manager (`npm install` or `yarn install`).
4. Run the Svelte development server using the command `npm run dev` or `yarn dev`.
5. Access the Silver Chatbot User Interface in your web browser at `http://localhost:5000` (default port).

## Main Functions

### `handleSubmit()`

This function is called when the user submits a message. It initializes an event source to send and receive messages between the frontend and backend.

### `handleError(err)`

This function handles errors during the communication and resets the chat state if an error occurs.

### `scrollToBottom()`

This function scrolls the chat display to the bottom, ensuring the latest messages are always visible.

## Chat Display

The chat display is implemented using the `ChatMessage` component. It displays the conversation history, including messages from the user, chatbot, and loading indicators.

## User Interaction

1. Type your message in the input field at the bottom of the chat display.
2. Click the "Send" button to submit your message to the chatbot.

