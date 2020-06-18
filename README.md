# Product-Landing-Page

<!DOCTYPE html>
<html>
  <head>
    <title>  WeTech Landing Page </title>
    <style>
      body {
        background-image: url(https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcSTodNabP1o0GQPNIcfFeCqNb5EQ0H3r6H8nQcd4_Kt3pzbLiMy&usqp=CAU);
      background-size: cover;
        background-blend-mode: multiply;
      }
   #header {
     height: 6vh;
      }
   #nav-bar {
     position: fixed;
     
     background-color: rgb(18,19,231);
     overflow: hidden;
     top: 0;
     width: 100%;
      }
       .nav-class {
         color: white;
      }
      #nav-bar a {
        float: right;
        display: block;
        text-decoration: none;
        text-align: center;
       
        color: white;
      }
      #nav-bar ul {
        list-style: none;
        display: inline;
        text-align: right;
      }
  #header-img {
width: 100px;
      }
    #nav-bar li {
     display: inline;
     list-style: none;
      }
      #nav-bar li a {
        height: 50px;
        width: 6em;
        text-decoration: none;
        line-height: 1.5;
        font-size: 2em;
       text-align: center;
      }
       
      
     
      

  
      
      .landing {
        height: 8vh;
        background: #eeeeee;
        text-align: center;
        font-size: 5em;
        line-height: 1.5;
        color: rgb(18,19,231);
      }
      .search {
     width: 15em;
        height: 20px;
        font-size: 20px;
      }
      .submit {
        background-color: green;
        font-size: 20px;
        height: 2em;
      }
      .more {
        line-height: 10;
      }
      section {
       
     
  
       
        line-height: 2;
      }
      #many {
        text-align: center;
      }
      h2 {
        font-size: 4em;
        color: white;
      }
      p {
        font-size: 2em;
        color: white;
      }
      .img {
        width: 200px;
        
      }
      #video {
        text-align: center;
      }
      #footer {
        text-align: center;
        
        height: 3vh;
        background-color: rgb(18,19,231);
      
      }
      #footer ul {
        list-style: none;
      }
      #footer li {
        display: inline;
        padding: 3em;
        font-size: 2em;
        color: white;
        line-height: 1.5;
        width: 10em;
      }
      .nav-link {
        
      }
      @media (max-width:100px) {
        p {
          font-size: 2em;
        }
      }
        #form {
          text-align: center;
          display: flex;
          justify-content: center;
          align-content: center;
      }
     #email {
        font-size: 20px;
      }
      h3 {
        font-size: 30px;
        color: white;
      }
      
      
      #submit {
      font-size: 20px;
        background-color: green;
        padding: 0.5em;
        border: none;
        border-radius: 5px;
      }
      .line {
        line-height: 1;
      }
    </style>
  </head>
  <body>
    <header id="header">
     
      <nav id="nav-bar">
      <div> <img id="header-img" src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcTNB1cctc3xpDiir47wnRUMfR3RwUx_a9NEzHFE0_enwAfOMma2&usqp=CAU" alt="logo"> WeTech </div>
        <div>
        <ul>
          <li> <a href="#many" class="nav-link"> Home </a> </li>
          <li> <a href="#video" class="nav-link"> Services </a> </li>
          <li> <a href="#footer" class="nav-link"> Blog </a> </li>
        </ul>
        </div>
      </nav>
      </div>
    </header>
    <main>
      <div>
        <h1 class="landing"> WeTech </h1>
      </div>
      <section>
      <div class="more" style="text-align: center;">
        <input class="search" type="text" name="search" placeholder="search anything">
        <input class="submit" type="submit" placeholder="search">
      </div>
      
        <div id="many">
          <h2> The future of tech is here </h2>
        <p> Holisticly incentve  revolutionary, <br> collaboration and idea sharing before cost effective users. <br> Actual focused services before highly efficient human capital. </p>
          <h2> Start second guessing </h2>
          <p> Hold  back misleading content on the web. <br> Join the WeTech family to check the integrity of <br> the websites you behind what you find online.  </p>
          <h2>  Get started </h2>
          <img class="img" src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcRcM6Q9uXQPU2FSEsHOw4zm-blClPRVvMlCexRjEOBwBYnPOtRr&usqp=CAU" alt="logo of html">
        
        
      
        <h2> Check out top 7 technologies </h2>
       <iframe id="video" width="560" height="315" src="https://www.youtube.com/embed/AuVHftBiDVw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
          </div>
        </section>                                                                             
    </main>
    <div class="line">
      <h3> Sign up for  newsletter </h3>
    
    
      <form id="form" action="https://www.freecodecamp.com/email-submit">
       <input type="email" id="email" name="email" placeholder="Enter email">
        <input type="submit" id="submit" placeholder="Sign up"> 
      </form>
    </div>
    <div>
    <footer id="footer">
    <ul>
      <li> Contact Us </li>
      <li> Feedback </li>
      <li> Polices </li>
      </ul>
      </footer>
    </div>
    
    
    
    
    
  </body>
  <script src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"> </script>
</html>
