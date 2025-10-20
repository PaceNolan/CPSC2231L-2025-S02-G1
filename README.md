# CPSC2231L-text-analysis
Text Analysis Project – Milestone 1

Course: CPSC 2231L – Programming Workshop Lab
Semester: Fall 2025
Institution: Fairfield University, School of Engineering and Computing

📘 Overview

This project is part of the semester-long software development assignment for CPSC 2231L.
The goal of Milestone 1 is to build the foundation for a text analysis tool that preprocesses and analyzes multiple text articles about the same topic.

The program currently performs the following:

Loads multiple text files (articles) from a folder.

Removes stop words (common words like “and”, “the”, “but”, etc.).

Calculates basic text statistics (total words, unique words, word frequency).

Ranks words by their frequency of occurrence.

All preprocessing is done for one topic (folder) at a time.

🧱 Project Structure

The project uses an object-oriented architecture with at least three classes:

File	Description
Main.java	Entry point of the program. Handles user input and coordinates analysis.
FileLoader.java	Loads all text files from a specified directory (topic folder).
StopWords.java	Stores and filters out common English stop words.
ArticleStats.java	Processes the text to calculate statistics and generate ranked word frequencies.
⚙️ How to Run

Place your article .txt files in a folder (one topic per folder).

Ensure the folder path is correctly referenced in Main.java.

Compile all Java files:

javac Main.java FileLoader.java StopWords.java ArticleStats.java


Run the program:

java Main


The program will:

Read all text files from the specified directory.

Remove stop words.

Display word counts, unique word counts, and top frequent words.

🧮 Example Output
Analyzing topic: Electric Cars
Total Words: 3256
Unique Words: 972
Top 10 Most Frequent Words:
1. car - 124
2. battery - 98
3. electric - 87
4. model - 75
...

👥 Group Members

Nolan: Implemented FileLoader.java

Kevin: Implemented StopWords.java

Sion: Implemented ArticleStats.java and Main.java integration

UML Diagram:
<img width="2198" height="524" alt="UML Diagram for CPSC2231L (2)" src="https://github.com/user-attachments/assets/750eb8a0-04e4-4170-ac80-4b4ff42a0d09" />

