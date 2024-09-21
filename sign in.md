<!DOCTYPE html>  
<html lang="en">  
<head>  
  <meta charset="UTF-8">  
  <meta name="viewport" content="width=device-width, initial-scale=1.0">  
  <title>MySchool App Sign In</title>  
  <link rel="stylesheet" href="styles.css">  
</head>  
<body>  
  <div class="container">  
   <h1>MySchool App Sign In</h1>  
   <form id="signin-form">  
    <div class="form-group">  
      <label for="email">Email</label>  
      <input type="email" id="email" name="email" required>  
    </div>  
    <div class="form-group">  
      <label for="otp-email">OTP (sent to your email)</label>  
      <input type="number" id="otp-email" name="otp-email" required>  
    </div>  
    <div class="form-group">  
      <label for="password">Password</label>  
      <input type="password" id="password" name="password" required>  
    </div>  
    <button id="continue-signin" type="submit">Continue Sign In</button>  
   </form>  
  </div>  
  
  <div class="container" id="video-upload-container" style="display: none;">  
   <h1>Upload Live Video</h1>  
   <input type="file" id="video-upload" name="video-upload" accept="video/*" required>  
   <button id="upload-video">Upload Video</button>  
  </div>  
  
  <button id="finish-signin" style="display: none;">Finish Sign In</button>  
  
  <script src="script.js"></script>  
</body>  
</html>
