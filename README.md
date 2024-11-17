# derfnamtech
A cyber security response website
<!DOCTYPE html>
<html lang="en">
<head>
<title>Derfnam Tech | CyberSecurity Solutions</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1"> 
<link rel="stylesheet" href="style.css"> 
<link rel="shortcut icon" href="images/fav.png" type="image/x-icon">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css"> 
<link rel="stylesheet" id="theme-switcher" href="">
</head>

<body>
 

    <div class="header">

      <picture>
        <img src="images/site-logo.png" alt="" srcset="">
      </picture>

      <h1>DERFNAM TECH</h1>
      <p>Ensuring Adequate Digital Security</p>

    </div>

    <div class="navbar" id="mynavbar">
        <button class="dropdown-btn">
          <span style="font-size:30px;cursor:pointer; color: gold;" onclick="openNav()">&#9776; Explore </span>
        </button>

          <div class="dropdown-container">
              <a onclick="document.getElementById('id01').style.display='block'" style="width:auto;">Join Us Now</a>
              <a onclick="document.getElementById('id02').style.display='block'" style="width:auto;">Login</a>   
              <a href="#about">About</a>
              <a href="#card">Contact Us</a>
              <label class="switch" id="right">
                <input type="checkbox" checked>
                <span class="slider round" onclick="toggleTheme()"></span>
              </label>
          </div>
  
    </div>

    

            <div id="id01" class="modal">
  
      <form class="modal-content animate" action="/action_page.php" method="post" id="signup_form" autocomplete="on">
        <div class="imgcontainer">
          <span onclick="document.getElementById('id01').style.display='none'" class="close" title="Close Modal">&times;</span>
          <img src="images/img_avatar2.png" alt="Avatar" class="avatar">
        </div>
        <h1 style="text-align: center; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">Register</h1>
    
        <div class="container">
          <label for="uname"><b>Username</b></label>
          <input type="text" placeholder="Enter Username" name="uname" required>
    
                     
          <label for="email"><b>Email</b></label>
      <input type="text" placeholder="Enter Email" name="email" required>

      <label for="psw"><b>Password</b></label>
      <input type="password" id="psw" name="psw" placeholder="Enter a strong Password" pattern="(?=.*\d)(?=.*[a-z])(?=.*[A-Z]).{8,}" 
      title="Must contain at least one number and one uppercase and lowercase letter, and at least 8 or more characters" required>
      
      <label for="checkbox">
        <input type="checkbox" checked="checked" name="remember" style="margin-bottom:15px"> Remember me
      </label>

      <p>By creating an account you agree to our <a href="notyet.html" style="color:dodgerblue">Terms & Privacy</a>.</p>

          <button type="submit">Sign Up</button>
        </div>
    
        <div class="container" style="background-color:inherit">
          <button type="button" onclick="document.getElementById('id01').style.display='none'" class="cancelbtn">Cancel</button>

        </div>
              <div id="message">
        <h3>Password must contain the following:</h3>
        <p id="letter" class="invalid">A <b>lowercase</b> letter</p>
        <p id="capital" class="invalid">A <b>capital (uppercase)</b> letter</p>
        <p id="number" class="invalid">A <b>number</b></p>
        <p id="length" class="invalid">Minimum <b>8 characters</b></p>
      </div>
      </form>

            </div>



            <div id="id02" class="modal2">
  
      <form class="modal-content animate2" action="/action_page.php" method="post" id="login_form" onsubmit="return validatePasswords()" autocomplete="on">
        <div class="imgcontainer2">
          <span onclick="document.getElementById('id02').style.display='none'" class="close2" title="Close Modal2">&times;</span>
          <img src="images/img_avatar2.png" alt="Avatar" class="avatar2">
        </div>
        <h1 style="text-align: center; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">Login</h1>
    
        <div class="container2">
          <label for="uname"><b>Username</b></label>
          <input type="text" placeholder="Enter Username" name="uname" required>
    
          <label for="psw"><b>Password</b></label>
          <input type="password" id="psw2" name="psw2" placeholder="Enter Password"
          title="Must contain at least one number and one uppercase and lowercase letter, and at least 8 or more characters" required>
           
          <label for="psw-repeat"><b>Repeat Password</b></label>
          <input type="password" id="psw-repeat" placeholder="Repeat Password" name="psw-repeat"
          title="Must contain at least one number and one uppercase and lowercase letter, and at least 8 or more characters" required>

          <button type="submit">Login</button>
          <label for="checkbox">
            <input type="checkbox" checked="checked" name="remember"> Remember me
          </label>
        </div>
    
        <div class="container2" style="background-color:inherit">
          <button type="button" onclick="document.getElementById('id02').style.display='none'" class="cancelbtn2">Cancel</button>
          <span class="psw2">Forgot <a href="notyet.html">password?</a></span>
        </div>

      </form>

            </div>
            


