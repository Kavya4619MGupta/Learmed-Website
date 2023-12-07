<!DOCTYPE html>
<html>
<head>
	<link rel="shortcut icon" type="png" href="images/icon/favicon.png">
	<meta charset="utf-8">
	<meta http-equiv="X-UA-Comaptible" content="IE=edge">
	<title>LearnEd</title>
	<meta name="desciption" content="">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<link rel="stylesheet" type="text/css" href="style.css">
	<script type="text/javascript" src="script.js"></script>
	<script src="https://code.jquery.com/jquery-3.2.1.js"></script>
	<script>
		$(window).on('scroll', function(){
  			if($(window).scrollTop()){
  			  $('nav').addClass('black');
 			 }else {
 		   $('nav').removeClass('black');
 		 }
		})
	</script>
</head>
<body>
<!-- Navigation Bar -->
	<header id="header">
		<nav>
			<div class="logo"><img src="images/icon/logo.png" alt="logo"></div>
			<ul>
				<li><a class="active" href="">Home</a></li>
				<li><a href="#portfolio_section">Portfolio</a></li>
				<li><a href="#team_section">Team</a></li>
				<li><a href="#services_section">Services</a></li>
				<li><a href="#contactus_section">Contact</a></li>
				
			</ul>
			<div class="srch"><input type="text" class="search" placeholder="Search here..."><img src="images/icon/search.png" alt="search" onclick=slide()></div>
			<a class="get-started" href="login.html">Get Started</a>
			<img src="images/icon/menu.png" class="menu" onclick="sideMenu(0)" alt="menu">
		</nav>
		<div class="head-container">
			<div class="quote">
				<p>The beautiful thing about learning is that nobody can take it away from you</p>
				<h5>Education is the process of facilitating learning, or the acquisition of knowledge, skills, values, beliefs, and habits. Educational methods include teaching, training, storytelling, discussion and directed research!</h5>
				<div class="play">
					<img src="images/icon/play.png" alt="play"><span><a href="https://youtu.be/T65vYMcZQPw?si=sd_U-njibgWv1POX" target="_blank">Watch Now</a></span>
				</div>
			</div>
			<div class="svg-image">
				<img src="images/extra/svg1.jpg" alt="svg">
			</div>
		</div>
		<div class="side-menu" id="side-menu">
			<div class="close" onclick="sideMenu(1)"><img src="images/icon/close.png" alt=""></div>
			<div class="user">
				<img src="images/creator/roshan.jpeg" alt="Username">
				<p>roshank9419</p>
			</div>
			<ul>
				<li><a href="#about_section">About</a></li>
				<li><a href="#portfolio_section">Portfolio</a></li>
				<li><a href="#team_section">Team</a></li>
				<li><a href="#services_section">Services</a></li>
				<li><a href="#contactus_section">Contact</a></li>
				<li><a href="#feedBACK">Feedback</a></li>
			</ul>
		</div>
	</header>


<!-- Some Popular Subjects -->
	<div class="title">
		<span>Popular Subjects on LearnEd</span>
	</div>
	<br><br>
	<div class="course">
		<center><div class="cbox">
		<div class="det"><a href="subjects/jee.html"><img src="images/courses/book.png">JEE Preparation</a></div>
		<div class="det"><a href="subjects/gate.html"><img src="images/courses/d1.png">GATE Preparation</a></div>
		<div class="det"><a href="subjects/jee.html#sample_papers"><img src="images/courses/paper.png">Sample Papers</a></div>
		<div class="det"><a href="subjects/quiz.html"><img src="images/courses/d1.png">Daily Quiz</a></div>
		</div></center>
		<div class="cbox">
		<div class="det"><a href="subjects/computer_courses.html"><img src="images/courses/computer.png">Computer Courses</a></div>
		<div class="det"><a href="subjects/computer_courses.html#data"><img src="images/courses/data.png">Data Structures</a></div>
		<div class="det"><a href="subjects/computer_courses.html#algo"><img src="images/courses/algo.png">Algorithm</a></div>
		<div class="det det-last"><a href="subjects/computer_courses.html#projects"><img src="images/courses/projects.png">Projects</a></div>
		</div>
	</div>

	
