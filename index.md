<!doctype html>
<html>
<head>
<title>Katrice Bent's Personal Website</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="pwstyle.css">
</head>

<body>
<ul>
  <li><a href="#Home">Home</a></li>
  <li><a href="#About">About</a></li>
  <li><a href="#Education">Education</a></li>
  <li><a href="#Skills">Skills</a></li>
  <li><a href="#Experience">Experience</a></li>
  <li><a href="#Contact">Contact</a></li>
</ul>
<header>
  <h1>KATRICE BENT</h1>
</header>
<div class="bgimg-1">
  <div class="caption"> <span class="border">WELCOME TO MY PERSONAL WEBSITE</span> </div>
</div>
<div id="Home" class="maintext">
  <p style="text-align:center;">Hey, I'm Katrice Bent! Welcome to my personal website.</p>
  <div class="card"> <img src="IMG_1757.jpg" alt="Katrice" style="width:100%">
    <h1>Katrice Bent</h1>
    <p class="title">Student | Tech Lover | IT & Business Professional</p>
    <p>Ryerson University</p>
    <p>
      <button>Contact</button>
    </p>
  </div>
</div>
<div class="bgimg-3">
  <div class="caption"> <span class="border">ABOUT ME</span> </div>
</div>
<div id ="About" class="maintext">
  <h2>Who is Katrice?</h2>
  <p>I am an experienced Business Owner with a demonstrated history of working in the information technology and services industry. I am a skilled entrepreneurship professional working towards a Bachelor of Commerce in Business Technology Management from Ryerson University.</p>
	<p>Location: Ottawa, Ontario and Toronto, Ontario</p>
</div>
<div class="bgimg-3">
  <div class="caption"> <span class="border">EDUCATION</span> </div>
</div>

  <div id="Education" style="position:relative;">
    <div class="maintext">
      <h2>Education</h2>
		<img src="ryerson-rgb.png" alt="Ryerson University Logo">
      <p>Bachelor of Commerce - BCom<br>
		Major: Business Technology Management<br>
		  Minor: French<br>
		Ryerson University<br>
		Ted Rogers School of Management<br>
		Expected Graduation: April 2021</p>
    </div>
  </div>

<div class="bgimg-3">
  <div class="caption"> <span class="border">SKILLS</span> </div>
</div>

  <div id="Skills" style="position:relative;">
    <div class="maintext">
      <h2>Skills</h2>
      <p>HTML</p>
      <p>CSS</p>
      <p>JavaScript</p>
      <p>Project Management</p>
		<p>Microsoft Word</p>
		<p>Languages: English and French</p>
    </div>
  </div>

<div class="bgimg-3">
  <div class="caption"> <span class="border">EXPERIENCE</span> </div>
</div>

  <div id="Experience" style="position:relative;">
    <div class="maintext">
      <h2>Experience</h2>
      <div class="timeline">
        <div class="container left">
          <div class="content">
            <h2>IT Support Analyst</h2>
            <h3>Shared Services Canada</h3>
            <p>January 2020 - Present</p>
          </div>
        </div>
        <div class="container right">
          <div class="content">
            <h2>Junior Program Officer</h2>
            <h3>Canada Revenue Agency</h3>
            <p>May 2019 - December 2019</p>
          </div>
        </div>
        <div class="container left">
          <div class="content">
            <h2>Retail Sales Associate</h2>
            <h3>Rogers Communications</h3>
            <p>February 2018 - April 2019</p>
          </div>
        </div>
        <div class="container right">
          <div class="content">
            <h2>Junior Support Analyst</h2>
            <h3>Shared Services Canada</h3>
            <p>May 2018 - August 2018</p>
          </div>
        </div>
        <div class="container left">
          <div class="content">
            <h2>Events Associate</h2>
            <h3>WITM</h3>
            <p>September 2017 - April 2018</p>
          </div>
        </div>
      </div>
    </div>
  </div>

<div class="bgimg-3">
  <div class="caption"> <span class="border">CONTACT ME</span> </div>
</div>
<section>
  <div id="Contact" style="position:relative;">
    <div class="maintext">
      <h3>Get in touch with me!</h3>
      <form action="/action_page.php">
        <label for="fname">Name</label>
        <input type="text" id="fname" name="firstname" placeholder="Your first and last name..">
        <label for="country">Country</label>
        <select id="country" name="country">
          <option value="canada">Canada</option>
          <option value="usa">USA</option>
        </select>
        <label for="subject">Subject</label>
        <textarea id="subject" name="subject" placeholder="Write something.." style="height:200px"></textarea>
        <input type="submit" value="Submit">
      </form>
    </div>
  </div>
</section>
<footer>Katrice Bent 2020 | katrice.bent@ryerson.ca</footer>
</body>
<script src="pwjava.js"></script>
</html>
