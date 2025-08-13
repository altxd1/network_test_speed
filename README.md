🛰️ NetSpeed – Legacy Network Speed Testing & Analysis Tool
By Abdelmonaim Aaouadou

NetSpeed is a command-line network speed testing and analysis tool that I originally developed during my first month of programming. As one of my earliest full-scale software projects, NetSpeed holds a special place in my learning journey, marking the transition from beginner scripts to a full-featured utility.

🛠️ About the Project
NetSpeed was built to:

Run internet speed tests (ping, download, upload)

Store results in a local SQLite database

Analyze historical data and help users find optimal usage times

Display and mask public/local IP addresses

Notify users with results via desktop notifications

While it was a valuable hands-on exercise in using external APIs, databases, and terminal UX, this version represents a legacy implementation.

🧠 Lessons & Growth
Since creating NetSpeed, I've:

Learned to structure applications with OOP (Object-Oriented Programming) and modular design

Gained experience with clean code practices, exception handling, and modern UIs

Worked with frameworks like Tkinter, FastAPI, and PyQt for richer user experience

As such, modifying this version would be less efficient than redesigning it entirely using cleaner architecture and modern Python best practices.

🔁 Future Plans
I'm planning to:

Rebuild NetSpeed 2.0 from scratch with:

A GUI interface for easier navigation

Real-time graphs for historical speed data

Modular codebase with class-based design


A setup installer for Windows & Linux



####How to install requirements 

# network_test_speed
1. Clone or Download the Script
Make sure you have Python 3 installed, then download the script or clone the repository.

2. Install Required Packages
Open a terminal or command prompt and run:
  pip install requests speedtest-cli plyer

3. Run the Application
Navigate to the folder and run:
  python NetSpeed_FIXED_Abdelmonaim.py

 Platform Compatibility
✅ Windows (fully compatible, includes terminal color and title)

⚠️ Linux/macOS (functional, but some system commands like os.system("color") and title changes may not work)

📌 Notes
Make sure you're connected to the internet when launching the app.

IPv6 detection may vary based on your ISP/router setup.

You can unmask IPs if needed for debugging or logs.