<!-- ABOUT -->
	<div class="diffSection" id="about_section">
		<center><p style="font-size: 50px; padding: 100px">About</p></center>
		<div class="about-content">
				<div class="side-image">
					<img class="sideImage" src="images/extra/e3.jpg">
				</div>
				<div class="side-text">
					<h2>What you think about us ?</h2>
					<p>Education is the process of facilitating learning, or the acquisition of knowledge, skills, values, beliefs, and habits. Educational methods include teaching, training, storytelling, discussion and directed research.<br> Educational website can include websites that have games, videos or topic related resources that act as tools to enhance learning and supplement classroom teaching. These websites help make the process of learning entertaining and attractive to the student, especially in today's age. <br>Using HTML(HyperText Markup Language), CSS(Cascading Style Sheet), JavaScript, we can make learning more easier and in a interesting way.</p>
				</div>
		</div>
	</div>


<!-- PORTFOLIO -->
	<div class="diffSection" id="portfolio_section">
		<center><p style="font-size: 50px; padding: 100px; padding-bottom: 40px;">Portfolio</p></center>
		<div class="content">
			<p>
				“Education is the passport to the future, for tomorrow belongs to those who prepare for it today.” “Your attitude, not your aptitude, will determine your altitude.” “If you think education is expensive, try ignorance.” “The only person who is educated is the one who has learned how to learn …and change.”
			</p>
		</div>
	</div>
	<div class="extra">
		<p>We're increasing this data every year</p>
		<div class="smbox">
		<span><center><div class="data">154</div><div class="det">Enrolled Students</div></center></span>
		<span><center><div class="data">62</div><div class="det">Total Courses</div></center></span>
		<span><center><div class="data">56</div><div class="det">Placed Students</div></center></span>
		<span><center><div class="data">27</div><div class="det">Total Projects</div></center></span>
		</div>
	</div>


<!-- TEAM -->
<div class="diffSection" id="team_section">
    <center><p style="font-size: 50px; padding-top: 100px; padding-bottom: 60px;">We're the Creators</p></center>
    <div class="totalcard">
        <div class="card">
            <center><img src="https://i.pinimg.com/1200x/3a/50/ff/3a50ffd3f82f18382e58aa666ba312d6.jpg"></center>
            <center><div class="card-title">Anshuman Singh</div>
            <div id="detail">
                <p>“ Education is not a destination; it's a lifelong expedition where the more you explore, the richer your life becomes. So, embark on this adventure with enthusiasm and an open mind. “</p>
                <div class="duty"></div>
                <a href="https://www.linkedin.com/in/anshuman-singh-a483aa284/" target="_blank"><button class="btn-roshan">Follow +</button></a>
            </div>
            </center>
        </div>
        <div class="card">
            <center><img src=""></center>
            <center><div class="card-title">Kavya Gupta</div>
            <div id="detail">
                <p>“ The classroom is not just a space for learning facts; it's a laboratory for cultivating creativity, critical thinking, and a passion for lifelong discovery. “</p>
                <div class="duty"></div>
                <a href="" target="_blank"><button class="btn-akhil">Follow +</button></a>
            </div>
            </center>
        </div>
        <div class="card">
            <center><img src=""></center>
            <center><div class="card-title">Ramandeep Singh</div>
            <div id="detail">
                <p>“ Knowledge is the fuel for innovation, and education is the vehicle that takes you on a transformative journey from curiosity to expertise.“</p>
                <div class="duty"></div>
                <a href="" target="_blank"><button class="btn-akhil">Follow +</button></a>
            </div>
            </center>
        </div>
    </div>
</div>




<!-- SERVICES -->
	<div class="service-swipe">
		<div class="diffSection" id="services_section">
		<center><p style="font-size: 50px; padding: 100px; padding-bottom: 40px; color: #fff;">Services</p></center>
		</div>
		<a href="subjects/computer_courses.html"><div class="s-card"><img src="images/icon/computer-courses.png"><p>Free Online Computer Courses</p></div></a>
		<a href="subjects/jee.html"><div class="s-card"><img src="images/icon/brainbooster.png"><p>Building Concepts for Competitive Exams</p></div></a>
		<a href="#"><div class="s-card"><img src="images/icon/online-tutorials.png"><p>Online Video Lectures</p></div></a>
		<a href="subjects/jee.html#sample_papers"><div class="s-card"><img src="images/icon/papers.jpg"><p>Sample Papers of Various Competitive Exams</p></div></a>
		<a href="#"><div class="s-card"><img src="images/icon/p3.png"><p>Performance and Ranking Report</p></div></a>
		<a href="#contactus_section"><div class="s-card"><img src="images/icon/discussion.png"><p>Discussion with Our Tutors & Mentors</p></div></a>
		<a href="subjects/quiz.html"><div class="s-card"><img src="images/icon/q1.png"><p>Daily Brain Teasing Questions to Improve IQ</p></div></a>
		<a href="#contactus_section"><div class="s-card"><img src="images/icon/help.png"><p>24x7 Online Support</p></div></a>
	</div>





	<!-- CONTACT US -->
