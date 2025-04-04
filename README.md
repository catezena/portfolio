<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css"
</head>
<body>
    <header>
        <h1>Welcome to My Portfolio</h1>
        <p>I'm Catherine Zena , a passionate Computer scientist</p>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#education">Education</a></li>
                <li><a href="#interests">Interests</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <p>Hello, I'm Catherine, a dedicated programmer with a passion for secure coding and innovative problem-solving. What drives me is the thrill of creating solutions that not only work seamlessly but also protect users and their data. With a strong foundation in languages like Java, C++, and Python, I enjoy exploring new challenges and mastering modern technologies. My enthusiasm for the ever-evolving tech world is fueled by a commitment to excellence and a desire to make a positive impact through technology.Let's coonect and see how my skills can contribute to your next project .</p>
    </section>

    <section id="education">
        <h2>Educational Background</h2>
        <p>I'm currently a second-year Bachelor of Computer Science student, specializing in software engineering, network analysis, and cybersecurity. My academic journey so far has equipped me with a solid foundation in programming languages like Java, C++, C, alongside hands-on experience in secure coding practices and real-world applications. I'm excited to continue growing my skills and exploring innovative technologies. Feel free to check out my CV to learn more about my academic projects and achievements</p>
        <a href="https://1drv.ms/b/c/8b86b33601f7e68e/EWNkPfJGhv9Ek9jUEsySsbkBeiagK_2aijzRmmIVaNK1dA" download>Download CV</a>
    </section>

    <section id="interests">
        <h2>Interests</h2>
        <I've always been fascinated by the way technology transforms everyday life, and that curiosity drives my passion for coding and innovation. I enjoy diving into secure coding practices and understanding how to build applications that not only perform well but are also resilient against modern threats. I’m also interested in web-development there’s something exciting about creating functional, user-friendly designs from scratch. What excites me the most is the constant learning in tech how you can never have enough of it ....keeps me on my toes and challenges me to grow every day.</p>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <ul>
            <li>
                <a href="https://github.com/catezena/SECURE-LOGIN-SYSTEM.git">SECURE-LOGIN-SYSTEM</a>:Description: I developed a secure authentication system with robust protection against SQL injection and Cross-Site Request Forgery (CSRF) attacks. The system utilized hashing algorithms for password storage and implemented session management to ensure user safety during login processes.

                Key Skills Used: Database management, encryption, and vulnerability testing.
                
                Technologies: Java, MySQL, and bcrypt for password hashing.
                
                My Role: Designed the database schema,
                
                implemented login functionality, and tested the system for common security vulnerabilities.
            </li>
            <li>
                <hrefaf="https://1drv.ms/b/c/8b86b33601f7e68e/ERhQsxG-OstHs35cdOmIHnwBrRu1vwSWtBmvBQb-x2J3KQ">HTTP HEADER ANALYSIS TOOL</a>:Description: This project involved creating a tool to analyze HTTP headers for security and performance optimization. By leveraging network analysis tools like Wireshark, I was able to identify vulnerabilities in data transmission and enhance application security. The project required a strong understanding of network protocols and an ability to interpret complex data flow patterns.

                Key Skills Used: Network analysis, Python scripting, and secure coding practices.
                
                Technologies: Python, Wireshark, and HTTP protocols.
                
                My Role: Designed and developed the tool, tested various use cases, and documented the findings with actionable security recommendations.
            </li>
            
        </ul>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <form action="#" method="post">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; [Year] [Your Name]. All rights reserved.</p>
    </footer>
</body>
</html>


/* GENERAL STYLES */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  transition: all 0.3s ease;
}

body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  line-height: 1.6;
  color: #2c3e50;
  background: linear-gradient(135deg, #e0f7fa 0%, #bbdefb 100%);
  scroll-behavior: smooth;
}

h1, h2, h3 {
  margin-bottom: 15px;
  font-weight: 600;
}

p {
  margin-bottom: 20px;
  line-height: 1.8;
}

