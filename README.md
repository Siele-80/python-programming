# python-programming
My first python presentation


**1. Title & Objective**
Title: A Beginners toolkit for Python
Objective: This toolkit documents the journey of learning Python for backend development. It highlights a structured progression—from building simple command-line application
The goal is to provide a clear and guide for a beginner to:
Understand core Python concepts
Build practical command-line applications
Why Python? Python is a programming language designed to create software, websites and even apps.
It is used in several industries; Healthcare, Finance, Entertainment, Science & Research, AI, Web Development and Cybersecurity
End goal: To design and develop a functional AI-powered healthcare chatbot using Python


****2. Quick Summary of the Technology**
What is Python?**
Python is a programming language designed to create software, websites and even apps.
**Where is it used?
It is used in several industries; Healthcare, Finance, Entertainment, Science & Research, AI, Web Development and Cybersecurity
**Real-world example:**
Spotify- Spotify uses Python to power its famous "Discover Weekly" playlist — that personalized playlist of 30 songs delivered to you every single day that somehow feels like it was handpicked by someone who knows your music taste perfectly, or someone who stalks ypur daily moves.


**3. System Requirements**
**Operating System:**
Windows (as tested), macOS, or Linux


**Tools & Editors:**
VS Code, VS Code Extensions; Python, PyCharm, Python debugger, Pylance, Google Colab
Packages: pip(comes with Python automatically)


**4. Installation & Setup Instructions**
Step by step

**Step 1: Install Python**
On Windows
Open your browser and type python.org and select the latest version of python
Download it and open
And you’ll see python installer, if you are on windows on your lower left, you will see a checkbox with click add python.
Make sure to check it since it is very important. Go through the logins process.
To confirm it is installed
Follow these simple steps to check if Python is installed
on your Windows computer:
Step 1 — Open the Search Bar
Look at the bottom left of your screen
Click the Magnifier / Search Bar

Step 2 — Open Terminal
Type:    terminal
Press:   Enter
Click:   "Command Prompt" or "Windows Terminal

Step 3 — Check Python Version
Type exactly this and press Enter:
python --version

Step 4 — Read the Result
If Python IS installed you will see:
Python 3.12.0

If Python is NOT installed you will see:
Python was not found

Step 5 — If Python is Not Installed
1. Go to:   python.org/downloads
2. Click:   "Download Python"
3. Run:     the installer
4. Tick:    "Add Python to PATH"
5. Click:   Install Now
6. Repeat:  Steps 1 to 4 above
You should be able to see this
C:\Users\yourname> python --version
Python 3.12. 


**on Linux**
1. Open your terminal
2. Run the following command and follow the on-screen instructions:
   sudo apt update && sudo apt install -y python3 python3-pip

  ** On Mac**
  /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)" && brew install python


**Step 2: Verify the Installation (Crucial Step — Windows, macOS & Linux)**
Windows
Open Command Prompt and run:
python --version
Expected terminal output:
Python 3.12.0

Verify pip Installation
```bash
pip --version
```
Expected terminal output:
```
pip 23.0 from C:\Python312\lib\site-packages\pip (python 3.12)
```

 **macOS**
 Verify pip Installation
```bash
pip3 --version
```
Expected terminal output:
```
pip 23.0 from /usr/local/lib/python3.12/site-packages/pip
```

**Linux**
Verify pip Installation
```bash
pip3 --version
```
Expected terminal output:
```
pip 23.0 from /usr/lib/python3/dist-packages/pip
```

**Install VS Code**
On your preferred browser click https://code.visualstudio.com
Then for each:
Windows  →  .exe installer
Mac      →  .dmg installer
Linux    →  .deb installer
Run the installer
Click through all default options

**Install Python extension**
Open:    VS Code
Press:   Ctrl + Shift + X  (Cmd + Shift + X on Mac)
Search:  Python
Find:    Python by Microsoft Verified
Click:   Install
Wait:    for installation to complete
```
**Select Python interpreter**
```
Press:   Ctrl + Shift + P  (Cmd + Shift + P on Mac)
Type:    Python: Select Interpreter
Press:   Enter
Select:  Python 3.12.0

Run this final check to confirm everything works:

