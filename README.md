Cybersecurity Awareness Console Application

 Overview
This is a C# console application designed to educate users about cybersecurity best practices. The program provides an interactive experience with an AI assistant that guides users through various topics including password safety, phishing awareness, and safe browsing techniques.

Features
- Interactive AI assistant that personalizes the experience using the user's name
- ASCII art introduction with audio greeting
- Three main educational sections:
  - Password Safety
  - Phishing Awareness
  - Safe Browsing
- Menu-driven interface with error handling
- Color-coded console output for better user experience
- Educational content with multiple sub-topics for each section

Prerequisites
- .NET Framework or .NET Core installed
- Windows operating system (for audio playback functionality)
- Audio file "Greetiings.wav" located at: `C:\Users\tshia\source\repos\ProgA1_ST10070515_PartOne\`

Installation
1. Clone or download the repository
2. Open the solution in Visual Studio
3. Ensure the audio file path is correct or modify it in the `intro()` method
4. Build and run the application

Usage
1. Launch the program
2. Enter your name when prompted
3. Interact with the AI assistant by:
   - Typing initial greetings (hi, hello, etc.)
   - Asking about its purpose
   - Requesting available topics
4. Select topics by entering numbers (1-4) from the main menu
5. Explore sub-topics within each section
6. Exit the program by selecting option 4

Program Structure
- `Main()`: Entry point and initial setup
- `intro()`: Displays ASCII art and plays welcome audio
- `phase1()`: Handles initial user interaction
- `phase2()`: Main menu system
- `passwordSafety()`: Password security education
- `phishing()`: Phishing awareness education
- `safe()`: Safe browsing education
- Helper methods:
  - `Margins()`: Creates visual separators
  - `TitlesUI()`: Formats section titles
  - `terminator()`: Handles program exit

Error Handling
- Validates user input
- Provides retry options for invalid selections
- Handles audio playback errors
- Uses try-catch blocks for robust operation

Limitations
- Audio file path is hardcoded
- Windows-specific audio playback
- Console-based interface only
- Limited initial interaction commands

Future Improvements
- Add more cybersecurity topics
- Implement cross-platform audio support
- Add configuration file for paths
- Include more interactive elements
- Add progress tracking

Contributing
Feel free to submit pull requests or issues for:
- Bug fixes
- New features
- Content additions
- UI improvements


