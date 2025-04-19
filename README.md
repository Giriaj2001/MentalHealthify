Steps to setup:

Install the following packages by running the "Setup.bat" file provided in the serenescreen folder by double clicking on it.
Anaconda3-2024.02-1-Windows-x86_64
TesseractOcrSetUp
OllamaSetup
Set the following paths for Anaconda3:
Add "C:\Users<Username>\anaconda3" to the system path variables.
Add "C:\Users<Username>\anaconda3\Scripts" to the system path variables.
Run the "Dependencies.bat" file provided in the serenescreen to initialize conda.
Run the "Dependencies1.bat" file provided in the serenescreen to create conda environment.
Run the "Dependencies2.bat" file provided in the serenescreen to activate conda environment and install the dependencies.
Ways to run:

Using "Run.bat":
Run the "Run.bat" file provided in the serenescreen to activate conda environment and start running the application.
Using command prompt:
At serenescreen directory in command prompt, give cmd = "conda activate serenescreen" to activate serenescreen.
Then, run the cmd = "streamlit run app.py" to run the application.
