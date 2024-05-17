# Project Setup Guide

Follow these steps to set up and run the project on your local machine.

## Step 1: Download and Extract

1. Download the project zip file.
2. Extract the contents to your desired location.

## Step 2: Install Python and Required Libraries

1. Ensure Python is installed on your machine. You can download it from [python.org](https://www.python.org/).
2. Install the required libraries by running the following command in your terminal:
    ```bash
    pip install -r requirements.txt
    ```

## Step 3: Navigate to `views.py`

1. Open the extracted project folder.
2. Navigate to `project -> Django application -> mlapp -> views.py`.

## Step 4: Update Paths

1. Open `views.py` in your preferred code editor.
2. Modify the file paths according to your PC's directory structure.

## Step 5: Open Terminal in VS Code

1. Open Visual Studio Code (VS Code).
2. Open the project folder in VS Code.
3. Open a new terminal window in VS Code by selecting `Terminal -> New Terminal` from the menu.

## Step 6: Navigate to Django Application

1. In the terminal, navigate to the Django application directory by running:
    ```bash
    cd project/Django application
    ```

## Step 7: Run the Server

1. In the terminal, run the following command to start the Django development server:
    ```bash
    python manage.py runserver
    ```

You should now be able to access the application by navigating to `http://127.0.0.1:8000/` in your web browser.
