How to Install Python on Windows (Step-by-Step Guide)

Follow these steps to install Python on Windows 10/11.


1. Download Python

    Go to the official Python website: https://www.python.org/downloads/
    Click Download Python 3.x.x (the latest version).





2. Install Python

    Open the Python Installer (the .exe file you just downloaded).
   
    Check the box: ✅ "Add Python to PATH" (VERY IMPORTANT!).
   
    Click "Install Now" and wait for the installation to finish.
   
    Once installed, click "Close".





4. Verify Python Installation
Method 1: Check in Command Prompt

Open Command Prompt (Win + R, type cmd, and press Enter).
    Type:

          python --version

or

          python -V

If Python is installed correctly, it will show something like:

          Python 3.x.x

Method 2: Check in Windows PowerShell
Open PowerShell (Win + X, select Windows PowerShell).
    
  Type:

          python --version

  If installed correctly, it will display the version.

  

4. Install pip (Python Package Manager)

pip should be installed automatically with Python. To verify, run:

          pip --version

If you see a version number, pip is installed. If not, install it with:

          python -m ensurepip --default-pip



5. Install Required Packages

You can now install packages like selenium:

          pip install selenium webdriver-manager




6. Run a Test Python Script

    Open Notepad and type:

          print("Hello, Python is installed!")

Save the file as test.py (select All Files as the type).
Open Command Prompt, navigate to the folder where you saved test.py, and run:

          python test.py

If Python is installed correctly, you should see:

          Hello, Python is installed!