```bash
python3 -c "import sys; print(sys.version)"
```

**5. Minimal Working Example**


name = "Sharon"
age = "22"
subject = "Python"

print("My name is " + name)
print("I am " + str(age) + " years old")
print("I am learning " + subject)


age = int(input("How old are you? "))
if age >= 18:
    print("You are adult pro!")
else:
    print("You are really young!")


Learning Journey

1. Basics

Variables, data types
Conditions and loops
Functions
Variables- "named containers that store data in computer memory"
example name = "John"
 name  ────────── the LABEL on the container
"John" ────────── the DATA stored inside
patient_name = "Mary"
print(patient_name)
string- Raw text wrapped in quotes
example:
print("patient_name")
String- Text and words
Integer- Whole numbers
Boolean- Yes or No values
int()-converts a value into an integer
age = int("23")
print(age)

example: 
patient_name = "Mary"
patient_age  = 25
is_admitted  = True
25 is an integer while true is a boolean value




**6. AI Agents Utilised**
Claude
ChatGpt


**7. AI Prompt Journal**
**Prompt used:** 


Prompt 1 **Guided Learning Phase**
I'm new to Python and fairly new to coding, and I'd like you to be my Python tutor. Instead of giving direct answers, please help me learn by:- Asking guiding questions that help me discover solutions- Breaking down problems into smaller steps- Giving hints when I'm stuck rather than complete solutions- Encouraging me to explain my thinking- Pointing out patterns and connections to previous concepts- Helping me debug by asking me to examine my assumptionsLet's start with [specific coding or python question]"
**AI Helpfulness:** This prompt really helped in that instead of giving direct answers, it challenges me to think through problems using guided questions, helping me build a deeper understanding of concepts. It has improved my ability to break down problems, recognize patterns, and debug code more effectively.


Prompt 2 **Understanding Verification**
I've created this python implementation: 

 age = int(input("How old are you? "))

if age >= 18:
    print("You are adult pro!")
else:
    print("You are really young!")

Could you:
1. Verify if I've followed python best practices? 
2. Explain any improvements I should make?
3. Suggest what I should learn next?give an example so i can practice 
4. Point out any python habits that might be showing in my code?
**AI Helpfulness**
This exercise is useful for building foundational Python skills, including handling user input, type conversion, and conditional logic. It also introduces basic problem-solving and highlights the importance of writing user-friendly and error-resistant code.


Prompt 3 **Real-World Troubleshooting**
"I'm following a tutorial to write Python code. I ran a simple program that asked the user for their age and used int() to convert the input into a number. However, when I entered a non-numeric value like "twenty", the program crashed with a ValueError.

**AI Helpfulness**
This phase focuses on developing practical debugging and problem-solving skills in Python by working through real-world issues encountered during coding. To fix this, I implemented error handling using a try and except block, which allowed the program to handle invalid input.

    age = int(input("How old are you? "))
    if age >= 18:
        print("You are an adult!")
    else:
        print("You are really young!")
except ValueError:
    print("Please enter a valid number.")


**8. Common Issues & Fixes**
| Issue                         | Cause                            | Fix                                 | Example                     |
| ----------------------------- | -------------------------------- | ----------------------------------- | --------------------------- |
| Program crashes on input      | User enters non-numeric value    | Use `try-except` to handle errors   | `int("abc")` → `ValueError` |
| Wrong data type               | `input()` returns a string       | Convert using `int()` or `float()`  | `age = int(input())`        |
| Logic not working as expected | Incorrect condition              | Review and test conditions          | `if age > 18` vs `>= 18`    |
| Code not running              | Indentation error                | Fix spacing (Python is strict)      | Missing indentation in `if` |
| Unexpected output             | Mixing strings and numbers       | Convert types properly              | `"Age: " + str(age)`        |
| Program stops unexpectedly    | Unhandled exceptions             | Add error handling                  | `try-except` block          |
| Variables not defined         | Using variable before assignment | Ensure variables are declared first | `print(age)` before input   |
| Infinite loop                 | Wrong loop condition             | Adjust loop condition               | `while True` without break  |


**9. References**
Youtube Programming with Mosh: https://mosh.link/python-course


w3schools: https://www.w3schools.com/python/python_intro.asp
