**SupportBot** is a terminal-based chatbot written in pure Python that simulates a customer support assistant using rule-based keyword matching.

**How it works:**
The bot scans everything the user types for known keywords and triggers the matching response handler. No AI or external libraries are used — just string matching, conditionals, and logic.

**What it does:**

- Greets the user and asks for their name, then remembers it for the rest of the session
- Detects keywords like "hello", "help", "bye", "order", "refund", "password", "hours", "contact", and more
- Handles 15 conversation topics with detailed, realistic responses
- Auto-extracts order numbers (e.g. ORD98765) from user messages using regex
- Gives context-aware replies to "yes" and "no" based on the active topic
- Tracks consecutive failed matches and escalates to a "contact a human" suggestion
- Shows real-time open/closed status based on the current day and time
- Ends the session gracefully when the user says "bye" or presses Ctrl+C

**Skills it builds:**
String handling, keyword matching, regex, conditional logic, session state management, conversation flow design, and terminal UI formatting with ANSI colors.
