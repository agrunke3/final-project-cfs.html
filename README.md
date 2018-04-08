# final-project-cfs.html
<!DOCTYPE html>
   <head>
       <meta charset="utf-8">
       <title></title>
      <link rel="stylesheet" href="style.css"> 
      <link href="https://fonts.googleapis.com/css?family=Encode+Sans+Condensed" rel="stylesheet">

   </head>
   <body>
          <h1>Let's Create an ID card!</h1>
     <form>
       <label>First Name<br> <input type="text" id="firstName" name="First Name"/></label><br>
       <label>Last Name<br> <input type="text" id="lastName" name="Last Name"/></label><br>
       <label>Age<br> <input type="number" id="age" name="Age"/></label><br>
       <label>Phone Number<br> <input type="number" id="phoneNumber" name="Phone Number"/></label><br>

       <label>Address<br> <input type="text" id="address" name="Name"/></label><br>

       <button type="button" value="submit" onclick="idCard()">Get ID Card!</button>
     </form>

      <div id="idCard">

          <img src="http://www.iconninja.com/files/373/611/612/person-user-profile-male-man-avatar-account-icon.svg">
          <p id="postFullName"></p>
          <p id="postAge"></p>
          <p id="postPhoneNumber"></p>
          <p id="postAddress"></p>
      </div>
  
    <script src = "script.js"></script>
   </body>
</html>