/* HEADER STYLES */
header {
  background: linear-gradient(45deg, #1a5276, #3498db);
  color: white;
  text-align: center;
  padding: 60px 0 20px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
  position: relative;
  overflow: hidden;
}

header::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: radial-gradient(circle, rgba(52, 152, 219, 0.3) 10%, rgba(0, 0, 0, 0.05) 70%);
  z-index: 1;
}

header h1 {
  font-size: 42px;
  font-weight: 700;
  text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
  transform: translateY(0);
  transition: transform 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275);
  position: relative;
  z-index: 2;
}

header h1:hover {
  transform: translateY(-5px);
}

header p {
  font-size: 20px;
  margin-bottom: 30px;
  max-width: 700px;
  margin-left: auto;
  margin-right: auto;
  opacity: 0.9;
  position: relative;
  z-index: 2;
}

/* NAVIGATION STYLES */
nav {
  padding-bottom: 15px;
  position: relative;
  z-index: 2;
}

nav ul {
  list-style: none;
  display: flex;
  justify-content: center;
  gap: 15px;
}

nav ul li {
  margin: 0 10px;
}

nav ul li a {
  color: white;
  text-decoration: none;
  padding: 8px 18px;
  border-radius: 25px;
  font-weight: 500;
  background-color: rgba(41, 128, 185, 0.4);
  transition: all 0.3s ease;
  display: block;
  border: 1px solid rgba(255, 255, 255, 0.2);
}

nav ul li a:hover {
  background-color: rgba(41, 128, 185, 0.7);
  transform: translateY(-3px);
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
  border-color: rgba(255, 255, 255, 0.5);
}

nav ul li a:active {
  transform: translateY(0);
}

/* SECTION STYLES - COMMON */
section {
  padding: 70px 30px;
  max-width: 1100px;
  margin: 0 auto 40px;
  border-radius: 12px;
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.08);
  transition: transform 0.4s ease, box-shadow 0.4s ease;
  border-top: 4px solid #3498db;
}

section:hover {
  transform: translateY(-5px);
  box-shadow: 0 15px 35px rgba(0, 0, 0, 0.15);
}

section h2 {
  text-align: center;
  color: #1a5276;
  position: relative;
  padding-bottom: 20px;
  margin-bottom: 30px;
  font-size: 32px;
}

section h2::after {
  content: '';
  position: absolute;
  bottom: 0;
  left: 50%;
  transform: translateX(-50%);
  width: 80px;
  height: 4px;
  background: linear-gradient(90deg, #3498db, #1a5276);
  border-radius: 2px;
  transition: width 0.3s ease;
}

section:hover h2::after {
  width: 120px;
}

/* ABOUT SECTION STYLES - FIXED TO MATCH INTERESTS */
#about {
  background: linear-gradient(to bottom right, #ffffff, #f0f8ff);
}

#about p {
  text-align: justify;
  border-left: 4px solid transparent;
  padding-left: 15px;
  margin-left: 5px;
  transition: all 0.3s ease;
  border-radius: 0 5px 5px 0;
}

#about p:hover {
  border-left-color: #3498db;
  background-color: rgba(52, 152, 219, 0.08);
  padding-left: 20px;
  transform: none;
}

/* EDUCATION SECTION STYLES */
#education {
  background: linear-gradient(to bottom right, #f0f8ff, #e1f5fe);
  border-top-color: #2196f3;
}

#education p {
  text-align: justify;
  margin-bottom: 25px;
  transition: transform 0.3s ease;
  padding-left: 15px;
  border-left: 4px solid transparent;
  border-radius: 0 5px 5px 0;
}

#education p:hover {
  transform: none;
  border-left-color: #2196f3;
  background-color: rgba(33, 150, 243, 0.08);
  padding-left: 20px;
}

