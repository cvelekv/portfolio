<!DOCTYPE html>
<html>
<body>

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

<meta name="viewport" content="width=device-width, initial-scale=1">

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/3.3.7/css/bootstrap.min.css">

<link rel="stylesheet" href="//fonts.googleapis.com/css?family=Lato:300,400,700,300italic,400italic,700italic">

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.5.2/animate.min.css">

<style>

@media only screen and (max-device-width: 400px) {  
  #pg1, #pg2, #pg3, .main { padding: 8px; }
  footer { text-shadow: 1px 1px 1px #85adad; }
}

html { scroll-behavior: smooth; }

body {
  background: url("https://i.pinimg.com/564x/c4/16/ce/c416cec658acbff32fb69f8c54791249.jpg");
  font-family: "Lato", "Helvetica Neue";
}

#aboutMe {
  background-color: #d1e0e0;
  font-size: 1.3em;
  color: black;
  text-shadow: 2px 2px 1px white;
  box-shadow: 2px 4px 15px #85adad;
  border-radius: 41px;
  opacity: 0.7;
  width: 96%;
  margin-left: auto;
  margin-right: auto;
}

.header {
  background: url("https://i.pinimg.com/564x/04/75/5d/04755d0c63f26806b855bd42358df3bf.jpg");
  box-shadow: 2px 4px 15px #85adad;
  border-radius: 5px;
  border-bottom: 2px solid #527a7a;
}

.pageOne, .pageTwo, .pageThree {
  background-size: cover;
  height: auto;
  border: 1px solid silver;
  padding: 31px;
  border-radius: 11px;
  margin-bottom: 15px;
  box-shadow: 21px 5px 71px grey;
}

.pageOne {
  background: url("https://images.unsplash.com/photo-1474377207190-a7d8b3334068?dpr=1&auto=compress,format&fit=crop&w=1500&h=&q=80&cs=tinysrgb&crop=");
  margin-top: 77px;
  color: lavender;
  text-shadow: 2px 2px 2px black;
}

.pageTwo {
  background: url("https://i.pinimg.com/564x/d6/54/75/d6547570f7ce600c6bdbc0a6fb34f633.jpg");
  padding-top: 12px;
}

.pageThree {
  background: url("https://images.unsplash.com/photo-1494135820019-7afdee2d494f?dpr=1&auto=compress,format&fit=crop&w=1500&h=&q=80&cs=tinysrgb&crop=");
  padding-top: 60px;
  padding-bottom: 11px;
}

h1 {
  font-size: 4.3em;
  margin-top: 7px;
  padding: 20px;
}

p2, p3, h4 {
  font-size: 3.2em;
  color: ghostwhite;
  text-shadow: 1px 1px 1px #00e6e6;
}

p1 {
  color: #006666;
  font-size: 1.31em;
  text-shadow: 1px 1px floralwhite;
}

h2 { font-size: 2em; }

h4 { font-size: 2.2em; }

