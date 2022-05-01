<!DOCTYPE html>
<html>
  <head>
      <meta charset="utf-8">
      <meta name="viewport" content="width=device-width">
      <title>Portfolio site template</title>
      <link href="style.css" rel="stylesheet" type="text/css" />
      <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.13.0/css/all.css">
      <link rel="icon" href="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b2/Repl.it_logo.svg/220px-Repl.it_logo.png">
      <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
      <script src="script.js"></script>
  </head>
    <body>
	  
        <div class="container">
	  
		<!--────────────────Header───────────────-->
	<header>
		<a class="logo" href="#home">
              <img src="https://newsletter-images--timmy-i-chen.repl.co/logo-light.png" alt="repl logo" />
		</a>
		<nav>	
		 <ul class="nav-bar"><div class="bg"></div>
			<li><a class="nav-link active" href="#home">Home</a></li>
			<li><a class="nav-link" href="#projects">Projects</a></li>
			<li><a class="nav-link" href="#contact">Contact</a></li>
		 </ul>
			
			<div class="hamburger">
				<div class="line1"></div>
            <div class="line2"></div>
				<div class="line3"></div>
			</div>
		</nav>
	</header>
	<main>
		<!--─────────────────Home────────────────-->
	  <div id="home">
		 <div class="filter"></div>
		 <section class="intro">
		  <h3>Your Name.<hr></h3>
		  <p>Short Description.</p>
		  <p>Something more about yourself.</p>
          <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit.</p>
			  
		  <!--────social media links─────-->
			 
		  <div class="social-media">
			  <a href="#" target="_blank"><i class='fab fa-codepen'></i></a>
			  <a href="#" target="_blank"><i class='fab fa-twitter'></i></a>
			  <a href="#" target="_blank"><i class='fab fa-github'></i></a>
			  <a href="#" target="_blank"><i class='fab fa-linkedin-in'></i></a>
			  <a href="#" target="_blank"><i class="fab fa-youtube"></i></a>
		    </div>
			 
		 </section> 
	  </div>  
		
	  <!--───────────────Projects───────────────-->
	  <div id="projects"> 
		 <h3>My Projects.<hr></h3>
		  <p>Here are some of my projects, you may like.</p>
		  <div class="work-box">
		  <div class="work">
		<!--───────────────card───────────────-->
			<div class="card">
			    <img class="work-img" src="https://images.unsplash.com/photo-1518611507436-f9221403cca2?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1225&q=80">
			    <a href="" target="_blank"> <!--Link to project-->
				<div class="work-content">Lorem ipsum dolor sit amet consectetur.</div></a>
            </div>
			<div class="card">
			    <img class="work-img" src="https://images.unsplash.com/photo-1462642109801-4ac2971a3a51?ixlib=rb-1.2.1&auto=format&fit=crop&w=1266&q=80">
				<a href="" target="_blank"> <!--Link to project-->
				<div class="work-content">Lorem ipsum dolor sit amet consectetur.</div></a>
            </div>
            <div class="card">
			    <img class="work-img" src="https://images.unsplash.com/photo-1485815457792-d1a966f9bde0?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80">
				<a href="" target="_blank"> <!--Link to project-->
				<div class="work-content">Lorem ipsum dolor sit amet consectetur.</div></a>
            </div>
            <div class="card">
			    <img class="work-img" src="https://images.unsplash.com/photo-1517842645767-c639042777db?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80">
				<a href="" target="_blank"> <!--Link to project-->
				<div class="work-content">Lorem ipsum dolor sit amet consectetur.</div></a>
            </div> 
			<div class="card">
			    <img class="work-img" src="https://images.unsplash.com/photo-1535556116002-6281ff3e9f36?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=781&q=80">
				<a href="" target="_blank"> <!--Link to project-->
				<div class="work-content">Lorem ipsum dolor sit amet consectetur.</div></a>
            </div>
			<div class="card">
			    <img class="work-img" src="https://images.unsplash.com/photo-1483546416237-76fd26bbcdd1?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80">
				<a href="" target="_blank"> <!--Link to project-->
				<div class="work-content">Lorem ipsum dolor sit amet consectetur.</div></a>
            </div> 	  
		  </div>
		  </div>
	  </div>
		 
		<!--──────────────Contact────────────────-->
	  <div id="contact">
		  <!--────social media links─────-->
		   <h3>Contact.<hr></h3>
		   <p>Feel free to contact me on my social media.</p>
		    <div class="social-media">
			  <a href="#" target="_blank"><i class='fab fa-codepen'></i></a>
			  <a href="#" target="_blank"><i class='fab fa-twitter'></i></a>
			  <a href="#" target="_blank"><i class='fab fa-github'></i></a>
			  <a href="#" target="_blank"><i class='fab fa-linkedin-in'></i></a>
			  <a href="#" target="_blank"><i class="fab fa-youtube"></i></a>
		    </div>
		  </div>

	</main>
	  <footer class="copyright">© 2020 
		  <a href="https://repl.it/@lilykhan" target="_blank"> Lilykhan.</a>
     </footer>
	  
  </div>
  </body>
</html>