#education a {
  display: inline-block;
  padding: 12px 25px;
  background: linear-gradient(45deg, #2196f3, #0d47a1);
  color: white;
  text-decoration: none;
  border-radius: 30px;
  font-weight: 500;
  transition: all 0.3s ease;
  position: relative;
  overflow: hidden;
  box-shadow: 0 4px 15px rgba(33, 150, 243, 0.3);
}

#education a:hover {
  transform: translateY(-3px);
  box-shadow: 0 8px 20px rgba(33, 150, 243, 0.4);
}

#education a:active {
  transform: translateY(0);
}

/* INTERESTS SECTION STYLES */
#interests {
  background: linear-gradient(to bottom right, #ffffff, #e8f5e9);
  border-top-color: #4caf50;
}

#interests p {
  text-align: justify;
  border-left: 4px solid transparent;
  padding-left: 15px;
  margin-left: 5px;
  transition: all 0.3s ease;
  border-radius: 0 5px 5px 0;
}

#interests p:hover {
  border-left-color: #4caf50;
  background-color: rgba(76, 175, 80, 0.08);
  padding-left: 20px;
}

/* PROJECTS SECTION STYLES */
#projects {
  background: linear-gradient(to bottom right, #f0f8ff, #e3f2fd);
  border-top-color: #03a9f4;
}

#projects ul {
  list-style: none;
}

#projects li {
  margin-bottom: 35px;
  padding: 25px;
  background: #ffffff;
  border-radius: 10px;
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
  transition: all 0.4s ease;
  border-left: 5px solid transparent;
}

#projects li:hover {
  transform: translateY(-7px) scale(1.01);
  box-shadow: 0 15px 30px rgba(0, 0, 0, 0.1);
  border-left: 5px solid #03a9f4;
  background-color: rgba(3, 169, 244, 0.03);
}

#projects a {
  color: #0288d1;
  font-weight: bold;
  text-decoration: none;
  font-size: 20px;
  position: relative;
  display: inline-block;
  transition: all 0.3s ease;
}

#projects a::after {
  content: '';
  position: absolute;
  width: 0;
  height: 2px;
  bottom: 0;
  left: 0;
  background-color: #0288d1;
  transition: width 0.3s ease;
}

#projects a:hover {
  color: #01579b;
}

#projects a:hover::after {
  width: 100%;
}

/* CONTACT SECTION STYLES */
#contact {
  background: linear-gradient(to bottom right, #ffffff, #e1f5fe);
  border-top-color: #00bcd4;
}

#contact form {
  max-width: 600px;
  margin: 0 auto;
}

#contact label {
  display: block;
  margin-bottom: 8px;
  font-weight: bold;
  color: #0277bd;
  transition: color 0.3s ease;
}

#contact label:hover {
  color: #01579b;
}

#contact input,
#contact textarea {
  width: 100%;
  padding: 12px 15px;
  margin-bottom: 25px;
  border: 2px solid #b3e5fc;
  border-radius: 8px;
  transition: all 0.3s ease;
  box-shadow: inset 0 1px 3px rgba(0, 0, 0, 0.05);
}

#contact input:focus,
#contact textarea:focus {
  border-color: #29b6f6;
  box-shadow: 0 0 0 3px rgba(41, 182, 246, 0.25);
  outline: none;
}

#contact textarea {
  height: 150px;
  resize: vertical;
}

#contact button {
  padding: 12px 30px;
  background: linear-gradient(45deg, #00bcd4, #006064);
  color: white;
  border: none;
  border-radius: 30px;
  cursor: pointer;
  font-weight: 600;
  font-size: 16px;
  transition: all 0.3s ease;
  box-shadow: 0 4px 15px rgba(0, 188, 212, 0.3);
  position: relative;
  overflow: hidden;
}

#contact button::before {
  content: '';
  position: absolute;
  top: 0;
  left: -100%;
  width: 100%;
  height: 100%;
  background: linear-gradient(90deg, rgba(255,255,255,0.2), transparent);
  transition: left 0.5s ease;
}

