<!DOCTYPE html>  
<html lang="en">  
<head>  
  <meta charset="UTF-8">  
  <meta name="viewport" content="width=device-width, initial-scale=1.0">  
  <title>MySchool App Signup</title>  
  <link rel="stylesheet" href="styles.css">  
</head>  
<body>  
  <div class="container">  
   <h1>MySchool App Signup</h1>  
   <form id="signup-form">  
    <div class="form-group">  
      <label for="email">Email</label>  
      <input type="email" id="email" name="email" required>  
    </div>  
    <div class="form-group">  
      <label for="otp-email">OTP (sent to your email)</label>  
      <input type="number" id="otp-email" name="otp-email" required>  
    </div>  
    <div class="form-group">  
      <label for="phone">Phone Number</label>  
      <input type="tel" id="phone" name="phone" required>  
    </div>  
    <div class="form-group">  
      <label for="otp-phone">OTP (sent to your phone)</label>  
      <input type="number" id="otp-phone" name="otp-phone" required>  
    </div>  
    <button id="continue-signup" type="submit">Continue Signup</button>  
   </form>  
  </div>  
  
  <div class="container" id="video-upload-container" style="display: none;">  
   <h1>Upload Live Video</h1>  
   <input type="file" id="video-upload" name="video-upload" accept="video/*" required>  
   <button id="upload-video">Upload Video</button>  
  </div>  
  
  <div class="container" id="id-upload-container" style="display: none;">  
   <h1>Upload Government Issued ID</h1>  
   <input type="file" id="id-upload" name="id-upload" accept="image/*" required>  
   <button id="upload-id">Upload ID</button>  
  </div>  
  
  <button id="finish-signup" style="display: none;">Finish Signup</button>  
  
  <script src="script.js"></script>  
</body>  
</html>
