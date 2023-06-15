# Ex.08 Customer Registration Form
## AIM
  To write a program in JavaScript for creating a customer registration form for an agro-based company.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define different functions to register the customers based on their qualifications.

### STEP-3
  Using form elements to create the registration details of a customer.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
<!DOCTYPE html>
<html lang="en">

<head>
  <title>Registration Form</title>
  <script type="text/javascript" src="registration.js"></script>
</head>

<body onload="customerRegistrationForm()" style="background-color: mediumpurple;">
  <h1>Customer Registration Form</h1>
  <h2>Registration form for Agro-taset Company</h2>

  <form action="/action_page.php" onsubmit="myFunction()">
    <label for="fullName">Full Name:</label>
    <input type="text" name="fullName" size="15" /><br><br>

    <label for="dateOfBirth">Date of Birth:</label>
    <input type="date" name="dateOfBirth" /><br><br>

    <label for="email">Email:</label>
    <input type="text" name="email" size="50" /><br><br>

    <label for="contactNo">Contact Number:</label>
    <input type="text" name="contactNo" size="30" /><br><br>

    <label for="country">Country:</label>
    <select name="country">
      <option value="Default">Please select a country</option>
      <option value="AF">Australia</option>
      <option value="AL">Canada</option>
      <option value="IN">India</option>
      <option value="AS">Russia</option>
      <option value="AD">USA</option>
    </select><br><br>

    <label for="address">Address:</label>
    <input type="text" name="address" size="70" /><br><br>

    <label for="city">City:</label>
    <input type="text" name="city" size="30" /><br><br>

    <label for="pincode">Pincode:</label>
    <input type="text" name="pincode" /><br><br>

    <label for="state">State:</label>
    <input type="text" name="state" size="38" /><br><br>

    <label for="gender">Gender:</label>
    <input type="radio" name="gender" value="Male" />Male
    <input type="radio" name="gender" value="Female" />Female<br><br>

    <label>Language:</label>
    <input type="checkbox" name="language" value="English" checked />English
    <input type="checkbox" name="language" value="Non-English" />Non English<br><br>

    <label for="qualification">Your Qualification:</label><br>
    <textarea name="qualification" id="qualification"></textarea><br><br>

    <input type="submit" value="Submit">
  </form>

  <script>
    function myFunction() {
      alert("The form was submitted");
    }
  </script>
</body>

</html>
## OUTPUT

![Screenshot (58)](https://github.com/Krithikadini/EX08_Web-Design/assets/127816336/b8476240-f0d0-469a-83ac-b6e86f8fa64b)
![Screenshot (59)](https://github.com/Krithikadini/EX08_Web-Design/assets/127816336/6454776a-fe38-417b-99f8-f72d06cdd54c)


## RESULT
  Customer registration form using JavaScript is created successfully.
