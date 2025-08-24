This project is a desktop-based typing speed test application built entirely using Java SE and Swing. It simulates a real-time typing challenge where the user types a randomly chosen sentence, and the application calculates key performance metrics like:

CPM – Characters per Minute

WPM – Words per Minute (assuming average word length = 5 characters)

Accuracy – Percentage of correctly typed characters

Suggestion – Feedback based on your typing speed

🛠️ Technologies Used
Technology	Purpose
Java SE (JDK 8+) -	The programming language used to build the logic and structure

Swing (Java GUI) -	For building the GUI components such as JFrame, JTextArea, JLabel

Timer -	Used to display the live countdown of time while the user is typing

Random	- To randomly select a sentence from the array of predefined prompts

BoxLayout and JPanel -	To manage layout in a clean and responsive manner

Fonts, Colors, Insets -	To improve the visual appearance (Dark Mode UI)


📦 What This Project Does

Starts a Typing Game when the user clicks “Start”.

Displays a Random Sentence that the user must type exactly.

Enables a Typing Field where the user enters the text.

Begins a Timer to track how long the user takes to type.

Once typing is completed (Enter key is pressed):

Calculates Time Taken

Calculates Characters Per Minute (CPM)

Calculates Words Per Minute (WPM)

Calculates Accuracy by comparing character-by-character match

![image alt](https://github.com/Deepalirole/Typing-Game/blob/b2ce1c9d28869910d6b4b1ccfbd09b27349324a5/Screenshot%202025-08-23%20202354.png)

Displays a Smart Suggestion based on WPM:

⚠️ WPM < 20 → Needs more practice

⚠️ WPM 20–40 → Decent but can improve

✅ WPM > 40 → Great typing speed!

User can Reset and try again with a new sentence.


📈 Metrics Calculated

Metric	Formula

CPM	Typed Characters / Time (in minutes)

WPM	(Typed Characters / 5) / Time (in minutes)

Accuracy (%)	(Correct Characters / Total Characters) * 100


🎯 Objectives

This project is ideal for:

Practicing typing speed and accuracy

Java Swing GUI development experience

Understanding real-time UI updates and event-driven programming

Building portfolio-worthy desktop applications


👨‍💻 Target Users

Beginner programmers learning Java GUI

Users looking to improve typing speed

Students creating academic Java mini-projects

Developers preparing for interviews where fast typing is a plus




