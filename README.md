Welcome to myLLM Chat, a simple and private interface for interacting with your own local Large Language Models (LLMs). This guide will walk you through setting up the application, connecting to your model, and using its features.

🚀 Getting Started: 3 Simple Steps
To begin, you need to have a local LLM server running. A popular choice is LM Studio, which makes it easy to download and serve models.

Step 1: Run Your Local LLM Server
Open LM Studio (or your preferred server software).

Go to the Local Server tab (usually marked with a </> icon).

Select your desired model at the top.

Click Start Server.

You should see a message indicating that the server is running and listening on a specific IP address and port, typically localhost:1234.

Step 2: Open the HTML File
Simply double-click the lma12.html file. It will open directly in your default web browser (like Chrome, Firefox, or Safari). Because the app runs entirely on your machine, no internet connection is needed, and your conversations remain completely private.

Step 3: Connect to the Server
In the myLLM Chat interface, you will see fields for Server IP and Port on the top-left.

These are pre-filled with localhost and 1234, which are the standard defaults for LM Studio.

Click the Connect button.

If successful, the button will turn into a "Disconnect" button, and you will see your loaded model appear in a dropdown menu. You are now ready to chat.

✨ Core Features
Here’s a breakdown of the application's functionalities.

1. Managing Chats
New Chat: Click the + New Chat button to start a new, clean conversation.

Switching Chats: Your conversation history is listed on the left. Simply click on any chat to view it. The active chat is highlighted.

Deleting Chats: Hover over a chat in the list and click the red × button to permanently delete it.

2. The Chat Interface
Model Selection: If your server has multiple models loaded, you can switch between them using the dropdown at the top of the main chat area.

Code Blocks: The application automatically detects and formats code in the model's responses. A Copy button is provided for convenience.

Message Stats: For each response from the model, you'll see a few performance metrics:

t/s: Tokens per second (how fast the response was generated).

tokens: The number of tokens in that specific response.

ms: The total time in milliseconds for the response.

3. Token Counter
Located in the bottom-right corner, the token counter tracks the total tokens used for the entire current conversation.

Source: This number comes directly from the API's usage data after each message, ensuring it is an accurate reflection of your model's work.

Limit: It is displayed as [current tokens] / 4096, where 4096 is the context window limit set in the application. This helps you keep track of how close you are to the model's context limit for the ongoing chat.

###💡 Tips for Best Use

Privacy First: Since this file runs locally and connects to a local server, none of your conversation data ever leaves your computer.

No Installation Needed: This is a standalone file. You can save it anywhere on your computer and run it without any installation.

Browser-Based: All modern browsers are supported. If you encounter any display issues, make sure your browser is up to date.
