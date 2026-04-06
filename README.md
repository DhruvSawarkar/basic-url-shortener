# Basic URL Shortener (Python)

## 1. Project Overview  
This project is a basic Python application that shortens lengthy URLs using the TinyURL service. It prompts the user for a URL, validates it with the `validators` library, and generates a shorter version using `pyshorteners`. The program is simple, beginner-friendly, and demonstrates the use of external libraries, input validation, and basic error handling.

## 2. Problem Statement  
Long URLs are often hard to share, remember, and display—especially on platforms with space constraints or formatting issues. This project solves that problem by creating a Python-based tool that takes long URLs, validates them, and returns shortened versions. It helps users generate cleaner, more manageable links while introducing basic concepts of input handling, validation, and API usage.

## 3. Technology Stack  
- **Programming Language:** Python 3.x 
- **Libraries Used:**  
  - `pyshorteners`  
  - `validators`  
- **IDE:** Python IDLE / VSCode / Any Python-supported IDE

## 4. Implementation Steps  
- Prompt user to enter a URL  
- Validate the input using `validators.url()`  
- If valid, shorten the URL using `pyshorteners` and print it  
- Handle invalid inputs and exceptions gracefully


## 5. how to run
1. Clone the repository

2. Install dependencies:

pip install -r requirements.txt

3. Run the script:-

python url_shortener.py