<div class="content" id="contents">

      <div class="row">
            <div class="side">
                <h2 style="font-family: 'Eater'; font-size: 35px;"  id="about">About Us</h2>

                <div class="about_us" style="height:330px;">DarkTrace</div>
                  <p class="about">
                    We are a specialized team of CyberSecurity professionals committed to safeguarding your organization's most valuable digital
                    assets.With a deep understanding of the complexities of today's cyber threats, we offer a full spectrum of CyberSecurity services,
                    including threat detection, vulnerability assessments, and incident response. Our mission is to empower businesses to navigate the
                    digital world securely, ensuring that their operations remain resilent against any form of cyberattack. 
                  </p>

                  <h3 style="font-size: 25px; text-align: center;font-weight: 600; letter-spacing: 3px;">Our Key Priorities</h3>
                <div class="display_img1" style="height:200px;"><p>Securing Sensitive Information</p></div><br>
                <div class="display_img2" style="height:200px;"><p>Threat Intelligence</p></div><br>
                <div class="display_img3" style="height:200px;"><p>Mobile Phone Security</p></div><br>


    

                      

            <h1>User Rating</h1>
            <p>4.5 average based on 12K reviews.</p>

<p>5 star</p>
<div class="con">
  <div class="skills a">90%</div>
</div>

<p>4 star</p>
<div class="con">
  <div class="skills b">65%</div>
</div>

<p>3 star</p>
<div class="con">
  <div class="skills c">76%</div>
</div>

<p>2 star</p>
<div class="con">
  <div class="skills d">52%</div>
</div>
      
<p>1 star</p>
<div class="con">
  <div class="skills e">12%</div>
</div>

          </div>


      <div class="main" id="mymain">

        <h1 style="text-align: center;">OUR SERVICES</h1>
        <center>
        <div class="display" id="mydis" style="height:700px;">

            <div class="flip-box">

              <div class="flip-box-inner">
              <div class="flip-box-front">
                <h2>CONTINUOUS MONITORING</h2>
              </div>
              <div class="flip-box-back">
                <h2>INCIDENT RESPONSE</h2>
              </div>
              </div>
        
            </div>

            <div class="box">

              <div class="box-inner">
                <div class="box-front">
                    <h2>COMPLIANCE STANDARDS</h2>
                </div>
                <div class="box-back">
                    <h2>SECURITY SOLUTIONS</h2>
                </div>
              </div>

            </div>
        </div>
        </center>


   
          <h1 style="text-align: center; font-family:cursive; letter-spacing: 2px; word-spacing: 3px;">THREAT LANDSCAPE</h1>

        <div class="threats">
          <p>
        The threat landscape in cybersecurity is vast and continuously evolving, posing significant challenges to individuals,
        businesses, and governments alike.
        The proliferation of ransomware, where attackers encrypt critical data and demand payment for its release,
        has also become a significant concern, often crippling organizations and causing severe financial and reputational damage.
          </p>
        </div>

        <p id="card"></p>

          <h2 style="text-align:center">Contact Developer</h2>

        <div class="card">
      <img src="images/developer.jpg" alt="Derfnam" style="width:100%">
      <h1>Manfred Yayra Yegbe</h1>
      <p class="title">CEO & Founder, Derfnam Tech</p>
      <p>Massachusetts Institute of Technology</p>
      <div class="icons">
        <a href="tel:+233557476115"><i class="fa fas fas fa-phone"></i></a>
        <a href="https://www.instagram.com/dernamTech/"><i class="fa fa-instagram"></i></a> 
        <a href="https://www.facebook.com/derfnamTech/"><i class="fa fa-twitter"></i></a>  
        <a href="https://www.linkedin.com/in/Dark Trace/"><i class="fa fa-linkedin"></i></a>  
        <a href="https://www.facebook.com/DernamTech/"><i class="fa fa-facebook"></i></a>
        <a href="https://wa.me/0531907922" target="_blank"><i class="fa fab fa-whatsapp"></i></a>  
        <a href="mailto:derfnamcyber@gmail.com"><i class="fa fa-envelope"></i></a>
      </div>
      <p><button>Contact</button></p>
        </div>
        

      </div>
      </div>

</div>




<div class="footer">
    <footer>
  <h2>
    <p>&copy; 2024 Derfnam Tech. All rights reserved</p>
    
  </h2>
</footer>
</div>


<script src="app.js"></script>
</body>
</html>

