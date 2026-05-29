# Cybersecurity Awareness Bot (Part 2)

This is the Part 2 expansion of the Cybersecurity Awareness Chatbot. The system has been upgraded from a console application to a Graphical User Interface (GUI) using WinForms, providing a more interactive and user-friendly experience.

---

## New Features in Part 2

- **Graphical User Interface (GUI)**: A modern dark-themed window for interacting with the bot.
- **Dynamic Responses**: The bot now selects from multiple informative responses for common topics to keep interactions varied.
- **Sentiment Detection**: Recognises user emotions like "worried", "curious", or "frustrated" and adjusts responses with empathy and encouragement.
- **Memory & Personalisation**: Remembers the user's name and their favourite cybersecurity topics to provide more relevant advice later in the conversation.
- **Improved Conversation Flow**: Handles follow-up questions ("tell me more", "give me another tip") seamlessly without restarting the topic.
- **Keyword Recognition**: Enhanced detection for specific keywords like "password", "scam", and "privacy".

---

## How to run it

1. Open `CyberBot.csproj` in Visual Studio 2022.
2. Ensure you are on Windows (the app uses WinForms and `System.Media`).
3. Press F5 to build and run.
4. The GUI will launch, play the voice greeting, and display the banner.

---

## Project Structure

The project follows Object-Oriented Programming (OOP) principles and uses generic collections and delegates:

- `MainForm.cs` & `MainForm.Designer.cs` - The new GUI implementation.
- `Program.cs` - Launches the GUI application.
- `ResponseEngine.cs` - Advanced logic for keyword matching, random selection, sentiment detection, and memory recall.
- `UserProfile.cs` - Stores session data including user preferences and interaction history.
- `AudioPlayer.cs` - Handles the voice greeting integration.
- `AsciiArt.cs` - Provides the ASCII banner for the GUI.

---

## What you can ask the bot

Ask about topics like:
- Passwords
- Phishing
- Online Scams
- Privacy Settings
- Malware & Viruses
- Two-Factor Authentication (2FA)
- VPNs

Try saying things like:
- "I'm worried about scams."
- "Tell me more about privacy."
- "Give me another password tip."
- "What do I like?" (Memory check)

---

## Commits & Releases

The project includes a history of meaningful commits and version tags to track development milestones.
