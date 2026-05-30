# PROG6221POE

AZEEBOT – Cybersecurity Awareness Chatbot

Project Overview

AZEEBOT is a C# Windows Forms (WinForms) chatbot designed to educate users about cybersecurity awareness. It provides interactive guidance on topics such as phishing, password safety, online scams, privacy, safe browsing, and two-factor authentication.
  
The chatbot includes dynamic responses, memory, sentiment detection, and a graphical user interface to create an engaging learning experience.

------------------------------------------------------------------------------------------------------------------------------------------------------

Purpose of the Project

The purpose of AZEEBOT is to:
- Educate users about cybersecurity threats
- Simulate a conversational chatbot experience
- Demonstrate object-oriented programming (OOP) concepts
- Implement GUI-based interaction in C#
- Apply memory, sentiment detection, and keyword recognition
========================================================================================================================================================

Technologies Used

- C# (.NET Framework / WinForms)
- Visual Studio
- Object-Oriented Programming (OOP)
- Dictionaries & Lists (Collections)
- Delegates
- System.Media (Audio playback)

======================================================================================================================================================

Features

1. Graphical User Interface (GUI)
   
- Built using Windows Forms
- Clean and user-friendly layout
- RichTextBox chat display
- Input textbox and SEND button
- BEGIN button to start session
- ASCII art branding display
- Voice greeting on startup

-----------------------------------------------------------------------------------------------------------------------------------------------

2. Keyword Recognition
   
The chatbot recognises cybersecurity-related keywords such as:

- phishing
- password
- scam
- privacy
- safe browsing
- 2FA

It responds with relevant cybersecurity advice based on detected keywords.
--------------------------------------------------------------------------------------------------------------------------------------------------

3. Random Responses
   
AZEEBOT uses randomised responses to keep conversations dynamic and engaging. Multiple responses exist for each cybersecurity topic.

---------------------------------------------------------------------------------------------------------------------------------------------------

4. Conversation Flow
   
The chatbot maintains topic continuity. It can respond to follow-up inputs such as:

- "tell me more"
- "another tip"
- "continue"

-------------------------------------------------------------------------------------------------------------------------------------------------------

5. Memory & Recall
   
AZEEBOT remembers:

- User's name
- Favourite cybersecurity topic
- Previous interactions

Example:

- "I am interested in privacy"
- "What do you remember about me?"
  
--------------------------------------------------------------------------------------------------------------------------------------------------------

6. Sentiment Detection
   
The chatbot detects emotions such as:

- worried
- curious
- frustrated
- confused

It responds with supportive and context-aware cybersecurity advice.

---------------------------------------------------------------------------------------------------------------------------------------------------------

7. Voice Greeting
   
A WAV audio file is played when the chatbot starts using the AudioPlayer class.

---------------------------------------------------------------------------------------------------------------------------------------------------------

8. ASCII Art
The chatbot displays a custom ASCII art banner at startup using the AsciiArt class.
---------------------------------------------------------------------------------------------------------------------------------------------------------

9. Delegates
A custom delegate (BotResponseDelegate) is used for sentiment detection and method referencing.

-----------------------------------------------------------------------------------------------------------------------------------------------------
Project Structure

PROG6221POE/
│
├── Form1.cs              // GUI and user interaction
├── ChatbotEngine.cs      // Chatbot logic (AI behaviour)
├── AudioPlayer.cs        // Voice greeting system
├── AsciiArt.cs           // ASCII branding
├── Program.cs            // Application entry point

---------------------------------------------------------------------------------------------------------------------------------------------
How to Run the Project

1. Open the solution in Visual Studio
2. Restore NuGet packages if required
3. Build the solution
4. Run the application (Start Debugging / F5)
5. Enter your name and click BEGIN
6. Start chatting with AZEEBOT

----------------------------------------------------------------------------------------------------------------------------------------------------

Requirements

- Windows OS
- Visual Studio 2019 or later
- .NET Framework / .NET Windows Forms support
- WAV audio file placed in project directory

-----------------------------------------------------------------------------------------------------------------------------------

Future Improvements

- Add AI/NLP integration
- Improve UI design with modern controls
- Add chatbot database storage
- Expand cybersecurity topics
- Add speech-to-text input
  
------------------------------------------------------------------------------------------------------------------------------------
Author

Name: Mmabatho Vilakzi

Student Number: ST10460268

Module:Programming(PROG6221) POE Part 2

------------------------------------------------------------------------------------------------------------------------------------------------------------------
Notes

This project was developed as part of an academic POE assignment focusing on:

- GUI development
- OOP principles
- Dynamic responses
- Memory and sentiment detection
- Use of delegates and generic collections

------------------------------------------------------------------------------------------------------------------------------------------------------------------
Reference list:

-Wikipedia, 2026. HTTPS. [online] Available at: https://en.wikipedia.org/wiki/HTTPS [Accessed 13 April 2026].
Comodo cWatch, 2026. Check Website Reputation / Site Scan. [online] Available at: https://cwatch.comodo.com/site-scan/check-website-reputation.php [Accessed 12 April 2026].
-Boston University, 2026. How to identify and protect yourself from an unsafe website. [online] Available at: https://www.bu.edu/tech/support/information-security/security-for-everyone/how-to-identify-and-protect-yourself-from-an-unsafe-website/ [Accessed 11 April 2026].
-McAfee, 2026. 8 ways to know if online stores are safe and legit. [online] Available at: https://www.mcafee.com/learn/8-ways-to-know-if-online-stores-are-safe-and-legit/ [Accessed 10 April 2026].
