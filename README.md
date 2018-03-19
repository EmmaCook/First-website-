# First-website-
Using a template to make a CV 

This is the first time I've tried to make a website. I'm using TextEdit on Mac 
and saving my code here. 

I need to save it as plane text, and then open it with a web browser. 

I want to be able to put my own domain on it. 


<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Emma Cook</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css?family=Raleway:200,300,400,500,600,700,800" rel="stylesheet">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
  </head>
  <body>

    <!-- BEGIN NAVBAR -->
    <div class="navbar">
      <a href="#about">About</a>
      <a href="#experience">Experience</a>
      <a href="#education">Education</a>
      <a href="#projects">Projects</a>
      <a href="#skills">Skills</a>
      <a href="#contact">Contact</a>
    </div>
    <!-- END NAVBAR -->

    <div class="container">

      <!-- HEADER -->
      <div class="jumbotron">
        <div class="jumbotron-text">
          <h1>Emma Cook</h1>
          <p>Soon to be Front End Web Developer (Hoping to look at Full-Stack) in Manchester, UK.</p>
        </div>
        <div class="jumbotron-social">
          <ul class="ul-social">
            <li class="li-social-links">
              <a class="social" href="https://github.com/" target="_blank"><i class="fa fa-github" aria-hidden="true"></i></a>
            </li>
            <li class="li-social-links">
              <a class="social" href="https://linkedin.com" target="_blank"><i class="fa fa-linkedin" aria-hidden="true"></i></a>
            </li>
            <li class="li-social-links">
              <a class="social" href="https://www.facebook.com/" target="_blank"><i class="fa fa-facebook" aria-hidden="true"></i></a>
            </li>
            <li class="li-social-links">
              <a class="social" href="https://twitter.com/" target="_blank"><i class="fa fa-twitter" aria-hidden="true"></i></a>
            </li>
            <li class="li-social-links">
              <a class="social" href="https://plus.google.com/" target="_blank"><i class="fa fa-google-plus" aria-hidden="true"></i></a>
            </li>
          </ul>
        </div>
        <div id="down-arrow">
          <span><a href="#about"><i class="fa fa-chevron-down" aria-hidden="true"></i></a></span>
        </div>
      </div>
      <!-- END HEADER -->



      <!-- BEGIN ABOUT -->
      <div class="row white box-shadow">
        <div class="side-content"></div>
        <div class="main-content">
          <div class="content-header">
            <a class="anchor" name="about"></a>
            <h2>About</h2>
          </div>
          <div class="content-body">
            <p>Something about me</p>
          </div>
        </div>
        <div class="side-content"></div>
      </div>
      <!-- END ABOUT -->

      <!-- BEGIN EXPERIENCE -->
      <div class="row">
        <div class="side-content"></div>
        <div class="main-content">
          <div class="content-header">
            <a class="anchor" name="experience"></a>
            <h2>Experience</h2>
          </div>
          <!-- CARD #1 -->
          <div class="content-body">
            <div class="card">
              <div class="card-header">
                <h4>Audit Partnership<span class="job-title">Human Resources Officer</span></h4>
              </div>
              <div class="card-content">
                <p>A little bit about working in HR.</p>
              </div>
            </div>

          <!-- CARD #2 -->

            <div class="card">
              <div class="card-header">
                <h4>Starbucks <span class="job-title">Barista</span></h4>
              </div>
              <div class="card-content">
                <p>Everyones got to start somewhere right!</p>
              </div>
            </div>

          <!-- CARD #3 -->

            <div class="card">
              <div class="card-header">
                <h4>Audit Partnership <span class="job-title">Business Development Executive</span></h4>
              </div>
              <div class="card-content">
                <p>Before that I worked at APL in their Business Development team.</p>
              </div>
            </div>
          </div>
        </div>
        <div class="side-content"></div>
      </div>
      <!-- END EXPERIENCE -->

      <!-- BEGIN EDUCATION -->
      <div class="row white box-shadow">
        <div class="side-content"></div>
        <div class="main-content">
          <div class="content-header">
            <a class="anchor" name="education"></a>
            <h2>Education</h2>
          </div>
          <div class="content-body">

            <!-- EDUCATION 1 -->
            <div class="card">
              <div class="card-header">
                <h4>University of Manchester <span class="job-title">From 2015-2018</span></h4>
              </div>
              <div class="card-content">
                <p>I did a degree in Economics which was boring as hell, but was introduced to coding in R and now I'm set on becoming a web developer.</p>
              </div>
            </div>
            <!-- EDUCATION 2 -->
            <div class="card">
              <div class="card-header">
                <h4>Tadcaster Grammar School <span class="job-title">Did my GCSEs and A levels here</span></h4>
              </div>
              <div class="card-content">
                <p>I guess I used to be good at school... back in the day.</p>
              </div>
            </div>

          </div>
        </div>
        <div class="side-content"></div>
      </div>
      <!-- END EDUCATION -->

      <!-- BEGIN PROJECTS -->
      <div class="row">
        <div class="side-content-sm"></div>
        <div class="main-content-lg">
          <div class="content-header">
            <a class="anchor" name="projects"></a>
            <h2>Projects</h2>
          </div>
          <div class="content-body">
            <!-- CARD #1 -->
            <div class="project-card">
              <div class="project-image">
                <img src="http://placehold.it/250x350">
              </div>
              <div class="project-content">
                <h4>My first website</h4>
                <p>Here it is!!.</p>
                <a href="#">Link Text</a>
              </div>
            </div>
            <!-- CARD #2 -->
            <div class="project-card">
              <div class="project-image">
                <img src="http://placehold.it/250x350">
              </div>
              <div class="project-content">
                <h4>Dissertation Presentation</h4>
                <p>I made a nice-ish looking html ioslides presentation but I'm hoping to workout how to make this look amazing instead of average.</p>
                <a href="#">Link Text</a>
              </div>
            </div>
            <!-- CARD #3 -->
            <div class="project-card">
              <div class="project-image">
                <img src="http://placehold.it/250x350">
              </div>
              <div class="project-content">
                <h4>To be confirmed...</h4>
                <p>Let's see what I can do...</p>
                <a href="#">Link Text</a>
              </div>
            </div>

          </div>
        </div>
        <div class="side-content-sm"></div>
      </div>
      <!-- END PROJECTS -->

      <!-- BEGIN SKILLS -->
      <div class="row white box-shadow">
        <div class="side-content"></div>
        <div class="main-content">
          <div class="content-header">
            <a class="anchor" name="skills"></a>
            <h2>Skills</h2>
          </div>
          <div class="content-body">
            <ul class="ul-skills">
	      <li class="li-skills">I'd say this is quite hopeful! Hahaa</li>	
              <li class="li-skills">Javascript</li>
              <li class="li-skills">HTML</li>
              <li class="li-skills">CSS</li>
              <li class="li-skills">React</li>
              <li class="li-skills">Node.js</li>
              <li class="li-skills">Bootstrap</li>
              <li class="li-skills">Webpack</li>
              <li class="li-skills">jQuery</li>
              <li class="li-skills">Javascript</li>
              <li class="li-skills">HTML</li>
              <li class="li-skills">CSS</li>
              <li class="li-skills">React</li>
              <li class="li-skills">Node.js</li>
              <li class="li-skills">Bootstrap</li>
              <li class="li-skills">Webpack</li>
              <li class="li-skills">jQuery</li>
            </ul>
          </div>
        </div>
        <div class="side-content"></div>
      </div>
      <!-- END SKILLS -->

      <!-- BEGIN CONTACT -->

      <div class="row blue">
        <div class="side-content"></div>
        <div class="main-content">
          <div class="content-header">
            <a class="anchor" name="contact"></a>
            <h2 class="white-text">Contact Me</h2>
          </div>
          <div class="contact content-body">
            <form method="POST" action="https://formspree.io/emma.l.cook1@gmail.com">
                <input type="hidden" name="_subject" value="Contact request from personal website" />
                <input type="email" name="_replyto" placeholder="Your email" required>
                <textarea name="message" placeholder="Your message" required></textarea>
                <button type="submit">Send</button>
            </form>
          </div>
        </div>
        <div class="side-content"></div>
      </div>
      <!-- END CONTACT -->

      <!-- BEGIN FOOTER -->
      <div class="row">
        <div class="side-content"></div>
        <div class="main-content">
          <div class="content-header">
          </div>
          <div class="content-body">
            <p>Copyright EMMA COOK 2017</p>
          </div>
        </div>
        <div class="side-content"></div>
      </div>
      <!-- END FOOTER -->

    </div>
  </body>
</html>
