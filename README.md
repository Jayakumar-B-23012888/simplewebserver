# EX01 Developing a Simple Webserver
## Date:
27-03-2024
## AIM:
To develop a simple webserver to serve html pages.

## DESIGN STEPS:
### Step 1: 
HTML content creation.

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Serving the HTML pages.

### Step 5:
Testing the webserver.

## PROGRAM:
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Web Development Class</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
    }
    .container {
      max-width: 800px;
      margin: 50px auto;
      padding: 20px;
      background-color: #fff;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }
    h1, h2, h3 {
      text-align: center;
      color: #007bff;
    }
    p {
      text-align: center;
    }
    .btn {
      display: inline-block;
      padding: 10px 20px;
      background-color: #007bff;
      color: #fff;
      text-decoration: none;
      border-radius: 4px;
      transition: background-color 0.3s ease;
    }
    .btn:hover {
      background-color: #0056b3;
    }
    ul {
      list-style-type: none;
      padding: 0;
      text-align: center;
    }
    li {
      display: inline-block;
      margin: 0 10px;
      color: #555;
    }
    img {
      display: block;
      margin: 20px auto;
      max-width: 100%;
      border-radius: 8px;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Web Development Class</h1>
    <p>Welcome to Web Development Class website.</p>
    <p>Start your journey to becoming a web developer today!</p>
    <div style="text-align: center;">
      <a href="#" class="btn">Enroll Now</a>
    </div>
    <hr>
    <h2>Course Outline</h2>
    <ul>
      <li>Introduction to HTML</li>
      <li>Styling with CSS</li>
      <li>JavaScript Fundamentals</li>
      <li>Responsive Web Design</li>
    </ul>
    <hr>
    <h3>About Us</h3>
    <p>We are passionate about teaching web development and helping individuals achieve their goals in the field of technology.</p>
    <img src="development-4536630_640.png" alt="Web Development Class">
  </div>
</body>
</html>


## OUTPUT:

![alt text](output.png)
## RESULT:
The program for implementing simple webserver is executed successfully.
