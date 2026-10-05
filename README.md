Login Form
A simple and responsive Login Form created using HTML and CSS.
The design uses a colorful gradient background with a clean white login card.
📌 Project Overview
This project contains a basic login form with:
Email input field
Password input field
Forgot Password text
Log In button
Sign Up link
Gradient background
Centered login card design
🛠️ Technologies Used
HTML5 — for creating the structure of the login form
CSS3 — for styling, layout, colors, spacing, and gradients
📁 Project Structure
Login-Form/
│
├── index.html
├── sign.html
└── README.md
🚀 How to Run
Create a folder named Login-Form.
Save the HTML code as index.html.
If you have a Sign Up page, save it as sign.html.
Open index.html in any web browser.
🎨 Design
The login form includes:
Sky-blue to purple gradient background
White rounded login container
Centered form layout
Styled input fields
Gradient Log In button
Sign Up navigation link
💻 HTML & CSS Code
The main page can be created using the following code:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
            margin: 0%;
            padding: 0%;
            box-sizing: border-box;
        }

        body{
            height: 100vh;
            background: linear-gradient(90deg,skyblue,purple);
            display: flex;
            align-items: center;
            justify-content: center;
        }

        form{
            height: 80%;
            width: 30%;
            background-color: white;
            border-radius: 10px;
        }

        .email,.password,.login{
            width: 80%;
            height: 20%;
            margin: auto;
            margin-top: 5%;
        }

        h1{
            height: 10%;
            margin-top: 5%;
        }

        input{
            margin-top: 5%;
            width: 100%;
            height: 50%;
            text-align: center;
        }

        p{
            margin-top: 5%;
        }

        #login{
            background: linear-gradient(90deg,skyblue,purple);
            border: none;
            border-radius: 10px;
            color: white;
        }

        .password>p{
            color: gray;
            font-style: italic;
        }

        .login>p{
            text-align: center;
        }

        a{
            text-decoration: none;
            font-style: italic;
        }
    </style>
</head>

<body>
    <form action="">
        <h1 align="center">Log In Form</h1>

        <div class="email">
            <label>Email</label>
            <input type="text" placeholder="xyz@gmail.com">
        </div>

        <div class="password">
            <label>Password</label>
            <input type="password" placeholder="abcd@gmail.com">
            <p>Forget Password?</p>
        </div>

        <div class="login">
            <input type="button" value="Log In" id="login">
            <p>Not a Member? <a href="sign.html">Sign Up</a></p>
        </div>
    </form>
</body>
</html>
⚠️ Note
The original code had:
id="\"
For the CSS rule #login to work correctly, it should be:
id="login"
The README code above uses the corrected version.
📄 License
This project is created for learning and educational purposes.# Login-form
