## MathGestures AI
MathGestures AI is an innovative educational web application that allows users to solve mathematical expressions using hand gestures, without the need for a keyboard, mouse, or touchscreen. Built with OpenCV, cvzone, Streamlit, and integrated with Google's Gemini AI, this project provides a hands-free and interactive learning experience.

## Key Features:
1) Real-time hand gesture detection using webcam input.
2) Virtual canvas to draw math expressions in the air using finger movements.
3) Gesture-controlled actions:
  - Draw (Index finger up)
  - Clear canvas (All fingers except thumb up)
  - Solve (Thumbs up)
4) AI-powered solution generation with step-by-step explanations.
5) Designed for accessibility and kinesthetic learning — ideal for students, educators, and differently-abled users.

## Project Setup
### 1. Python Version
This project requires Python 3.9 to 3.12. If you have Python 3.13 or a different version, it is recommended to install Python 3.12 and create a virtual environment with it.

### 2. Virtual Environment Setup
It's highly recommended to use a virtual environment to manage project dependencies.
1.  **Navigate to your project directory:**
    cd "Your Project Folder"
2.  **Locate your Python 3.12 executable.** If you installed it to the default location, it might be similar to:
    `C:\Users\YOUR_USERNAME\AppData\Local\Programs\Python\Python312\python.exe`
    You can verify its path by opening a new Command Prompt and typing:
    where python
    Look for the path that points to your Python 3.12 installation.
4.  **Create a new virtual environment using Python 3.12:**
    Replace `C:\Users\YOUR_USERNAME\AppData\Local\Programs\Python\Python312\python.exe` with the actual path to your Python 3.12 executable.
    "C:\Users\ANKUSH\AppData\Local\Programs\Python\Python312\python.exe" -m venv venv
5.  **Activate the virtual environment:**
    .\venv\Scripts\activate
    You should see `(venv)` at the beginning of your command prompt, indicating the virtual environment is active.

### 3. Install Dependencies
Once the virtual environment is active, install the required Python packages. You will likely need `streamlit`, `google-generativeai`, `mediapipe`, and `python-dotenv`.
pip install streamlit google-generativeai mediapipe python-dotenv

### 4. API Key Configuration
This project uses an API key, which should be stored in a `.env` file for security and easy management.
1.  **Create a file named `.env`** in the root of your project directory (the same directory as `main.py`).
2.  **Add your Gemini-1.5 Flash API key to the `.env` file** in the following format:
    API_KEY="YOUR_ACTUAL_API_KEY_HERE"
    Replace `YOUR_ACTUAL_API_KEY_HERE` with your actual Google Generative AI API key.

### 5. Run the Project
With the virtual environment active and dependencies installed, you can run the Streamlit application:
streamlit run main.py
This command will open the Streamlit application in your web browser.

## Future Enhancements
- Support for complex math operations (algebra, calculus).
- Mobile version with touchless controls.
- Multilingual support for wider accessibility.
- Integration with AR for immersive learning.
- Gamified interface for students and kids.

⭐ Support
If you found this project helpful or interesting, consider giving it a ⭐ on GitHub!
