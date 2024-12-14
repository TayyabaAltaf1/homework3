# homework3
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>HTML Form Example</title>
</head>
<body>
  <h1>Contact Us</h1>
  
  <!-- Form starts here -->

    <label for="name">Full Name:</label><br>
    <input type="text" id="name" name="name" placeholder="Enter your full name" required><br><br>

    <label for="father-name">Father's Name:</label><br>
    <input type="text" id="father-name" name="father_name" placeholder="Enter your father's name" required>
    <br><br>

    <label for="email">Email:</label><br>
    <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>
    

    <label for="subject">Subject:</label><br>
    <select id="subject" name="subject" required>
      <option value="">-- Select Subject --</option>
      <option value="english">English</option>
      <option value="chemistry">Chemistry</option>
      <option value="Mathematics">mathematics</option>
    </select><br><br>




    <label for="education">Highest Level of Education:</label><br>
    <select id="education" name="education" required>
      <option value="">-- Select Education --</option>
      <option value="High School">High School</option>
      <option value="Associate Degree">Associate Degree</option>
      <option value="Bachelor's Degree">Bachelor's Degree</option>
      <option value="Master's Degree">Master's Degree</option>
      <option value="Doctorate">Doctorate</option>
    </select><br><br>








    <label for="date">Date:</label><br>
    <input type="date" id="date" name="date" required><br><br>



    <label for="phone">Phone Number:</label><br>
    <input type="tel" id="phone" name="phone" placeholder="Enter your phone number" required><br><br>



    <label for="dob">Date of Birth:</label><br>
    <input type="date" id="dob" name="dob" required><br><br>



    <label for="message">Message:</label><br>
    <textarea id="message" name="message" rows="5" cols="30" placeholder="Write your message here">
    </textarea><br><br>
    
    <button type="submit">Submit</button>
    
  </form>
  
</body>
</html>
