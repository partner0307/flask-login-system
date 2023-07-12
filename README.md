# Simple Login System using Flask and SQLite

This repository contains a simple login system built with Flask and SQLite. It allows users to register for an account, log in, and log out.

## Installation

To run this project locally, follow these steps:

1. Clone the repository to your local machine using the following command:

   ```
   git clone https://github.com/your-username/simple-login-system.git
   ```

2. Navigate to the project directory:

   ```
   cd simple-login-system
   ```

3. Create a virtual environment to isolate the project's dependencies:

   ```
   python -m venv env
   ```

4. Activate the virtual environment:

   - On macOS and Linux:
     ```
     source env/bin/activate
     ```

   - On Windows:
     ```
     .\env\Scripts\activate
     ```

5. Create the SQLite database:

   ```
   flask init-db
   ```

6. Run the Flask development server:

   ```
   flask run
   ```

7. Open your web browser and visit `http://localhost:5000` to access the application.

## Usage

This Flask application allows users to register for an account, log in, and log out. Here are the available routes:

- `/register`: Allows users to register for an account.
- `/login`: Allows users to log in to their account.
- `/logout`: Allows users to log out of their account.
- `/dashboard`: A protected route that only logged-in users can access.

When a user registers for an account, their information is stored in the SQLite database. When they log in, their credentials are checked against the database. If they are valid, they are redirected to the dashboard.

If a user tries to access the dashboard without being logged in, they are redirected to the login page.

This is a simple example of how to build a login system using Flask and SQLite. You can customize it further based on your project's requirements.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

If you have any questions or suggestions, feel free to contact us at [email@example.com](mailto:email@example.com).
