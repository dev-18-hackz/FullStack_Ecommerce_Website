# FullStack_Ecommerce_Website

## Overview
This is a simple e-commerce platform built using Flask. It provides users with essential e-commerce functionalities such as user registration, login, product management, cart operations, and order placement.

## Prerequisites
Before running this project, ensure the following prerequisites are met:

1. Python: Install Python from the official Python website if it is not already installed on your system.

2. SQLite: SQLite is bundled with Python by default. If it's missing, install it using pip:
```sh
pip install sqlite3
```

## Installation
Follow these steps to set up and run the project locally:

1. Clone the Repository: Clone the project repository to your local machine:
   ```sh
    git clone https://github.com/yourusername/ecommerce-platform.git
    cd ecommerce-platform
    ```

2. Install the required Python packages using pip:

    ```sh
    pip install -r requirements.txt
    ```

3. Create a SQLite database and replace `ecommerce.db` with your desired database name in the `init_
db()` function in `app.py`.

## Running the Application
1. Start the Application: Run the application using the following command:
    ```sh
    python app.py
    ```

2. Open your web browser and navigate to `http://127.0.0.1:5000/`. You should see a login page 
where you can create an account or log in with an existing one.
