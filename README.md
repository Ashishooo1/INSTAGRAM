<!DOCTYPE html>
<html>
<head>
<style>
body {
 font-family: Arial, sans-serif;
}

form {
 width: 300px;
 margin: 0 auto;
}

form h1 {
 background-color: #00BFFF;
 color:  red;
 padding: 20px;
 text-align: center;
 font-size: 1.5em;
}

form label {
 display: block;
 padding: 10px;
 font-size: 0.9em;
}

form input[type="text"], form input[type="number"] {
 width: 100%;
 padding: 10px;
 margin: 10px 0;
 box-sizing: border-box;
}

form input[type="submit"] {
 background-color: #4CAF50;
 color: white;
 padding: 10px 20px;
 margin: 10px 0;
 border: none;
 cursor: pointer;
 width: 100%;
 font-size: 0.9em;
}
</style>
</head>
<body>

<form action="">
 <h1>Attendance Form</h1>
 <label for="fname">First Name:</label>
 <input type="text" id="fname" name="fname">
  
 <label for="lname">Last Name:</label>
 <input type="text" id="lname" name="lname">
  
 <label for="contact">Contact Number:</label>
 <input type="number" id="contact" name="contact">
  
 <label for="email">Email:</label>
 <input type="text" id="email" name="email">
  
 <label for="dob">Date of Birth:</label>
 <input type="date" id="dob" name="dob">
  
 <label for="event">Event Name:</label>
 <input type="text" id="event" name="event">
  
 <label for="time">Time of Event:</label>
 <input type="time" id="time" name="time">
  
 <input type="submit" value="Submit">
</form>

</body>
    </html>