#contact button:hover {
  transform: translateY(-3px);
  box-shadow: 0 8px 20px rgba(0, 188, 212, 0.4);
}

#contact button:hover::before {
  left: 100%;
}

#contact button:active {
  transform: translateY(0);
}

/* FOOTER STYLES */
footer {
  background: linear-gradient(45deg, #1a5276, #3498db);
  color: white;
  text-align: center;
  padding: 30px;
  box-shadow: 0 -5px 15px rgba(0, 0, 0, 0.1);
  position: relative;
  overflow: hidden;
}

footer::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: radial-gradient(circle, rgba(52, 152, 219, 0.3) 10%, rgba(0, 0, 0, 0.05) 70%);
}

footer p {
  position: relative;
  z-index: 1;
  opacity: 0.9;
  transition: opacity 0.3s ease;
}

footer p:hover {
  opacity: 1;
}

/* Accent colors and decorative elements */
.accent-bg {
  position: fixed;
  z-index: -1;
  width: 300px;
  height: 300px;
  border-radius: 50%;
  background: radial-gradient(circle, rgba(41, 128, 185, 0.2), transparent 70%);
}

.accent-top-right {
  top: -100px;
  right: -100px;
}

.accent-bottom-left {
  bottom: -100px;
  left: -100px;
  background: radial-gradient(circle, rgba(41, 182, 246, 0.2), transparent 70%);
}

/* RESPONSIVE STYLES */
@media (max-width: 768px) {
  header {
    padding: 40px 0 15px;
  }
  
  header h1 {
    font-size: 32px;
  }
  
  header p {
    font-size: 16px;
  }
  
  nav ul {
    flex-direction: column;
    align-items: center;
    gap: 10px;
  }
  
  nav ul li {
    margin: 3px 0;
    width: 80%;
  }
  
  nav ul li a {
    display: block;
    text-align: center;
    padding: 10px;
  }
  
  section {
    padding: 40px 20px;
    margin-bottom: 20px;
  }
  
  section h2 {
    font-size: 26px;
  }
  
  #projects li {
    padding: 15px;
  }
  
  #contact button {
    width: 100%;
  }
}

@media (min-width: 769px) and (max-width: 1024px) {
  section {
    padding: 50px 25px;
  }
  
  section h2 {
    font-size: 28px;
  }
}

/* Animation for page load */
@keyframes fadeIn {
  from {
    opacity: 0;
    transform: translateY(20px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

body > * {
  animation: fadeIn 0.8s ease-out forwards;
  animation-delay: calc(var(--animation-order, 0) * 0.1s);
}

header {
  --animation-order: 1;
}

section:nth-of-type(1) {
  --animation-order: 2;
}

section:nth-of-type(2) {
  --animation-order: 3;
}

section:nth-of-type(3) {
  --animation-order: 4;
}

section:nth-of-type(4) {
  --animation-order: 5;
}

section:nth-of-type(5) {
  --animation-order: 6;
}

footer {
  --animation-order: 7;
}

/* Scroll animation */
html {
  scroll-behavior: smooth;
}

/* Custom scrollbar - blue color scheme */
::-webkit-scrollbar {
  width: 10px;
}

::-webkit-scrollbar-track {
  background: #e3f2fd;
}

::-webkit-scrollbar-thumb {
  background: linear-gradient(to bottom, #2196f3, #0d47a1);
  border-radius: 5px;
}

::-webkit-scrollbar-thumb:hover {
  background: linear-gradient(to bottom, #1976d2, #01579b);
}

/* Additional decorative elements */
section::before {
  content: '';
  position: absolute;
  top: 15px;
  right: 15px;
  width: 50px;
  height: 50px;
  border-radius: 50%;
  background: linear-gradient(45deg, rgba(52, 152, 219, 0.1), rgba(52, 152, 219, 0.05));
  opacity: 0.5;
  z-index: 0;
  transition: all 0.3s ease;
}

section:hover::before {
  width: 70px;
  height: 70px;
  opacity: 0.8;
}

