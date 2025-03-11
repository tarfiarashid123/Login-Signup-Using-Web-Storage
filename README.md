Login & Signup System Using Web Storage

Overviewliminating the need for a backend database.

Features

This is a simple Login and Signup system implemented using Local Storage and Session Storage in JavaScript. The project includes three main pages: Signup, Login, and Dashboard. User authentication is managed through Web Storage, e

User Signup: New users can register by providing a username, email, and password.

User Login: Registered users can log in using their credentials.

Session Management: Users remain logged in using Session Storage.

Local Storage: Stores user credentials securely (hashed for better security).

Dashboard Access: Only logged-in users can access the dashboard.

Logout Functionality: Users can log out to end their session.

Technologies Used

HTML: Structure of the web pages

CSS: Styling and responsiveness

JavaScript: Functionality and user authentication

Local Storage & Session Storage: Managing user data

How to Use

1. Clone the Repository

 git clone https://github.com/tarfiarashid123/Login-Signup-Using-Web-Storage.git

2. Open the Project

Navigate to the project folder

Open index.html in a browser

3. Signup Process

Enter a username, email, and password

Click Signup (Data is stored in Local Storage)

4. Login Process

Enter registered email and password

Click Login (Session starts)

5. Dashboard & Logout

After login, the user is redirected to the dashboard

Click Logout to end the session

File Structure

📂 Login-Signup-Using-Web-Storage
 ├── 📄 index.html   (Login Page)
 ├── 📄 signup.html  (Signup Page)
 ├── 📄 dashboard.html  (Dashboard Page)
 ├── 📄 style.css   (CSS Styling)
 ├── 📄 script.js   (Main JavaScript File)
 ├── 📄 README.md   (Project Documentation)

Future Improvements

Implement password hashing for better security

Add form validation for better user input handling

Improve UI/UX with better design

Implement forgot password functionality

License

This project is open-source and available under the MIT License.

💡 Contributions are welcome! Feel free to submit a pull request.
