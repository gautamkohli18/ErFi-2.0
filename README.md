ErFi 🚀

<br>

ErFi (Error Finder) is your ultimate desktop tool for finding and identifying specific sentences in Excel files with ease. With the tagline "Find Smart. Solve Smart.", ErFi is here to make your life easier and your error-hunting missions smoother. 🕵️‍♂️

Features 🌟<br>
Read and Search: Load prompts from an input Excel file and search for them in a main Excel file. No more manual searching—let ErFi do the heavy lifting! 💪
Results in Style: View your search results in a neat table format. Because who doesn’t like pretty tables? 📊
Standalone Goodness: Create an executable so that your tech-challenged friends can use it without needing to install anything. 🧑‍💻
Requirements 📦
Python 3.7 or higher
Required Python packages: openpyxl, tkinter, pyinstaller (for making standalone executables)
Installation 🎉
Install Python Packages
Get the necessary Python packages with pip: <br> <font color="green">
pip install openpyxl pyinstaller</font>
Create a Standalone Executable
No Python, no problem! Make your app into a standalone executable with PyInstaller:

Install PyInstaller (if not already installed):<br> <font color="green">
pip install pyinstaller</font>

Create the executable:<br> <font color="green">
pyinstaller --onefile --windowed app.py </font>

Find your shiny new executable in the dist folder. ✨

Usage 🚀
Run the Application

Double-click the standalone executable to launch ErFi.

Alternatively, run the script directly if you have Python installed:

python app.py

Using ErFi

Main Excel File Path: Hit "Browse" to select the main Excel file where ErFi will work its magic. 🧙‍♂️
Input Excel Sheet Name: Enter the sheet name from which ErFi will read the prompts. 📝
Load Input File: Click this to start the search and let the results roll in.
View Results

Check out the results in a stylish table. ErFi brings you the details you need, like Annotator ID, Name, Prompt, Response 1, and Response 2.
Troubleshooting 🤔
No 'Prompt' Column Found: Double-check that your input file has a "Prompt" column. Without it, ErFi might get a bit grumpy. 😅
File Not Found: Make sure the file paths are correct and that the files are actually there. No file, no fun! 🎉
Application Errors: Ensure all required packages are installed and that you're running the app in a compatible Python environment.
Contributing 🤝
Want to make ErFi even cooler? Fork the repo, make your changes, and submit a pull request. We love contributions! 💖

License 📝
This project is licensed under the MIT License - check out the LICENSE file for the details.

