# HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="style.css">
    <title>Lynus Portfolio</title>
</head>
<body>
  <header style="position: relative;">

    <div class="w3-top" class="header" id="home">
      <div class="w3-bar  w3-card w3-left-align w3-large heeder-large-screen" style="background-color: #000015;" >
        <a class="w3-bar-item w3-button w3-hide-medium w3-hide-large w3-right w3-padding-large w3-hover-black w3-large " href="javascript:void(0);" onclick="myFunction()" title="Toggle Navigation Menu"><i class="fa fa-bars"></i></a>
        <a href="#home" class="w3-bar-item w3-button w3-padding-large  w3-hover-black">Penaranda</a>
        <div >
          <a href="#about" class="w3-bar-item w3-button w3-hide-small w3-padding-large w3-hover-black" >About</a>
          <a href="#skills" class="w3-bar-item w3-button w3-hide-small w3-padding-large w3-hover-black"> Skills</a>
          <a href="#hobbies" class="w3-bar-item w3-button w3-hide-small w3-padding-large w3-hover-black">Hobbies</a>
          <a href="#contact information" class="w3-bar-item w3-button w3-hide-small w3-padding-large w3-hover-black">Contact Information</a>
        </div>
    
      </div>

      <div id="navDemo" class="w3-bar-block  w3-hide w3-hide-large w3-hide-medium w3-large">
        <a href="#about" class="w3-bar-item w3-button w3-padding-large"onclick="myFunction()">About</a>
        <a href="#skills" class="w3-bar-item w3-button w3-padding-large"onclick="myFunction()">Skills</a>
        <a href="#hobbies" class="w3-bar-item w3-button w3-padding-large" onclick="myFunction()">Hobbies</a>
        <a href="#contact information" class="w3-bar-item w3-button w3-padding-large" onclick="myFunction()">Contact information</a>
      </div>
    </div>
  </header>
      <section >
         <div class="hero" id="about">
           <div class="hero-description">
             <div class="hero-text">
              <h1 class="hero-title">Lynus Penaranda</h1>
              <p>
                Student of University of the East in Information Technology
              </p>
              <span class="w3-text-white social" style="margin-top:050px">
                <p >Follow me on Social media</p>
                <div class="w3-margin-top">
             <a href="https://www.facebook.com/penaranda2005">  <i class="fa fa-facebook-official w3-hover-opacity icons" ></i></a> 
             <a href="https://www.instagram.com/lytoughasf/"><i class="fa fa-instagram w3-hover-opacity icons" ></i></a> 
             <a href="https://github.com/lynus15"><i class="fa fa-github w3-hover-opacity icons"></i></a>   
             </div>
              </span>
             </div>
           </div>
         </div>
      </section>
      <main style="padding-bottom:40px ;">
        <h2 class="title" id="skills">Skills</h2>
        <div class="skills">
          <div class="skills-list">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR1z4mc0fjCkQkDh-1F3od_KyMB0kk9l7UnrA&s" alt="basketball" style="width:100px; height: 100px;"/>
          <h3>Basketball</h3>
          <p></p>
          </div>
          <div class="skills-list">
              <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ2Nppu_Uos62dUJp8W2MPJGu_frKOpBwnk_w&s" alt="cooking" style="width:100px; height: 100px;"/>
            <h3>Cooking</h3>
            <p></p>
          </div>
          
        
        </div>
        <div class="title" id="hobbies">
         <h2 class="title">Hobbies</h2>
        
        <div class="hobbies-store">

          <div class="hobbies-list">
            <div class="hobbies-image">
              <img src="https://i.pinimg.com/736x/5c/53/9b/5c539b9aa78bcd36fde4fbffac2a423c.jpg" alt="Photo by Katharina Gloth | Unsplash"/>
            </div>
            <div class="hobbies-text-description">
             <h4>Rides</h4>
             <span> with Friends </span>
            </div>

          </div>
          <div class="hobbies-list">
            <div class="hobbies-image">
              <img src="https://t3.ftcdn.net/jpg/05/70/06/64/360_F_570066449_SS8sx5K4ZsYXCcXvR014q2prysMs1kf2.jpg" alt="Photo by Maverick Timotius | Unsplash"/>
            </div>
            <div class="hobbies-text-description">
              <h4>Playing Basketball</h4>
              <span> with anyone </span>
            </div>

          </div>

          </div>

        </div>
      </div>
      <div class="contact information" id="contact information" style="padding-bottom: 10px !important;">
      <div class="contact information-list contact-address"  >
        <h5><span><i class="fa fa-map-marker w3-xlarge w3-text-white"></i></span>Address</h5>
        <p> Pla Pla, Caloocan City</p>
      </div>
      <div class="contact information-list">
        <h5><span><i class="fa fa-envelope w3-xlarge w3-text-light-grey"></i></span>Receive weekly update email</h5>
        <div class="email-contact information">
          <input placeholder="Email"  type="email" style="margin: 8px 0px !important;"/>
          
          <button class="w3-btn w3-red w3-round " style="width: 100px; padding:3px 10px !important">Send me</button>
        </div>
  
      </div>
      <div class="contact information-list" >
        <h5><span><i class="fa fa-phone w3-xlarge w3-text-white"></i></span>Phone</h5>
        <p> 0969-319-2180</p>
      </div>

      </div>
    </div>

      </div>
      
</body>
</html>
