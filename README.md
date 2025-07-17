<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>AMS-Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color:white;
      margin: 0;
      padding: 0;
      color:blue;
    }

    header {
      background-color: white;
      color: blue;
      padding: 40px 20px;
      text-align: center;
    }

    nav {
      background-color:white;
      text-align: center;
      padding: 12px;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }

    nav a:hover {
      color:white;
    }

    section {
      padding: 40px 20px;
      max-width: 900px;
      margin: 20px auto;
      background-color: white;
      border-radius: 10px;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    }

    h1, h2 {
      color:blue;
    }

    ul {
      list-style-type: square;
      margin-left: 20px;
    }

    .contact-info p {
      margin: 8px 0;
    }

    .socials a {
      margin: 0 10px;
      color: blue;
      text-decoration: none;
    }

    .socials a:hover {
      text-decoration: underline;
    }

    .media-gallery {
      display: flex;
      gap: 20px;
      flex-wrap: wrap;
      justify-content: center;
    }

    .media-gallery img {
      width: 200px;
      height: 120px;
      object-fit: cover;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.2);
    }

    footer {
      background-color:white;
      color: blue;
      text-align: center;
      
      padding: 25px 20px;
    }

    footer a {
      color:blue;
      text-decoration: none;
      margin: 0 10px;
    }

    footer a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <header>
    <h1>AUWAL MUHD SANI</h1>
    <h3>Frontend Web Developer</h3>
  </header>
    <!-- Navigation -->
    <nav class="fixed w-full bg-white shadow-md z-50">
        <div class="container mx-auto px-6 py-3 P justify-between items-center">
            </div>
<section id="about">
    <h2>About Me</h2>
    <p>Hello! I'm Auwal Muhd Sani, a passionate beginner learning web development. I started with HTML and CSS and am currently learning Python, Java, and C. My goal is to become a full-stack developer and build creative, useful applications.</p>
  </section>

  <section id="education">
    <h2>Education</h2>
    <p>I began my studies at Usman International School where I discovered my interest in computers. Now, I'm pursuing a Bachelor's degree in Software Engineering at Northwest University, Kano State. I’m learning important topics like system design, software development, and programming languages.</p>
  </section>
 

  <section id="projects">
    <h2>My Projects</h2>
    <ul>
      <li>Basic HTML Portfolio Website</li>
      <li>Personal Bio Page</li>
      <li>Simple Calculator using JavaScript</li>
    </ul>
  </section>
  <section id="contact">
    <h2>Contact Me</h2>
    <div class="contact-info">
      <p><strong>Location:</strong> Kano State, Nigeria</p>
      <p><strong>Email:</strong> ams310705@gmail.com</p>
      <p><strong>Phone:</strong>08104528431</p>
    </div>
    <div class="socials">
     <h3>Follow Me:</h3>
     <a href="https://www.tiktok.com/@auwal.muhammad923?_t=ZM-8xp73xgCPET&_r=1">Tiktok</a> |
     <a href="https://x.com/Kawu_Rosee?t=YThW_jR5rY_6BDEzsFSLFw&s=09">X</a> |
     <a href="https://www.instagram.com/kawu_rosee?igsh=eGFwMnVhc3FlcXdx ">Instagram</a>
    </div>
  </section>
   <aside id="sidebar">
          <div class="dark">
            <h3>For more information</h3>
            <form class="quote">
  						<div>
  							<label>Name</label><br>
  							<input type="text" placeholder="Name">
  						</div>
  						<div>
  							<label>Email</label><br>
  							<input type="email" placeholder="EmailAddress">
  						</div>
  						<div>
  							<label>Message</label><br>
  							<textarea placeholder="Message"></textarea>
  						</div>
  						<button class="button_1" type="submit">Send</button>
					</form>
          </div>
        </aside>
      </div>
    </section>            
          <section id="Video">
            <div class="mt-20">
                <h3 class="text-2xl font-bold text-center mb-8">MY FAVOURITE ARTIST</h3>
                <div class="max-w-4xl mx-auto">
                    <div class="video-container">
                        <iframe src="file:///C:/Users/user/AppData/Local/Packages/5319275A.WhatsAppDesktop_cv1g1gvanyjgm/TempState/5E18F86FAD006A5846541997511989D5/WhatsApp%20Video%202025-07-02%20at%2012.02.59_55713ec4.mp4" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    </div>
                    <p class="mt-4 text-center text-gray-600">CENTRAL CEE WITH HIS NEW SONG GUILT TRIPPIN</p>
                </div>
            </div>
        </div>
    </section>
  <footer>
    <p>&copy; 2025 AMS. All Rights Reserved.</p>
    <p>Contact: 
      <a href="https://x.com/Kawu_Rosee?t=YThW_jR5rY_6BDEzsFSLFw&s=09">X</a> |
      <a href="https://www.instagram.com/kawu_rosee?igsh=eGFwMnVhc3FlcXdx">Instagram</a> |
      <a href="https://wa.link/bc4ddn">WhatsApp</a>
  </footer>
   
  <!-- JavaScript -->
  <script>
    window.onload = function() {
      alert("Welcome to AMS Portfolio!");
    };
  </script>

</body>
</html>


