# Flask Todo List App

## Prerequisites

Before you begin, ensure you have the following installed:
- Python (version 3.6 or higher)
- pip (Python package installer)

## Installation

1. **Clone the repository:**
    ```sh
    git clone https://github.com/dotcomaki/flaskintroduction.git
    cd flaskintroduction
    ```

2. **Create a virtual environment:**
    ```sh
    python3 -m venv venv
    ```

3. **Activate the virtual environment:**
    - On macOS/Linux:
        ```sh
        source venv/bin/activate
        ```
    - On Windows:
        ```sh
        venv\Scripts\activate
        ```

4. **Install Flask:**
    ```sh
    pip install Flask
    ```

## Setting Up Flask

1. **Create a Flask application:**
    - Create a file named `app.py`:
        ```python
        from flask import Flask

        app = Flask(__name__)

        @app.route('/')
        def hello_world():
            return 'Hello, World!'

        if __name__ == '__main__':
            app.run(debug=True)
        ```

2. **Run the Flask application:**
    ```sh
    flask run
    ```

    You should see output indicating that the server is running, and you can visit `http://127.0.0.1:5000/` in your web browser to see "Hello, World!".

## Additional Resources

- [Flask Documentation](https://flask.palletsprojects.com/)
- [Flask Tutorial](https://flask.palletsprojects.com/en/2.0.x/tutorial/)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
