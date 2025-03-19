# index.html.
<!DOCTYPE html>
 <html>
 <head>
     <title>Portfolio</title>
     <style>
         body {
             font-family: Arial, sans-serif;
             margin: 0;
             padding: 0;
             background-color:black;
         }
 
         header {
             background-color: #941919;
             color: #fff;
             text-align: center;
             padding: 2rem 0;
             position: relative; /* Add this */
         }
 
         .header-content h1 {
             font-size: 2.5rem;
         }
 
         /* Add styles for the round profile picture */
         .profile-picture {
             width: 100px; /* Adjust the size as needed */
             height: 100px;
             border-radius: 75%; /* Create a circular shape */
             object-fit: cover; /* To ensure the image fills the circular area */
             position: absolute; /* Add this */
             top: 75px; /* Adjust top position as needed */
             left: 75px; /* Adjust left position as needed */
         }
 
         nav {
             background-color: #333;
             color: #fff;
             text-align: center;
         }
 
         nav ul {
             list-style-type: none;
             padding: 0;
         }
 
         nav ul li {
             display: inline;
             margin: 0 20px;
         }
 
         nav ul li a {
             text-decoration: none;
             color: #fff;
         }
 
         .section-content {
             background-color: #fff;
             padding: 2rem;
             margin: 1rem;
             border-radius: 20px;
             box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
             text-align: justify;
         }
 
         .download-button {
             background-color: #333;
             color: #fff;
             padding: 0.5rem 1rem;
             text-decoration: none;
             border-radius: 20px;
             display: inline-block;
             margin-top: 10px;
             align-self: center;
         }
 
         .download-button:hover {
             background-color: #555;
         }
 
         footer {
             text-align: center;
             padding: 1rem 0;
             background-color: #333;
             color: #fff;
         }
 
         ul {
             list-style-type: disc;
             padding-left: 20px;
         }
     </style>
 </head>
 <body>
     <header>
         <div class="header-content">
             <!-- Add your profile picture here -->
             <img src="passport photo.jpg" alt="Your Profile Picture" class="profile-picture">
             <h1>Ruban D</h1> 2Has conversations. Original line has conversations.
             <p>BCA Student</p> 1Has a conversation. Original line has a conversation.
         </div>
     </header>
 
     <nav>
         <ul>
             <li><a href="#about">About</a></li>
             <li><a href="#education">Education</a></li>
             <li><a href="#skills">Skills</a></li>
             <li><a href="#projects">Projects</a></li>
             <li><a href="#resume">Resume</a></li>
            
         </ul>
     </nav>
 
     <section id="about">
         <div class="section-content">
             <h2>About Me</h2>
             <p>I am a motivated and detail-oriented<b> Bachelor of Computer Applications (BCA)</b> student with a strong foundation in programming languages such as Java, Python, and C++. I have developed a keen interest in cloud computing and have honed my skills in this area to understand how cloud technologies can optimize and streamline business operations. Along with my technical skills, I am proficient in MS Word, ensuring that I can effectively communicate, document, and present technical information.

I am eager to apply my skills and knowledge to contribute to software development projects and am actively looking for opportunities where I can further develop my expertise. My goal is to work in a dynamic software company where I can grow professionally while delivering high-quality solutions."**

This gives a clear, concise overview of your skills and aspirations while highlighting your strengths!</p>
 
         </div>
     </section>
 
     <section id="education">
         <div class="section-content">
             <h2>Education</h2>
             <p>Aided University-BCA</p>
             
             
         </div>
     </section>
 
     <section id="skills">
         <div class="section-content">
             <h2>Skills</h2>
             <ul>
                 <li>Java</li>
                 <li>C++</li>
                 <li>Cloud Computing</li>
                 <li>Python</li>
                 <li>ML & AI</li>
             </ul>
         </div>
     </section>
 
     <section id="projects">
         <div class="section-content">
             <h2>Projects</h2>
             <ul>
                 <li><a href="#">Traffic Recognition system</a></li>
                 <!-- Add more project links here -->
             </ul>
         </div>
     </section>
 
     <section id="resume">
     
         <div class="section-content">
             <center>
             <h2>Resume</h2>
             <a href="file.pdf" target="_blank" class="download-button">Download CV</a>
         </center>
         </div>
         
     </section>
 
     <footer>
         <p>&copy; 2025 Pranesh S</p>
     </footer>
 
     <script>
         // Smooth scrolling to section when clicking on navigation links
         document.querySelectorAll('a[href^="#"]').forEach(anchor => {
             anchor.addEventListener('click', function(e) {
                 e.preventDefault();
 
                 const targetId = this.getAttribute('href').substring(1);
                 const targetElement = document.getElementById(targetId);
 
                 if (targetElement) {
                     window.scrollTo({
                         top: targetElement.offsetTop,
                         behavior: 'smooth'
                     });
                 }
             });
         });
     </script>
 </body>
 </html>
