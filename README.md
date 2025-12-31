Beginner Python Programming
This repository contains fundamental Python concepts and practical exercises designed for beginners. It covers everything from basic data types to web development basics with FastAPI.

📂 Project Structure
The repository is organized into Jupyter Notebooks and specialized folders for easy learning:

📔 Core Python Notebooks
Data_types: Understanding strings, integers, floats, and booleans.

Conditional_Statement: Working with if, elif, and else logic.

Loops: Master for and while loops.

Functions: Basics of defining and calling functions.

Higher_order_function: Introduction to advanced function concepts.

File_handling_json: Learning how to read/write files and work with JSON data.

Operators: Math, logical, and comparison operators.

🌐 Web Development (API)
API & FastAPI: Introduction to building RESTful APIs using the FastAPI framework.

Examples: Includes scripts for GET, POST, PUT, and DELETE requests.

🚀 Getting Started
Prerequisites
To run these files, ensure you have Python installed. It is recommended to use Miniconda to manage your environments.

Bash

# Example of activating a conda environment
conda activate Intermediate_python
Installation
Clone the repository:

Bash

git clone https://github.com/MudaserShah/Beginner-python.git
Install required libraries:

Bash

pip install fastapi uvicorn
Running the API
To run the FastAPI examples (like hello_world.py):

Bash

uvicorn hello_world:app --reload
Then visit http://127.0.0.1:8000 in your browser.

🛠️ Tools Used
Language: Python 3.10+

Editor: Visual Studio Code

Environment Manager: Miniconda

Framework: FastAPI