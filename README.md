# Flask Time and Time Zone Web App

This Flask web application demonstrates how to display the current time and time zone information.

## Features
- Displays the current time dynamically.
- Shows the time zone of the server where the application is hosted.

### Technologies Used

- Python
- Flask
- HTML
- CSS (minimal)
- JavaScript (minimal)
### Installation

1. **Clone the repository:**

    Open your terminal and run the following command to clone the repository:

    ```bash
    git clone https://github.com/ahmed-m-awad/Time-zone-web-app.git
    ```


2. **Navigate to the project directory:**

    ```bash
    cd Guessing_Game-ExpressJS
    ```

3. **Install the dependencies:**

    Run the following command to install all the necessary dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. **Start the project:**

    After the dependencies are installed, start the project using:

    ```bash
    flask run
    ```

    This will start the project and you should see output indicating that the project is running.

## Usage

The homepage (/) displays the current time in a specified format (e.g., HH:MM
).
The time zone information is also displayed on the homepage, showing the time zone of the server where the application is hosted.

## WSGi
```bash
gunicorn wsgi
```