p3 { text-shadow: 1px 2px 6px #527a7a; }

.btnList {
  padding: 21px;
  margin-bottom: 71px;
}

.btn-default {
  background-color: #f2f2f2;
  font-size: 1.7em;
  margin: 3px;
  opacity: 0.88;
}

.mailForm, .submitbtn {
  background-color: ghostwhite;
  border-radius: 7px;
  opacity: 0.8;
  box-shadow: 2px 2px 3px grey;
}

.mailForm {
  font-size: 20px;
  height: 37px;
  width: 260px;
  margin: 2px;
  margin-top: 5px;
}

.submitbtn {
  font-size: 18px;
  height: 33px;
  margin-top: 11px;
}

</style>

<nav class="navbar navbar-fixed-top animated fadeInDown">
  <header class="header">
    <ul class="nav nav-pills">
      <li class="pull-left">
        <a href="#home">
          <p1><i class="fa fa-home" aria-hidden="true"></i></p1>
        </a>
      </li>
      <li class="pull-right">
        <a href="#pg3">
          <p1>Contact</p1>
        </a>
      </li>
      <li class="pull-right">
        <a href="#pg2">
          <p1>Portfolio</p1>
        </a>
      </li>
      <li class="pull-right">
        <a href="#aboutMe">
          <p1>About me</p1>
        </a>
      </li>
    </ul>
  </header>
</nav>

<div class="container main text-center animated fadeIn">
  <!-- start of all pages -->

  <!-- page one -->
  <div class="pageOne text-center" id="pg1">
    <h1>Nikola Djekic</h1>
    <img style="border-radius:50%; width:18em; border:1px solid lavender;" src="https://lh3.googleusercontent.com/-1AQiv-J_j3U/W4WGmG6qJsI/AAAAAAAAGvw/4SsAuyVRaxwUeltoR2ahhQZSAI2tu2ESACL0BGAs/w530-h530-n/Linked%2Bin%2Bsmall20180827_153048.jpg"></img>
    <h2>Junior Front-End Developer</h2>
    <h2><i class="fa fa-free-code-camp" aria-hidden="true"></i> FreeCode Camper</h2>
    <br>
    <br>
    <div class="well" id="aboutMe">
      <h3 style="text-decoration:underline;">About me:</h3>
      <p>Born and raised in Belgrade, I finished Electrotechnical Highschool „Nikola Tesla“, as a Telecommunications Technician. I started working right after Highschool, and after a few years on various types of jobs, travelling the world and finding myself,
        I spent three years in Austria, where my application for Bachelor studies was accepted on „Johannes Kepler“ University in Linz, a nice and peacefull town in province of Upper Austria. As my studies were focused more on the bussiness side of things
        and not really matching up to my expectations, I started learning on my own over the courses available on the internet. After finishing few of them and lots of material read as well as many tutorials watched, I’ve done a lot of thinking and weighing
        out my options, and finally made a hard decision to drop out of studies in Linz and henceforth focus all my time and energy only on programming.</p>
    </div>
    <br>
  </div>
  <!-- end of page one -->

  <!-- page two -->
  <div class="pageTwo" id="pg2">
    <p2 style="text-decoration:underline;">PORTFOLIO</p2>
    <br>
    <br>
    <div class="row">

      <div class="col-lg-6 col-xs-12 text-center" id="porCube">
        <h4>Pomodoro Clock</h4>
        <p data-height="333" data-theme-id="1" data-slug-hash="KQMwvo" data-default-tab="result" data-user="nikoladjekic" data-pen-title="Pomodoro Clock - FreeCodeCamp" class="codepen">See the Pen <a href="https://codepen.io/nikoladjekic/pen/KQMwvo/">Pomodoro Clock - FreeCodeCamp</a> by Nikola (<a href="https://codepen.io/nikoladjekic">@nikoladjekic</a>) on <a href="https://codepen.io">CodePen</a>.</p>
        <script async src="https://static.codepen.io/assets/embed/ei.js"></script>
        <a href="https://codepen.io/Nikilla/full/NapPXZ/" target="blank"></a>
      </div>

      <div class="col-lg-6 col-xs-12 text-center" id="porCube">
        <h4>Local Weather App</h4>
        <p data-height="333" data-theme-id="1" data-slug-hash="jazObE" data-default-tab="result" data-user="nikoladjekic" data-embed-version="2" data-pen-title="Local Weather App" class="codepen">See the Pen <a href="https://codepen.io/nikoladjekic/pen/jazObE/">Local Weather App</a> by Djeka (<a href="https://codepen.io/nikoladjekic">@nikoladjekic</a>) on <a href="https://codepen.io">CodePen</a>.</p>
        <script async src="https://production-assets.codepen.io/assets/embed/ei.js"></script>
        <a href="https://codepen.io/nikoladjekic/full/jazObE/" target="blank">          
        </a>
      </div>

      <div class="col-lg-6 col-xs-12 text-center" id="porCube">
        <h4>TicTacToe game</h4>
        <p data-height="333" data-theme-id="1" data-slug-hash="gveejj" data-default-tab="result" data-user="nikoladjekic" data-pen-title="TicTacToe Game - JQuery" class="codepen">See the Pen <a href="https://codepen.io/nikoladjekic/pen/gveejj/">TicTacToe Game - JQuery</a> by Nikola (<a href="https://codepen.io/nikoladjekic">@nikoladjekic</a>) on <a href="https://codepen.io">CodePen</a>.</p>
        <script async src="https://static.codepen.io/assets/embed/ei.js"></script>
      </div>

      <div class="col-lg-6 col-xs-12 text-center" id="porCube">
        <h4>Wikipedia search engine</h4>
        <p data-height="333" data-theme-id="1" data-slug-hash="eyGmOW" data-default-tab="result" data-user="nikoladjekic" data-embed-version="2" data-pen-title="Wikipedia Viewer" class="codepen">See the Pen <a href="https://codepen.io/nikoladjekic/pen/eyGmOW/">Wikipedia Viewer</a> by Djeka (<a href="https://codepen.io/nikoladjekic">@nikoladjekic</a>) on <a href="https://codepen.io">CodePen</a>.</p>
        <script async src="https://production-assets.codepen.io/assets/embed/ei.js"></script>
      </div>

    </div>
    <br>
    <a style="color:#ccffff; text-shadow: 1px 1px 1px black;" href="https://codepen.io/nikoladjekic/pens/popular/#" target="_blank">Click here to see more projects</a>
  </div>
  <!-- end of page two -->

  <!-- page three -->
  <div class="pageThree text-center" id="pg3">
    <p3>Find me on social media</p3>
    <div class="btnList">

      <a class="btn btn-default" href="https://www.facebook.com/nikola.djekic.524" target="_blank"><i class="fa fa-facebook-square fa-lg" aria-hidden="true"></i> Facebook</a>

      <a class="btn btn-default" href="https://www.github.com/nikoladjekic" target="_blank"><i class="fa fa-github-square fa-lg" aria-hidden="true"></i> GitHub</a>

      <a class="btn btn-default" href="https://www.linkedin.com/in/nikola-djekic-a1134316a/" target="_blank"><i class="fa fa-linkedin-square fa-lg" aria-hidden="true"></i> LinkedIn</a>

      <a class="btn btn-default" href="https://codepen.io/nikoladjekic/#" target="_blank"><i class="fa fa-codepen fa-lg" aria-hidden="true"></i> CodePen</a>
    </div>

    <div>
      <p3>or e-mail me below</p3>
      <form action="mailto:nikoladj.21@gmail.com" method="post" enctype="text/plain">
        <input class="mailForm" type="text" placeholder="*Name" name="name" required><br>
        <input class="mailForm" type="text" placeholder="*E-Mail Address" name="mail" required><br>
        <input class="mailForm" type="text" placeholder="*Comment" name="comment" required><br>
        <input class="mailForm" type="text" placeholder="Phone"><br>
        <input class="mailForm" type="text" placeholder="Website"><br>
    </div>
    <button class="submitbtn" type="submit"> Submit</i></button><br>

    <!-- footer note -->
    <br>
    <br>
    <br>
    <footer class="text-center" style="font-size:1.1em">INFO: This Page was created and designed by <strong>Nikola Djekic</strong>, using HTML5 <i class="fa fa-html5 fa-lg" aria-hidden="true"></i> and CSS3 <i class="fa fa-css3 fa-lg" aria-hidden="true"></i>. &#169 2018.</footer>

  </div> <!-- end of page three -->
</div> <!-- end of container -->
</body>
</html>