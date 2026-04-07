<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>My Portfolio</title>

<!-- Bootstrap CSS -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">

<style>
body { padding-top: 70px; scroll-behavior: smooth; }

/* Hero */
.hero {
    height: 100vh;
    background: linear-gradient(to right, #4facfe, #00f2fe);
    color: white;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
}

/* Section */
.section { padding: 60px 0; }

/* Skills */
.skill-bar {
    height: 25px;
    background: #ddd;
    border-radius: 5px;
    overflow: hidden;
}
.skill-fill {
    height: 100%;
    color: white;
    text-align: right;
    padding-right: 10px;
    line-height: 25px;
    font-weight: bold;
    width: 0;
    transition: 1.5s;
}
.pink { background: linear-gradient(to right, #ff00cc, #ff33cc); }
.blue { background: linear-gradient(to right, #0000ff, #3333ff); }
.yellow { background: #f2f200; color: black; }
.orange { background: #e69138; }

/* Footer */
.footer {
    background: #222;
    color: white;
    text-align: center;
    padding: 15px;
}
</style>
</head>

<body>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
<div class="container">
<a class="navbar-brand" href="#">MyPortfolio</a>
<button class="navbar-toggler" data-bs-toggle="collapse" data-bs-target="#menu">
<span class="navbar-toggler-icon"></span>
</button>

<div class="collapse navbar-collapse" id="menu">
<ul class="navbar-nav ms-auto">
<li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
<li class="nav-item"><a class="nav-link" href="#about">About</a></li>
<li class="nav-item"><a class="nav-link" href="#skills">Skills</a></li>
<li class="nav-item"><a class="nav-link" href="#projects">Projects</a></li>
<li class="nav-item"><a class="nav-link" href="#certificates">Certificates</a></li>
<li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
</ul>
</div>
</div>
</nav>

<!-- Hero -->
<section id="Home" class="hero">
<div>
<h1>Hello, kavya</h1>
<p class="lead">Web Developer | Assistent professor</p>
<a href="https://ibb.co/2YyC3kVx"><img src="https://i.ibb.co/Tqk7Mgj6/Screenshot-2026-04-06-122139.png" 
alt="Screenshot-2026-04-06-122139" target="_blank" border="1"></a> 

  <img src="image.jpg" width="200">  
</div>
</section>

<!-- About -->
<section id="about" class="section text-center">
<div class="container">
<h2>About Me</h2>
<p>I am a passionate web developer skilled in HTML, CSS, Bootstrap and JavaScript.</p>
  <img src="image.jpg" width="12px">
</div>
</section>

<!-- Skills -->
<section id="skills" class="section bg-light">
<div class="container">
<h2 class="text-center">Professional Skills</h2>

<div class="mb-4">
<h5>Communication Skills</h5>
<div class="skill-bar">
<div class="skill-fill pink" data-width="80%">80%</div>
</div>
</div>

<div class="mb-4">
<h5>Problem-Solving</h5>
<div class="skill-bar">
<div class="skill-fill blue" data-width="85%">85%</div>
</div>
</div>

<div class="mb-4">
<h5>Leadership & Teamwork</h5>
<div class="skill-bar">
<div class="skill-fill yellow" data-width="90%">90%</div>
</div>
</div>

<div class="mb-4">
<h5>Adaptability</h5>
<div class="skill-bar">
<div class="skill-fill orange" data-width="75%">75%</div>
</div>
</div>

</div>
</section>

<!-- Projects -->
<section id="projects" class="section text-center">
<div class="container">
<h2>Projects</h2>
<div class="row">                          
<div class="col-md-4">
<div class="card">
<img src=   
<div class="card-body"><h5>Project 1</h5></div>
</div>
</div>
</div>
</div>
</section>

<!-- Certificates -->
<section id="certificates" class="section bg-light text-center">
<div class="container">
<h2>Certificates</h2>
<div class="row">
<div class="col-md-4">
<div class="card">
  <a href="https://learn.saylor.org/admin/tool/certificate/index.php?code=0489803404KY" target="_blank">
    <img src="certificate1.jpg" class="img-fluid">
</a>
<div class="card-body"><h5>Certificate 1</h5></div>
</div>
</div>
</div>
</div>
</section>

<!-- Contact -->
<section id="contact" class="section text-center">
<div class="container">
<h2>Contact Me</h2>
<form>
<input class="form-control mb-2" placeholder="Name">
<input class="form-control mb-2" placeholder="Email">
<textarea class="form-control mb-2" placeholder="Message"></textarea>
<button class="btn btn-primary">Send</button>
</form>
</div>
</section>

<!-- Footer -->
<div class="footer">
<p>© 2026 My Portfolio</p>
</div>

<!-- Bootstrap JS -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

<!-- Skills Animation -->
<script>
window.onload = function() {
document.querySelectorAll('.skill-fill').forEach(bar => {
bar.style.width = bar.getAttribute('data-width');
});
};
</script>

</body>
</html>
