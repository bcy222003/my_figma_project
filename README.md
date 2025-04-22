<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Student Registration Form</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <div class="header">
      <div class="logo">
        <img src="file:///C:/Users/abc/Documents/book.png" alt="logo">
        
      </div>
      <div class="profile">
        <div class="profile-pic">:)</div>
        <div class="ref">Ref No: 11573</div>
      </div>
    </div>

    <h1 class="form-title">Student Registration Form</h1>

    <div class="section">. Student Information</div>
    <div class="form-group"><label>Full Name:</label><input type="text"></div>
    <div class="form-group"><label>Date of Birth:</label><input type="date"></div>
    <div class="form-group gender">
      <label>Gender:</label>
      <label><input type="radio" name="gender"> Male</label>
      <label><input type="radio" name="gender"> Female</label>
    </div>
    <div class="form-group"><label>Nationality:</label><input type="text"></div>
    <div class="form-group"><label>Contact Information:</label><input type="text"></div>

    <div class="section">. Parent/Guardian Information</div>
    <div class="form-group"><label>Parent/Guardian Name(s):</label><input type="text"></div>
    <div class="form-group"><label>Relationship to Student:</label><input type="text"></div>
    <div class="form-group"><label>Contact Information (Phone Number, Email):</label><input type="text"></div>
    <div class="form-group"><label>Emergency Contact Information:</label><input type="text"></div>

    <div class="section">. Education Information</div>
    <div class="form-group"><label>School/Institution Name:</label><input type="text"></div>
    <div class="form-group"><label>Graduation Date (if applicable):</label><input type="date"></div>
    <div class="form-group"><label>How did you hear about us?</label><input type="text"></div>
    <div class="form-group"><label>Why are you interested in our program?</label><input type="text"></div>

    <div class="form-group checkbox">
      <label><input type="checkbox"> Are you Agree to the terms and conditions of enrollment?</label>
      <p class="terms">* Terms and Conditions</p>
      <div class="icons">
        <span class="like">&#128077;</span> <!-- Thumbs up -->
        <span class="dislike">&#128078;</span> <!-- Thumbs down -->
      </div>
    </div>
    
    <div class="form-group signature">
      <label>Signature of the student and, if the student is a minor, a parent or guardian</label>
      <div class="sign-box"></div>
    </div>
  </div>
</body>
</html>
