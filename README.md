<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Muneeb Tariq - Personal Portfolio</title>

  <!--
    - favicon
  -->
  
  <!--
    - custom css link
  -->
  <link rel="stylesheet" href="./assets/css/style.css">

  <!--
    - google font link
  -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600&display=swap" rel="stylesheet">
</head>

<body>

  <!--
    - #MAIN
  -->

  <main>

    <!--
      - #SIDEBAR
    -->

    <aside class="sidebar" data-sidebar>

      <div class="sidebar-info">

        <figure class="avatar-box">
          <img src="./assets/images/muneeb(1).jpg" alt="Richard hanrick" width="80" style=" border-radius: 20px">
        </figure>

        <div class="info-content">
          <h1 class="name" title="Muneeb Tariq">Muneeb Tariq</h1>

          <p class="title">  AI Engineer <br> Django Developer </p>
        </div>

        <button class="info_more-btn" data-sidebar-btn>
          <span>Show Contacts</span>

          <ion-icon name="chevron-down"></ion-icon>
        </button>

      </div>

      <div class="sidebar-info_more">

        <div class="separator"></div>

        <ul class="contacts-list">

          <li class="contact-item">

            <div class="icon-box">
              <ion-icon name="mail-outline"></ion-icon>
            </div>

            <div class="contact-info">
              <p class="contact-title">Email</p>

              <a href="mailto:muhammadmuneebtariq07@gmail.com" class="contact-link">muhammadmuneeb<br>tariq07@gmail.com</a>
            </div>

          </li>

          <li class="contact-item">

            <div class="icon-box">
              <ion-icon name="phone-portrait-outline"></ion-icon>
            </div>

            <div class="contact-info">
              <p class="contact-title">Phone</p>

              <a href="tel:+92 336 9939547" class="contact-link">+92 336 9939547</a>
            </div>

          </li>

          <li class="contact-item">

            <div class="icon-box">
              <ion-icon name="calendar-outline"></ion-icon>
            </div>

            <div class="contact-info">
              <p class="contact-title">Birthday</p>

              <time datetime="2001-08-16">August 16, 2001</time>
            </div>

          </li>

          <li class="contact-item">

            <div class="icon-box">
              <ion-icon name="location-outline"></ion-icon>
            </div>

            <div class="contact-info">
              <p class="contact-title">Location</p>

              <address>Islamabad, Pakistan</address>
            </div>

          </li>

        </ul>

        <div class="separator"></div>

        <ul class="social-list">

          

        

          <li class="social-item">
            <a href="https://www.linkedin.com/in/muhammad-muneeb-39172119a" class="social-link">
              <ion-icon name="logo-linkedin"></ion-icon>
            </a>
          </li>

          <li class="social-item">
            <a href="https://github.com/Sardarmani" class="social-link">
              <ion-icon name="logo-github"></ion-icon>
            </a>
          </li>


        </ul>

      </div>

    </aside>





    <!--
      - #main-content
    -->

    <div class="main-content">

      <!--
        - #NAVBAR
      -->

      <nav class="navbar">

        <ul class="navbar-list">

          <li class="navbar-item">
            <button class="navbar-link  active" data-nav-link>About</button>
          </li>

          <li class="navbar-item">
            <button class="navbar-link" data-nav-link>Resume</button>
          </li>

          <li class="navbar-item">
            <button class="navbar-link" data-nav-link>Portfolio</button>
          </li>

          <li class="navbar-item">
            <button class="navbar-link" data-nav-link>Blog</button>
          </li>

          <li class="navbar-item">
            <button class="navbar-link" data-nav-link>Contact</button>
          </li>

        </ul>

      </nav>





      <!--
        - #ABOUT
      -->

      <article class="about  active" data-page="about">

        <header>
          <h2 class="h2 article-title">About me</h2>
        </header>


        <section class="about-text">
          <div class="intro">
            <p>Hi, I'm Muneeb Tariq, a passionate and dedicated computer science student based in Islamabad, Pakistan. I have a strong foundation in software development and data analysis, with a keen interest in artificial intelligence and machine learning.</p>
            <p>Currently, I am pursuing a Bachelor's degree in Computer Science from Quaid-e-Azam University, where I have been exposed to a wide range of coursework including data structures, artificial intelligence, web development, and compiler construction. I maintain a GPA of 3.2 and actively engage in projects and Internships to enhance my skills.</p>
            <p>In addition to my academic pursuits, I have gained practical experience through internships and projects. As a Data Analyst at Wenclims, I have developed data-driven insights from complex datasets. I have also worked as a Software Developer (Internee) at Software Productivity Strategists inc (SPS), where I enhanced my programming skills and resolved critical software issues.</p>
            <p>Currently, I am furthering my knowledge and skills as an AI Trainee Intern at ExpertFlow, where I am excited to explore new challenges and contribute to innovative projects.</p>

        </div>
        
        </section>


        <!--
          - service
        -->

        <section class="service">

          <h3 class="h3 service-title">What i'm doing</h3>

          <ul class="service-list">

            <li class="service-item">

              <div class="service-icon-box">
                <img src="./assets/images/AI.png" alt="camera icon" width="40">
              </div>

              <div class="service-content-box">
                <h4 class="h4 service-item-title">Artifical ntelligence </h4>

                <p class="service-item-text">
                  I am passionate about artificial intelligence technologies, including natural language processing, computer vision, and neural networks.                </p>
              </div>

            </li>


            <li class="service-item">

              <div class="service-icon-box">
                <img src="./assets/images/machine-learning.png
                " alt="design icon" width="40">
              </div>

              <div class="service-content-box">
                <h4 class="h4 service-item-title">Machine Learning</h4>

                <p class="service-item-text">
                  I specialize in machine learning techniques for predictive modeling, data analysis, and pattern recognition.                </p>
              </div>

            </li>

            <li class="service-item">

              <div class="service-icon-box">
                <img src="./assets/images/icon-dev.svg" alt="Web development icon" width="40">
              </div>

              <div class="service-content-box">
                <h4 class="h4 service-item-title">Web development</h4>

                <p class="service-item-text">
                  High-quality development of sites at the professional level.
                </p>
              </div>

            </li>

            <li class="service-item">

              <div class="service-icon-box">
                <img src="./assets/images/icon-app.svg" alt="mobile app icon" width="40">
              </div>

              <div class="service-content-box">
                <h4 class="h4 service-item-title">Mobile apps</h4>

                <p class="service-item-text">
                  Professional development of applications for iOS and Android.
                </p>
              </div>

            </li>

            
          </ul>

        </section>


        <!--
          - testimonials
        -->

  

        <!--
          - testimonials modal
        -->

        <div class="modal-container" data-modal-container>

          <div class="overlay" data-overlay></div>

          <section class="testimonials-modal">

            <button class="modal-close-btn" data-modal-close-btn>
              <ion-icon name="close-outline"></ion-icon>
            </button>

            <div class="modal-img-wrapper">
              <figure class="modal-avatar-box">
                <img src="./assets/images/avatar-1.png" alt="Daniel lewis" width="80" data-modal-img>
              </figure>

              <img src="./assets/images/icon-quote.svg" alt="quote icon">
            </div>

            <div class="modal-content">

              <h4 class="h3 modal-title" data-modal-title>Daniel lewis</h4>

              <time datetime="2021-06-14">14 June, 2021</time>

              
            </div>

          </section>

        </div>


        <!--
          - clients
        -->

   
      </article>





      <!--
        - #RESUME
      -->

      <article class="resume" data-page="resume">

        <header>
          <h2 class="h2 article-title">Resume</h2>
        </header>

        <section class="timeline">

          <div class="title-wrapper">
            <div class="icon-box">
              <ion-icon name="book-outline"></ion-icon>
            </div>

            <h3 class="h3">Education</h3>
          </div>

          <ol class="timeline-list">

            <li class="timeline-item">
        
                <h4 class="h4 timeline-item-title">Quaid-i-Azam University</h4>
        
                <span>2020 — 2024</span>
        
                <p class="timeline-text">
                    Completed Bachelor of Science in Computer Science (BSCS). Key courses included:
                    <ul style="color: aliceblue;">
                        <li>Data Structures and Algorithms</li>
                        <li>Operating Systems</li>
                        <li>Database Systems</li>
                        <li>Artificial Intelligence</li>
                        <li>Software Engineering</li>
                        <li>Machine Learning</li>
                    </ul>
                </p>
        
            </li>
        
            <li class="timeline-item">
        
                <h4 class="h4 timeline-item-title">Lawrence College Ghora Gali, Murree</h4>
        
                <span>2017 — 2019</span>
                
                <p class="timeline-text">
                    Completed F.Sc. (Pre-Engineering). Key courses included:
                    <ul style="color: aliceblue;">
                        <li>Mathematics</li>
                        <li>Physics</li>
                        <li>Chemistry</li>
                        <li>English</li>
                    </ul>
                </p>
        
            </li>
        
            <li class="timeline-item">
        
                <h4 class="h4 timeline-item-title">Matriculation</h4>
        
                <span>2015 — 2017</span>
        
                <p class="timeline-text">
                    Completed high school with a focus on Science. Key subjects included:
                    <ul style="color: aliceblue;">
                        <li>Biology</li>
                        <li>Chemistry</li>
                        <li>Mathematics</li>
                        <li>Physics</li>
                    </ul>
                </p>
        
            </li>
        
        </ol>
        
        </section>

        <section class="timeline">

          <div class="title-wrapper">
            <div class="icon-box">
              <ion-icon name="book-outline"></ion-icon>
            </div>

            <h3 class="h3">Experience</h3>
          </div>

          <ol class="timeline-list">

            <li class="timeline-item">

              <h4 class="h4 timeline-item-title">AI Engineer</h4>

              <span>04-2024 — Present</span>

              <p class="timeline-text">
                Nemo enim ipsam voluptatem blanditiis praesentium voluptum delenit atque corrupti, quos dolores et qvuas
                molestias
                exceptur.
              </p>

            </li>

            <li class="timeline-item">

              <h4 class="h4 timeline-item-title">Data Analyst</h4>

              <span>06-2023 — Present</span>

              <p class="timeline-text">
                Nemo enims ipsam voluptatem, blanditiis praesentium voluptum delenit atque corrupti, quos dolores et
                quas molestias
                exceptur.
              </p>

            </li>

            <li class="timeline-item">

              <h4 class="h4 timeline-item-title">Software Developer (Internee)</h4>

              <span>05-2023 – 7-2023</span>

              <p class="timeline-text">
                Nemo enims ipsam voluptatem, blanditiis praesentium voluptum delenit atque corrupti, quos dolores et
                quas molestias
                exceptur.
              </p>

            </li>

          </ol>

        </section>

        <section class="skill">

          <h3 class="h3 skills-title">My skills</h3>

          <ul class="skills-list content-card">

            <li class="skills-item">

              <div class="title-wrapper">
                <h5 class="h5">Problem Solbing</h5>
                <data value="80">80%</data>
              </div>

              <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 80%;"></div>
              </div>

            </li>

            <li class="skills-item">

              <div class="title-wrapper">
                <h5 class="h5">Machine Learning</h5>
                <data value="80">80%</data>
              </div>

              <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 70%;"></div>
              </div>

            </li>

            <li class="skills-item">

              <div class="title-wrapper">
                <h5 class="h5">Django Development</h5>
                <data value="70">70%</data>
              </div>

              <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 90%;"></div>
              </div>

            </li>

            <li class="skills-item">

              <div class="title-wrapper">
                <h5 class="h5">Python Programming</h5>
                <data value="90">90%</data>
              </div>

              <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 50%;"></div>
              </div>

            </li>

            <li class="skills-item">

              <div class="title-wrapper">
                <h5 class="h5">Data Analysis</h5>
                <data value="75">75%</data>
              </div>
            
              <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 75%;"></div>
              </div>
            
            </li>

          </ul>

        </section>

      </article>





      <!--
        - #PORTFOLIO
      -->

      <article class="portfolio" data-page="portfolio">

        <header>
          <h2 class="h2 article-title">Portfolio</h2>
        </header>

        <section class="projects">



          <div class="filter-select-box">

            <button class="filter-select" data-select>

              <div class="select-value" data-selecct-value>Select category</div>

              <div class="select-icon">
                <ion-icon name="chevron-down"></ion-icon>
              </div>

            </button>

            <ul class="select-list">

              <li class="select-item">
                <button data-select-item>All</button>
              </li>

              <li class="select-item">
                <button data-select-item>Web design</button>
              </li>

              <li class="select-item">
                <button data-select-item>Applications</button>
              </li>

              <li class="select-item">
                <button data-select-item>Web development</button>
              </li>

            </ul>

          </div>

          <ul class="project-list">

            <li class="project-item  active" data-filter-item data-category="web development">
              <a href="https://github.com/Sardarmani/Protein-Function-Prediction">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/project-1.jpg" alt="finance" loading="lazy">
                </figure>

                <h3 class="project-title">Protein-Function-Prediction</h3>

                <p class="project-category">Machine Learning</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="machine-learning">
              <a href="https://github.com/Sardarmani/stock_exchange_predictor">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/project-2.png" alt="predictor" loading="lazy">
                </figure>

                <h3 class="project-title">Stock Exchange Predictor</h3>

                <p class="project-category">Machine Learning</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="web development">
              <a href="#">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/project-3.jpg" alt="fundo" loading="lazy">
                </figure>

                <h3 class="project-title">E-Commerce Website</h3>

                <p class="project-category">Web development </p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="applications">
              <a href="https://github.com/Sardarmani/parkinson-s-disease-Classification">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/project-4.png" alt="brawlhalla" loading="lazy" style="height: auto;">
                </figure>

                <h3 class="project-title">Parkinson's disease classification</h3>

                <p class="project-category">Machine Learning</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="web design">
              <a href="https://github.com/Sardarmani/Audio-Classificaion-Using-Deep-Learning">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/project-5.png" alt="dsm." loading="lazy">
                </figure>

                <h3 class="project-title">Audio-Classificaion-Using-Deep-Learning </h3>

                <p class="project-category">Machine Learning</p>

              </a>
            </li>



            <li class="project-item  active" data-filter-item data-category="web development">
              <a href="https://github.com/Sardarmani/department">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/project-6.png" alt="summary" loading="lazy">
                </figure>

                <h3 class="project-title">Departmental Website</h3>

                <p class="project-category">Web development</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="applications">
              <a href="https://github.com/Sardarmani/Library-Managment-System">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/project-7.png" alt="Library-Managment-System" loading="lazy">
                </figure>

                <h3 class="project-title">Library Managment System</h3>

                <p class="project-category">Console based Applications</p>

              </a>
            </li>

            
              <a href="#">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/project-8.jpg" alt="movie classification" loading="lazy">
                </figure>

                <h3 class="project-title">Movie Rating Classification Using KNN (K- Nearest Neighbors)</h3>

                <p class="project-category">Machine Learning</p>

              </a>
            </li>

          </ul>

        </section>

      </article>





      <!--
        - #BLOG
      -->



      <article class="blog" data-page="blog">

        <header>
          <h2 class="h2 article-title">Blog</h2>
        </header>
      
        <section class="blog-posts">
      
          <ul class="blog-posts-list">
      
            <li class="blog-post-item">
              <blockquote class="wp-embedded-content" data-secret="YxcD878wqp"><a href="https://muneebtariqcom.wordpress.com/2024/02/12/protein-prediction/">Title: Unveiling Protein Secrets: Revolutionizing Bioinformatics with Machine&nbsp;Learning</a></blockquote>
              <iframe sandbox="allow-scripts" security="restricted" src="https://muneebtariqcom.wordpress.com/2024/02/12/protein-prediction/embed/#?secret=YxcD878wqp" width="100%" height="100%" title="&#8220;Title: Unveiling Protein Secrets: Revolutionizing Bioinformatics with Machine&nbsp;Learning&#8221; &#8212; Mani&#039;s Blogs" data-secret="YxcD878wqp" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" class="wp-embedded-content"></iframe>
            </li>
      

            <li class="blog-post-item">
              <blockquote class="wp-embedded-content" data-secret="EYnVOZy8gz"><a href="https://muneebtariqcom.wordpress.com/2024/01/10/forecasting-stock-prices-of-abbott-laboratoriespsx-company-using-prophet/">Forecasting Stock Prices of Abbott Laboratories(PSX Company) Using&nbsp;Prophet</a></blockquote>
              <iframe sandbox="allow-scripts" security="restricted" src="https://muneebtariqcom.wordpress.com/2024/01/10/forecasting-stock-prices-of-abbott-laboratoriespsx-company-using-prophet/embed/#?secret=EYnVOZy8gz" width="100%" height="100%" title="&#8220;Forecasting Stock Prices of Abbott Laboratories(PSX Company) Using&nbsp;Prophet&#8221; &#8212; Mani&#039;s Blogs" data-secret="EYnVOZy8gz" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" class="wp-embedded-content"></iframe><script>
                /*! This file is auto-generated */
                !function(d,l){"use strict";l.querySelector&&d.addEventListener&&"undefined"!=typeof URL&&(d.wp=d.wp||{},d.wp.receiveEmbedMessage||(d.wp.receiveEmbedMessage=function(e){var t=e.data;if((t||t.secret||t.message||t.value)&&!/[^a-zA-Z0-9]/.test(t.secret)){for(var s,r,n,a=l.querySelectorAll('iframe[data-secret="'+t.secret+'"]'),o=l.querySelectorAll('blockquote[data-secret="'+t.secret+'"]'),c=new RegExp("^https?:$","i"),i=0;i<o.length;i++)o[i].style.display="none";for(i=0;i<a.length;i++)s=a[i],e.source===s.contentWindow&&(s.removeAttribute("style"),"height"===t.message?(1e3<(r=parseInt(t.value,10))?r=1e3:~~r<200&&(r=200),s.height=r):"link"===t.message&&(r=new URL(s.getAttribute("src")),n=new URL(t.value),c.test(n.protocol))&&n.host===r.host&&l.activeElement===s&&(d.top.location.href=t.value))}},d.addEventListener("message",d.wp.receiveEmbedMessage,!1),l.addEventListener("DOMContentLoaded",function(){for(var e,t,s=l.querySelectorAll("iframe.wp-embedded-content"),r=0;r<s.length;r++)(t=(e=s[r]).getAttribute("data-secret"))||(t=Math.random().toString(36).substring(2,12),e.src+="#?secret="+t,e.setAttribute("data-secret",t)),e.contentWindow.postMessage({message:"ready",secret:t},"*")},!1)))}(window,document);
                </script>
                
                 </li>
      

                 <li class="blog-post-item">
                  <blockquote class="wp-embedded-content" data-secret="wNStapnujP"><a href="https://muneebtariqcom.wordpress.com/2023/09/10/detrend/">Demystifying Detrending: Uncovering Insights in Time Series&nbsp;Data</a></blockquote><iframe sandbox="allow-scripts" security="restricted" src="https://muneebtariqcom.wordpress.com/2023/09/10/detrend/embed/#?secret=wNStapnujP" width="100%" height="100%" title="&#8220;Demystifying Detrending: Uncovering Insights in Time Series&nbsp;Data&#8221; &#8212; Mani&#039;s Blogs" data-secret="wNStapnujP" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" class="wp-embedded-content"></iframe><script>
                    /*! This file is auto-generated */
                    !function(d,l){"use strict";l.querySelector&&d.addEventListener&&"undefined"!=typeof URL&&(d.wp=d.wp||{},d.wp.receiveEmbedMessage||(d.wp.receiveEmbedMessage=function(e){var t=e.data;if((t||t.secret||t.message||t.value)&&!/[^a-zA-Z0-9]/.test(t.secret)){for(var s,r,n,a=l.querySelectorAll('iframe[data-secret="'+t.secret+'"]'),o=l.querySelectorAll('blockquote[data-secret="'+t.secret+'"]'),c=new RegExp("^https?:$","i"),i=0;i<o.length;i++)o[i].style.display="none";for(i=0;i<a.length;i++)s=a[i],e.source===s.contentWindow&&(s.removeAttribute("style"),"height"===t.message?(1e3<(r=parseInt(t.value,10))?r=1e3:~~r<200&&(r=200),s.height=r):"link"===t.message&&(r=new URL(s.getAttribute("src")),n=new URL(t.value),c.test(n.protocol))&&n.host===r.host&&l.activeElement===s&&(d.top.location.href=t.value))}},d.addEventListener("message",d.wp.receiveEmbedMessage,!1),l.addEventListener("DOMContentLoaded",function(){for(var e,t,s=l.querySelectorAll("iframe.wp-embedded-content"),r=0;r<s.length;r++)(t=(e=s[r]).getAttribute("data-secret"))||(t=Math.random().toString(36).substring(2,12),e.src+="#?secret="+t,e.setAttribute("data-secret",t)),e.contentWindow.postMessage({message:"ready",secret:t},"*")},!1)))}(window,document);
                    </script>
                      
                     </li>


                     <li class="blog-post-item">
                      <blockquote class="wp-embedded-content" data-secret="shkrmzPBQW"><a href="https://muneebtariqcom.wordpress.com/2023/03/13/ssh-command/">SSH Command</a></blockquote><iframe sandbox="allow-scripts" security="restricted" src="https://muneebtariqcom.wordpress.com/2023/03/13/ssh-command/embed/#?secret=shkrmzPBQW" width="100%" height="100%" title="&#8220;SSH Command&#8221; &#8212; Mani&#039;s Blogs" data-secret="shkrmzPBQW" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" class="wp-embedded-content"></iframe><script>
                        /*! This file is auto-generated */
                        !function(d,l){"use strict";l.querySelector&&d.addEventListener&&"undefined"!=typeof URL&&(d.wp=d.wp||{},d.wp.receiveEmbedMessage||(d.wp.receiveEmbedMessage=function(e){var t=e.data;if((t||t.secret||t.message||t.value)&&!/[^a-zA-Z0-9]/.test(t.secret)){for(var s,r,n,a=l.querySelectorAll('iframe[data-secret="'+t.secret+'"]'),o=l.querySelectorAll('blockquote[data-secret="'+t.secret+'"]'),c=new RegExp("^https?:$","i"),i=0;i<o.length;i++)o[i].style.display="none";for(i=0;i<a.length;i++)s=a[i],e.source===s.contentWindow&&(s.removeAttribute("style"),"height"===t.message?(1e3<(r=parseInt(t.value,10))?r=1e3:~~r<200&&(r=200),s.height=r):"link"===t.message&&(r=new URL(s.getAttribute("src")),n=new URL(t.value),c.test(n.protocol))&&n.host===r.host&&l.activeElement===s&&(d.top.location.href=t.value))}},d.addEventListener("message",d.wp.receiveEmbedMessage,!1),l.addEventListener("DOMContentLoaded",function(){for(var e,t,s=l.querySelectorAll("iframe.wp-embedded-content"),r=0;r<s.length;r++)(t=(e=s[r]).getAttribute("data-secret"))||(t=Math.random().toString(36).substring(2,12),e.src+="#?secret="+t,e.setAttribute("data-secret",t)),e.contentWindow.postMessage({message:"ready",secret:t},"*")},!1)))}(window,document);
                        </script>
                            
                         </li>

                         <li class="blog-post-item">
                          <blockquote class="wp-embedded-content" data-secret="ssP10FnJHA"><a href="https://muneebtariqcom.wordpress.com/2023/08/13/unveiling-the-power-of-web-scraping-your-gateway-to-data-exploration/">Unveiling the Power of Web Scraping: Your Gateway to Data&nbsp;Exploration</a></blockquote><iframe sandbox="allow-scripts" security="restricted" src="https://muneebtariqcom.wordpress.com/2023/08/13/unveiling-the-power-of-web-scraping-your-gateway-to-data-exploration/embed/#?secret=ssP10FnJHA" width="100%" height="100%" title="&#8220;Unveiling the Power of Web Scraping: Your Gateway to Data&nbsp;Exploration&#8221; &#8212; Mani&#039;s Blogs" data-secret="ssP10FnJHA" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" class="wp-embedded-content"></iframe><script>
                            /*! This file is auto-generated */
                            !function(d,l){"use strict";l.querySelector&&d.addEventListener&&"undefined"!=typeof URL&&(d.wp=d.wp||{},d.wp.receiveEmbedMessage||(d.wp.receiveEmbedMessage=function(e){var t=e.data;if((t||t.secret||t.message||t.value)&&!/[^a-zA-Z0-9]/.test(t.secret)){for(var s,r,n,a=l.querySelectorAll('iframe[data-secret="'+t.secret+'"]'),o=l.querySelectorAll('blockquote[data-secret="'+t.secret+'"]'),c=new RegExp("^https?:$","i"),i=0;i<o.length;i++)o[i].style.display="none";for(i=0;i<a.length;i++)s=a[i],e.source===s.contentWindow&&(s.removeAttribute("style"),"height"===t.message?(1e3<(r=parseInt(t.value,10))?r=1e3:~~r<200&&(r=200),s.height=r):"link"===t.message&&(r=new URL(s.getAttribute("src")),n=new URL(t.value),c.test(n.protocol))&&n.host===r.host&&l.activeElement===s&&(d.top.location.href=t.value))}},d.addEventListener("message",d.wp.receiveEmbedMessage,!1),l.addEventListener("DOMContentLoaded",function(){for(var e,t,s=l.querySelectorAll("iframe.wp-embedded-content"),r=0;r<s.length;r++)(t=(e=s[r]).getAttribute("data-secret"))||(t=Math.random().toString(36).substring(2,12),e.src+="#?secret="+t,e.setAttribute("data-secret",t)),e.contentWindow.postMessage({message:"ready",secret:t},"*")},!1)))}(window,document);
                            </script>
                                                          
                             </li>

                             <li class="blog-post-item">
                              <blockquote class="wp-embedded-content" data-secret="4tjYgQw3yr"><a href="https://muneebtariqcom.wordpress.com/2023/08/24/apis-vs-websockets/">APIs vs WebSockets: Choosing the Right Communication Approach for Your Web&nbsp;Development</a></blockquote><iframe sandbox="allow-scripts" security="restricted" src="https://muneebtariqcom.wordpress.com/2023/08/24/apis-vs-websockets/embed/#?secret=4tjYgQw3yr" width="100%" height="400" title="&#8220;APIs vs WebSockets: Choosing the Right Communication Approach for Your Web&nbsp;Development&#8221; &#8212; Mani&#039;s Blogs" data-secret="4tjYgQw3yr" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" class="wp-embedded-content"></iframe><script>
                                /*! This file is auto-generated */
                                !function(d,l){"use strict";l.querySelector&&d.addEventListener&&"undefined"!=typeof URL&&(d.wp=d.wp||{},d.wp.receiveEmbedMessage||(d.wp.receiveEmbedMessage=function(e){var t=e.data;if((t||t.secret||t.message||t.value)&&!/[^a-zA-Z0-9]/.test(t.secret)){for(var s,r,n,a=l.querySelectorAll('iframe[data-secret="'+t.secret+'"]'),o=l.querySelectorAll('blockquote[data-secret="'+t.secret+'"]'),c=new RegExp("^https?:$","i"),i=0;i<o.length;i++)o[i].style.display="none";for(i=0;i<a.length;i++)s=a[i],e.source===s.contentWindow&&(s.removeAttribute("style"),"height"===t.message?(1e3<(r=parseInt(t.value,10))?r=1e3:~~r<200&&(r=200),s.height=r):"link"===t.message&&(r=new URL(s.getAttribute("src")),n=new URL(t.value),c.test(n.protocol))&&n.host===r.host&&l.activeElement===s&&(d.top.location.href=t.value))}},d.addEventListener("message",d.wp.receiveEmbedMessage,!1),l.addEventListener("DOMContentLoaded",function(){for(var e,t,s=l.querySelectorAll("iframe.wp-embedded-content"),r=0;r<s.length;r++)(t=(e=s[r]).getAttribute("data-secret"))||(t=Math.random().toString(36).substring(2,12),e.src+="#?secret="+t,e.setAttribute("data-secret",t)),e.contentWindow.postMessage({message:"ready",secret:t},"*")},!1)))}(window,document);
                                </script>
                                                    </li>
            
            
          </ul>
      
        </section>
      
      </article>
          




      <!--
        - #CONTACT
      -->

      <article class="contact" data-page="contact">

        <header>
          <h2 class="h2 article-title">Contact</h2>
        </header>

        <section class="mapbox" data-mapbox>
          <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3317.503682958577!2d73.1355460750412!3d33.7476479732732!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x38dfc11d3571e5bf%3A0x841a9ed6d869644f!2sQuaid%20e%20Azam%20University%20Islamabad!5e0!3m2!1sen!2s!4v1716018002923!5m2!1sen!2s" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
          </figure>
        </section>

        <section class="contact-form">

          <h3 class="h3 form-title">Contact Form</h3>

            <form action="mailto:muhammadmuneebtariq09@gmail.com" method="post" enctype="text/plain" class="form" data-form>
            <div class="input-wrapper">
              <input type="text" name="fullname" class="form-input" placeholder="Full name" required data-form-input>

              <input type="email" name="email" class="form-input" placeholder="Email address" required data-form-input>
            </div>

            <textarea name="message" class="form-input" placeholder="Your Message" required data-form-input></textarea>

            <button class="form-btn" type="submit" disabled data-form-btn>
              <ion-icon name="paper-plane"></ion-icon>
              <span>Send Message</span>
            </button>

          </form>

        </section>

      </article>

    </div>

  </main>






  <!--
    - custom js link
  -->
  <script src="./assets/js/script.js"></script>

  <!--
    - ionicon link
  -->
  <script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
  <script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>


  
</body>

</html>
