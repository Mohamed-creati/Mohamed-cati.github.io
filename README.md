
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>My Portfolio</title>
  
<body>
  <div class="hero">
      <!--header secion starts here-->
        <header> 
            
            <nav>
                <h2 class="logo">Portfo<span>lio</span></h2>
                <ul>
                    <li><a href="index.html">About Me</a></li>
                    <li><a href="contact.html">Contact Me</a></li>
                    <li><a href="registration.html">Registration</a></li>
                </ul>
                <a href="login.html" class="btn">Login</a>
            </nav>

        </header>

        <main>
            <!--home section starts here-->
            <div class="detel">
                <h1>I'm Itoro <span>Joseph</span></h1>
                
                <p>Hobbyist Web Developer with a working proficiency <br> in
                    HTML, CSS, and Bootstrap. I have solid understanding <br> of Linux,
                    SASS, and Git. Currently working to take the step <br> from Hobbyist 
                    to Professional.</p>
                    <br>
                    <br>
                <p>Connect with me on</p>
                <div class="logos">
                    <i class="fa-brands fa-github"></i>
                    <i class="fa-brands fa-twitter"></i>
                    <i class="fa-brands fa-linkedin-in"></i>
                </div>
            </div>
               
            <div class="images">
                <img src="images/shape-27325.png" alt="shapes-banner" class="shape">
                <div class="portrait"><img src="images/backgoundimg.jpeg"></div>
            </div>
    </div>
    <div class="hero-2">
          <!--about me secion starts here-->
            <div class="about">
                <div class="title">
                    <h2>About Me...</h2>
                </div>

                <div class="box">
                    <div class="card">
                        <i class="fa-solid fa-plug"></i>
                        <h3>Hobbies</h3>
                        <div class="para">
                            <ul>  
                                <li>Reading</li>
                                <li>Video games</li>
                                <li>Fitness</li>
                            </ul>
                        </div>
                    </div>

                    <div class="card">
                        <i class="fa-solid fa-plug"></i>
                        <h3>Priorities</h3>
                        <div class="para">
                            <ul>  
                                <li>God</li>
                                <li>Relationships</li>
                                <li>Career</li>
                            </ul>
                        </div>
                </div>

                <div class="card">
                    <i class="fa-solid fa-business-time"></i>
                    <h3>Skills</h3>
                    <div class="para">
                        <ul>  
                            <li>Programming</li>
                            <li>Digital Marketing</li>
                            <li>Technical Writing</li>
                        </ul>
                    </div>
                </div>
                
                </div>
                <button type="button">Contact Me</button>
            </div>
            
        </main>
        <footer>
            <p class="copyright">digitalnobsx© 2022 </p>
        </footer>

    </div>
</body>

</html>






<html>

<head>

  <title>What appears in browser tab</title>

</head>

<body>
  <!-- Largest heading size-->
  <h1>My first web page</h1>
  
   <!-- Sub heading-->
  <h2>Just Text!</h2>

  <!-- paragraph tag is used for adding text-->
  <p>In different sizes</p>
  <p>I can write as many paragraphs as I need...</p>


<img src="images/image.jpg">

  
</body>

</html>




<h1>Hello!</h1>
<p>My name is Mohamed</p>
<p>I like <b>boxing</b> and <i>fishing</i>

  - title: General Information
  type: map
  contents:
    - name: Full Name
      value: Albert Einstein
    - name: Date of Birth
      value: 14th March 1879
    - name: Languages
      value: English, German

- title: Education
  type: time_table
  contents:
    - title: PhD
      institution: University of Zurich, Zurich, Switzerland
      year: 1905
      description:
        - Description 1.
        - Description 2.
        - title: Description 3.
          contents:
            - Sub-description 1.
            - Sub-description 2.
    - title: Federal teaching diploma
      institution: Eidgenössische Technische Hochschule, Zurich, Switzerland
      year: 1900
      description:
        - Description 1.
        - Description 2.

- title: Experience
  type: time_table
  contents:
    - title: Professor of Theoretical Physics
      institution: Institute for Advanced Study, Princeton University
      year: 1933 - 1955
      description:
        - Description 1.
        - Description 2.
        - title: Description 3.
          contents:
            - Sub-description 1.
            - Sub-description 2.
    - title: Visiting Professor
      institution: California Institute of Technology, Pasadena, California, US
      year: 1933
      description:
        - Description 1.
        - Description 2.

    - title: Director
      institution: Kaiser Wilhelm Institute for Physics, Berlin, Germany.
      year: 1917-1933

    - title: Professor of Theoretical Physics
      institution: Karl-Ferdinand University, Prague, Czechoslovakia
      year: 1911 - 1917
      description:

    - title: Associate Professor of Theoretical Physics
      institution: University of Zurich, Zurich, Switzerland
      year: 1909 - 1911

- title: Open Source Projects
  type: time_table
  contents:
    - title: <a href="https://github.com/alshedivat/al-folio">al-folio</a>
      year: 2015-now
      description: A beautiful, simple, clean, and responsive Jekyll theme for academics.

- title: Honors and Awards
  type: time_table
  contents:
    - year: 1921
      items: 
        - Nobel Prize in Physics 
        - Matteucci Medal
    - year: 2029
      items: 
        - Max Planck Medal

- title: Academic Interests
  type: nested_list
  contents:
    - title: Topic 1.
      items: 
        - Description 1.
        - Description 2.
    - title: Topic 2.
      items:
        - Description 1.
        - Description 2.

- title: Other Interests
  type: list
  contents:
    - <u>Hobbies:</u> Hobby 1, Hobby 2, etc.
