                      1.Mini Calculator
Create a mini calculator application, which has following functionalities
Addition
Subtraction
Division
Multiplication
Your app should have
Two input boxes which should take two numbers from the user.
Four Buttons with following text content
Add
Subtract
Divide
Multiply
When user enter 2 and 4 and clicks on multiply button, an alert should come with 8 as ans
When user enter 8 and 4 and clicks on Divide button,an alert should come with 2 as ans



                            2.onClick Event
Copy the given template in events.html
<!DOCTYPE html>
<html>
<head>
<title>Events</title>
</head>
<body>
<button> Ring Bell </button>
</body>
</html>
<script>
// Write js here
</script>
Add an event to button such that, whenever user clicks on button, a message saying that
"Please open the door" should be shown in console



                                    3.Alert Scam
Copy the given template in scam.html
<!DOCTYPE html>
<html>
<head>
<title>Events</title>
</head>
<body>
<img
src="https://miro.medium.com/max/1400/1*mdcu3Ku9r44HMtraHUqu5g.jpeg"
alt=""
/>
</body>
</html>
<script>
// Write js here
</script>
Add an event to image such that, whenever user clicks on that image, an alert should be
displayed saying that "The website you are going to visit may harm your computer, do you
still want to redirect?"



                                        4.Show Quote
Copy the given template in quote.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>Document</title>
</head>
<body>
<button>Show Quote in console</button>
<p id="quote">Talk is cheap Show me the code</p>
</body>
</html>
<script>
//write js here
</script>
On clicking on button, display the quote given in p tag in console



                                5.Login and Logout basic
Copy the given template in login.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>Document</title>
</head>
<body>
<h1>This example demonstrates how we can change text content when
clicking on button</h1>
<hr>
<h1 id="display">Click on Login to continue</h1>
<button onClick="login()">Login</button>
<button onClick="logout()">Logout</button>
</body>
</html>
<script>
function login() {
//complete this function
}
function logout() {
//complete this function
}
</script>
Complete the given functions such that
When Login button is clicked, text in h1 tag should be changed to "Login Success"
When Logout button is clicked, text in h1 tag should be changed to "Logout Success"
Also check in dev tools for the change




                                6.Application
Copy the given template in masai.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>Document</title>
</head>
<body>
<h1>School Application</h1>
<p>Enter Your name and gender to apply for school</p>
<h2 id="display">Display entered name and gender here</h2>
<hr>
<input type="text" id ="name" placeholder="Enter your name">
<select id="gender">
<option value="Male">Male</option>
<option value="Female">Male</option>
</select>
<button>Apply</button>
</body>
</html>
<script>
</script>
Design an application such that when user clicks on Apply button, he should take entered
values from both input and select tags and display it in h2 tag with id "display.



                                    7.BMI Calculator
Create an application which calculates BMI (Body Mass Index)
Your app should have 2 input boxes
Take weight in kgs from user
Take height in meters from user
Based on entered height and weight calculate BMI of that person
Here is the formula for manually calculating BMI BMI = (weight) / (height *
height)
From the obtained BMI result, display whether the person is
UnderWeight - bmi <= 18.4
Normal Weight - bmi >= 18.5 && bmi <= 24.9
Overweight - bmi >= 25 && bmi <= 29.9
Obese - bmi >= 30
Hint: use If conditions



                            8.Leaderboard
Create the file leaderboard.html so that it looks similar to the image below
Functionality
By clicking on any number it shows up in the score box joined to any previous
numbers already present (Eg: To enter a score of 423 you have to press 4 2 3)
Once the button ENTER is pressed the score gets compared with the MIN and
MAX boxes, if the current score is less than the MIN score it gets updated with the
current score, if the current score is greater than the MAX score it gets updated
with the current score
The SCORE box will be reset with empty value