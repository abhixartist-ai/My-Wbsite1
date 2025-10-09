<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Smart Audit Data Management</title>
<style>
  body {
    margin: 0;
    font-family: "Poppins", sans-serif;
    background: linear-gradient(120deg, #0a3d62, #3c6382);
    color: white;
    display: flex;
    align-items: center;
    justify-content: center;
    height: 100vh;
    overflow: hidden;
  }

  .hero {
    text-align: center;
    max-width: 700px;
    padding: 40px;
    background: rgba(255, 255, 255, 0.08);
    border-radius: 20px;
    box-shadow: 0 4px 20px rgba(0,0,0,0.3);
    transition: transform 1s ease-in-out, opacity 1s ease-in-out;
  }

  /* Slide-up animation class */
  .slide-up {
    transform: translateY(-120%);
    opacity: 0;
  }

  h1 {
    font-size: 2.5em;
    margin-bottom: 10px;
  }

  h2 {
    font-size: 1.2em;
    color: #b8e994;
    margin-bottom: 20px;
    letter-spacing: 1px;
  }

  p {
    font-size: 1em;
    color: #f1f2f6;
    line-height: 1.6em;
    margin-bottom: 30px;
  }

  .tagline {
    font-style: italic;
    font-size: 1.1em;
    color: #82ccdd;
    margin-bottom: 25px;
  }

  .btn {
    text-decoration: none;
    background-color: #60a3bc;
    color: white;
    padding: 12px 30px;
    border-radius: 25px;
    transition: 0.3s;
    font-weight: 600;
    cursor: pointer;
  }

  .btn:hover {
    background-color: #3c6382;
    box-shadow: 0 0 10px #82ccdd;
  }
</style>
</head>
<body>

<div class="hero" id="heroBox">
  <h1>Smart Audit Data Management</h1>
  <h2>Secure • Organized • Insightful</h2>
  <p>Manage your audit data effortlessly with secure cloud storage and intelligent organization tools. 
     From document tracking to compliance insights — everything you need, in one reliable platform.</p>
  <div class="tagline">“Where Accuracy Meets Security.”</div>
  <button class="btn" id="getStarted">Get Started</button>
</div>

<script>
  document.getElementById("getStarted").addEventListener("click", function() {
    const hero = document.getElementById("heroBox");
    hero.classList.add("slide-up");

    // Wait until animation finishes before opening next page
    setTimeout(() => {
      window.location.href = "next.html"; // change to your real file name
    }, 900); // same as CSS transition time
  });
</script>

</body>
</html>