<div class="diffSection" id="contactus_section">
    <center><p style="font-size: 50px; padding: 100px">Contact Us</p></center>
    <div class="csec"></div>
    <div class="back-contact">
        <div class="cc">
        <form action="mailto:anshumanboard1@gmail.com" method="post" enctype="text/plain">
            <label>First Name <span class="imp">*</span></label><label style="margin-left: 185px">Last Name <span class="imp">*</span></label><br>
            <center>
            <input type="text" name="" style="margin-right: 10px; width: 175px" required="required"><input type="text" name="lname" style="width: 175px" required="required"><br>
            </center>
            <label>Email <span class="imp">*</span></label><br>
            <input type="email" name="mail" style="width: 100%" required="required"><br>
            <label>Message <span class="imp">*</span></label><br>
            <input type="text" name="message" style="width: 100%" required="required"><br>
            <label>Additional Details</label><br>
            <textarea name="addtional"></textarea><br>
            <button type="submit" id="csubmit">Send Message</button>
        </form>
        </div>
    </div>
</div>



<!-- /* FEEDBACK */ -->

<div class="title2" id="feedBACK">
	<span>Give Feedback</span>
	<div class="shortdesc2">
		<p>Please share your valuable feedback to us</p>
	</div>
</div>

<div class="feedbox">
	<div class="feed">
		<form action="mailto:anshumanboard1@gmail.com" method="post" enctype="text/plain">
			<label>Your Name</label><br>
			<input type="text" name="" class="fname" required="required"><br>
			<label>Email</label><br>
			<input type="email" name="mail" required="required"><br>
			<label>Additional Details</label><br>
			<textarea name="addtional"></textarea><br>
			<button type="submit" id="csubmit">Send Message</button>
		</form>
	</div>
</div>

<!-- Reviews by Students -->
<!--  -->

<!-- Sliding Information -->
	<marquee style="background: linear-gradient(to right, #FA4B37, #DF2771); margin-top: 50px;" direction="left" onmouseover="this.stop()" onmouseout="this.start()" scrollamount="20"><div class="marqu">“Education is the passport to the future, for tomorrow belongs to those who prepare for it today.” “Your attitude, not your aptitude, will determine your altitude.” “If you think education is expensive, try ignorance.” “The only person who is educated is the one who has learned how to learn …and change.”</div></marquee>

<!-- FOOTER -->
	<footer>
		<div class="footer-container">
			<div class="left-col">
				<img src="images/icon/logo - Copy.png" style="width: 200px;">
				<div class="logo"></div>
				<div class="social-media">
					<a href="#"><img src="images/icon\fb.png"></a>
					<a href="#"><img src="images/icon\insta.png"></a>
					<a href="#"><img src="images/icon\tt.png"></a>
					<a href="#"><img src="images/icon\ytube.png"></a>
					<a href="#"><img src="images/icon\linkedin.png"></a>
				</div><br><br>
				<p class="rights-text">Copyright © 2021 Created By Anshuman Singh All Rights Reserved.</p>
				<br><p><img src="images/icon/location.png"> Lovely Professional University<br>Phagwara, Punjab-144401</p><br>
				<p><img src="images/icon/phone.png"> +91-1234-567-890<br><img src="images/icon/mail.png">&nbsp; anshumanboard1@gmail.com</p>
			</div>
			<div class="right-col">
				<h1 style="color: #fff">Our Newsletter</h1>
				<div class="border"></div><br>
				<p>Enter Your Email to get our News and updates.</p>
				<form class="newsletter-form">
					<input class="txtb" type="email" placeholder="Enter Your Email">
					<input class="btn" type="submit" value="Submit">
				</form>
			</div>
		</div>
	</footer>

</body>
</html>
