# My-Profile-

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Portfolio</title>

<style>
body {
  margin: 0;
  font-family: Arial;
  background: #0f172a;
  color: white;
}

/* container */
.container {
  max-width: 420px;
  margin: auto;
  padding: 20px;
  animation: fadeIn 0.8s ease-in-out;
}

/* fade animation */
@keyframes fadeIn {
  from {opacity: 0; transform: translateY(20px);}
  to {opacity: 1; transform: translateY(0);}
}

/* profile */
.profile {
  text-align: center;
  padding: 20px;
}

.profile img {
  width: 110px;
  height: 110px;
  border-radius: 50%;
  border: 3px solid #38bdf8;
  transition: 0.3s;
}

.profile img:hover {
  transform: scale(1.1);
  box-shadow: 0 0 20px #38bdf8;
}

h1 {
  margin: 10px 0 5px;
}

/* typing animation */
.typing {
  width: fit-content;
  margin: auto;
  border-right: 2px solid #38bdf8;
  white-space: nowrap;
  overflow: hidden;
  animation: typing 3s steps(25) infinite, blink 0.7s infinite;
  color: #38bdf8;
  font-weight: bold;
}

@keyframes typing {
  0% { width: 0 }
  50% { width: 100% }
  100% { width: 0 }
}

@keyframes blink {
  50% { border-color: transparent; }
}

/* cards */
.card {
  background: #1e293b;
  padding: 15px;
  margin-top: 15px;
  border-radius: 12px;
  transition: 0.3s;
}

.card:hover {
  transform: translateY(-5px);
  box-shadow: 0 10px 20px rgba(56, 189, 248, 0.2);
}

/* skills */
.skills span {
  display: inline-block;
  background: #38bdf8;
  color: black;
  padding: 5px 10px;
  margin: 5px;
  border-radius: 20px;
  font-size: 12px;
  transition: 0.3s;
}

.skills span:hover {
  transform: scale(1.1);
  background: white;
}

/* projects */
.project {
  margin-top: 10px;
  padding: 10px;
  background: #334155;
  border-radius: 10px;
  transition: 0.3s;
}

.project:hover {
  background: #38bdf8;
  color: black;
  transform: scale(1.05);
}

/* links */
a {
  color: #38bdf8;
  text-decoration: none;
}
</style>

</head>

<body>

<div class="container">

  <!-- PROFILE -->
  <div class="profile">
    <img src="profile.png" alt="profile">
    <h1>Nadeesh</h1>
    <p class="typing">Frontend Web Developer</p>
  </div>

  <!-- ABOUT -->
  <div class="card">
    <h3>About Me</h3>
    <p>I am a passionate web developer building modern responsive websites using HTML, CSS, and JavaScript.</p>
  </div>

  <!-- SKILLS -->
  <div class="card skills">
    <h3>Skills</h3>
    <span>HTML</span>
    <span>CSS</span>
    <span>JavaScript</span>
    <span>Python</span>
    <span>Git</span>
  </div>

  <!-- PROJECTS -->
  <div class="card">
    <h3>Projects</h3>
    <div class="project">Login Page App</div>
    <div class="project">Portfolio Website</div>
    <div class="project">School Website (In Progress)</div>
  </div>

  <!-- CONTACT -->
  <div class="card">
    <h3>Contact</h3>
    <p>Email: nadeeshkumar001@gmail.com</p>
    <p>
      GitHub: 
      <a href="https://github.com/NadeeshKumar" target="_blank">
        github.com/NadeeshKumar
      </a>
    </p>
  </div>

</div>

</body>
</html>
