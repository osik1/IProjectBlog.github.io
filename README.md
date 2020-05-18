<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <meta http-equiv="X-UA-Compatible" content="ie-edge">
        <link href="https://fonts.googleapis.com/css?family=Montserrat|Open+Sans+Condensed:300|Oswald|Roboto&display=swap" rel="stylesheet">
        <link href="https://fonts.googleapis.com/css?family=Open+Sans:400,600,700" rel="stylesheet">
        <!--font awesome-->
        <script src="https://kit.fontawesome.com/bd832a5ee6.js" crossorigin="anonymous"></script>
        <!--custom styling-->
         <link rel="stylesheet" href="css/style.css">
         <!--google fonts-->
         <link href="https://fonts.googleapis.com/css?family=Candal&display=swap" rel="stylesheet">

        <title>Blog</title>
    </head>
    <body>

        <!-- Load Facebook SDK for JavaScript -->
      <div id="fb-root"></div>
      <script>
        window.fbAsyncInit = function() {
          FB.init({
            xfbml            : true,
            version          : 'v5.0'
          });
        };

        (function(d, s, id) {
        var js, fjs = d.getElementsByTagName(s)[0];
        if (d.getElementById(id)) return;
        js = d.createElement(s); js.id = id;
        js.src = 'https://connect.facebook.net/en_US/sdk/xfbml.customerchat.js';
        fjs.parentNode.insertBefore(js, fjs);
      }(document, 'script', 'facebook-jssdk'));</script>

      <!-- Your customer chat code -->
      <div class="fb-customerchat"
        attribution=setup_tool
        page_id="106511667508499"
        theme_color="#f3e3b2"
        logged_in_greeting="Feel free to ask us anything"
        logged_out_greeting="Feel free to ask us anything">
      </div>
        <header>
            <div class="logo">
                <img src="images/iprojectbloglogo.png" alt="" class="header-logo">
            </div>
            <i class="fa fa-bars menu-toggle" ></i>
            <Ul class="nav">
                <li><a href="">Home</a></li>
                <li>
                    <a href="">More <i class="fa fa-chevron-down" style="font-size: .8em;"></i></a>                                <!--creating a dropdown Menu-->
            
                    
                    <ul>
                        <li><a href="">Tips and tricks</a></li>
                        <li><a href="">News</a></li>
                        <li><a href="">How to</a></li>
                        <li><a href="">Web Development</a></li>
                        <li><a href="">Design</a></li>
                        <li><a href="">Security</a></li>
                        <li><a href="">Programming</a></li>
                    </ul>
                    </li>                <!--<li><a href="">Sign Up</a></li>
                <li><a href="">Login</a></li>-->
                <li>
                    <a href="">
                        <i class="fa fa-user"></i>
                        Osik
                        <i class="fa fa-chevron-down" style="font-size: .8em;"></i>                    <!--creating a dropdown Menu-->
                   </a> 
                    <ul>
                    <li><a href="admin/posts/index.html">Dashboard</a></li>
                    <li><a href="" class="logout">Logout</a></li>   
                    </ul>
                </li>
            </Ul>
        </header>
        <!--Page Wrapper-->
        <div class="page-wrapper">
            <!--Post Slider-->
            <div class="post-slider">
                <!--<h1 class="slider-title">Trending Posts</h1>-->
                <i class="fas fa-chevron-left prev"></i>     
                <i class="fas fa-chevron-right next"></i>

                <div class="post-wrapper">

                    <div class="post">
                        <img src="images/whatsapp.png" alt="" class="slider-image">
                        <div class="post-info">
                            <h3><a href="single.html">Tips and tricks of the most used mobile Application in Ghana.</a></h3>
                            <i class="far fa-user"> Osik Newton</i>
                            &nbsp;
                            <i class="fa fa-calendar" aria-hidden="true"> Dec. 1, 2019</i>
                        </div>
                    </div>
                   
                    <div class="post">
                            <img src="images/Web.jpg" alt="" class="slider-image">
                            <div class="post-info">
                                <h3><a href="single.html">Two ways to host your website for free without paying for any fee.</a></h3>
                                <i class="far fa-user"> Osik Newton</i>
                                &nbsp;
                                <i class="fa fa-calendar" aria-hidden="true"> Dec. 3, 2019</i>

                            </div>
                    </div>
                    <div class="post">
                            <img src="images/twitter.png" alt="" class="slider-image">
                            <div class="post-info">
                                <h3><a href="single.html">Do this to get more followers on twitter, the most interactive App.</a></h3>
                                <i class="far fa-user"> Osik Newton</i>
                                &nbsp;
                                <i class="fa fa-calendar" aria-hidden="true"> Dec. 5, 2019</i>
                            </div>
                    </div>
                    <div class="post">
                            <img src="images/windows.jpg" alt="" class="slider-image">
                            <div class="post-info">
                                <h3><a href="single.html">Know your Windows OS general troubleshooting tips now.</a></h3>
                                <i class="far fa-user"> Osik Newton</i>
                                &nbsp;
                                <i class="fa fa-calendar" aria-hidden="true"> Dec. 1, 2019</i>
                            </div>
                        </div>
                        <div class="post">
                                <img src="images/whatsapp.png" alt="" class="slider-image">
                                <div class="post-info">
                                    <h3><a href="single.html">Tips and tricks of the most used mobile Application in Ghana.</a></h3>
                                    <i class="far fa-user"> Osik Newton</i>
                                    &nbsp;
                                    <i class="fa fa-calendar" aria-hidden="true"> Dec. 1, 2019</i>
                                </div>
                            </div>
                            <div class="post">
                                    <img src="images/whatsapp.png" alt="" class="slider-image">
                                    <div class="post-info">
                                        <h3><a href="single.html">Tips and tricks of the most used mobile Application in Ghana.</a></h3>
                                        <i class="far fa-user"> Osik Newton</i>
                                        &nbsp;
                                        <i class="fa fa-calendar" aria-hidden="true"> Dec. 1, 2019</i>
                                    </div>
                                </div>
                                <div class="post">
                                        <img src="images/whatsapp.png" alt="" class="slider-image">
                                        <div class="post-info">
                                            <h3><a href="single.html">Tips and tricks of the most used mobile Application in Ghana.</a></h3>
                                            <i class="far fa-user"> Osik Newton</i>
                                            &nbsp;
                                            <i class="fa fa-calendar" aria-hidden="true"> Dec. 1, 2019</i>
                                        </div>
                                 </div>
                </div>
            </div>
            <!--//Post Slider-->
          

            <!--content-->
           
            <div class="content clearfix">
                <!--MAIN CONTENT-->
                <div class="main-content">
                    <h1 class="recent-post-title">Recent Post</h1>
                    <div class="post clearfix">
                        <img src="images/dnb.jpg" alt="" class="post-image">
                        <div class="post-preview">
                            <h2><a href="single.html">The DNB mobile App is out now, Know how to use it as a student. </a></h2>
                            <i class="far fa-user"> Osik Newton</i>
                            &nbsp;
                            <i class="fa fa-calendar"> Dec. 1 2019</i>
                            <p class="preview-text">
                                    DNB Application is an interactive smart phone and tablet Application for providing organisations with 
                                    real time information that is accurate, Structured and updated.  
                            </p>
                            <a href="single.html" class="btn read-more">Read More</a>
                        </div>
                    </div>

                    <div class="post clearfix">
                            <img src="images/windows.jpg" alt="" class="post-image">
                            <div class="post-preview">
                                <h2><a href="single.html">Know Windows general troubleshooting tips </a></h2>
                                <i class="far fa-user"> Osik Newton</i>
                                &nbsp;
                                <i class="fa fa-calendar"> Dec. 1 2019</i>
                                <p class="preview-text">
                                       There are basic troubleshooting steps you will want to take almost every time you face a device problem
                                       ,especially in Windows.  
                                </p>
                                <a href="single.html" class="btn read-more">Read More</a>
                            </div>
                        </div>

                        <div class="post clearfix">
                                <img src="images/dnb.jpg" alt="" class="post-image">
                                <div class="post-preview">
                                    <h2><a href="single.html">The DNB mobile App is out now, Know how to use it as a student. </a></h2>
                                    <i class="far fa-user"> Osik Newton</i>
                                    &nbsp;
                                    <i class="fa fa-calendar"> Dec. 1 2019</i>
                                    <p class="preview-text">
                                            DNB Application is an interactive smart phone and tablet Application for providing organisations with 
                                            real time information that is accurate, Structured and updated.  
                                    </p>
                                    <a href="single.html" class="btn read-more">Read More</a>
                                </div>
                            </div>

                            <div class="post clearfix">
                                    <img src="images/dnb.jpg" alt="" class="post-image">
                                    <div class="post-preview">
                                        <h2><a href="single.html">The DNB mobile App is out now, Know how to use it as a student. </a></h2>
                                        <i class="far fa-user"> Osik Newton</i>
                                        &nbsp;
                                        <i class="fa fa-calendar"> Dec. 1 2019</i>
                                        <p class="preview-text">
                                                DNB Application is an interactive smart phone and tablet Application for providing organisations with 
                                                real time information that is accurate, Structured and updated. With initial focus on University of 
                                                Ghana students, it provides real time and useful academic information on the go. 
                                        </p>
                                        <a href="single.html" class="btn read-more">Read More</a>
                                    </div>
                                </div>

                                <div class="post clearfix">
                                        <img src="images/dnb.jpg" alt="" class="post-image">
                                        <div class="post-preview">
                                            <h2><a href="single.html">The DNB mobile App. Know how to use it now as a student. </a></h2>
                                            <i class="far fa-user"> Osik Newton</i>
                                            &nbsp;
                                            <i class="fa fa-calendar"> Dec. 1 2019</i>
                                            <p class="preview-text">
                                                    DNB Application is an interactive smart phone and tablet Application for providing organisations with 
                                                    real time information that is accurate, Structured and updated. With initial focus on University of 
                                                    Ghana students, it provides real time and useful academic information on the go. 
                                            </p>
                                            <a href="single.html" class="btn read-more">Read More</a>
                                        </div>
                                    </div>

                                    <div class="pagination flex-row">
                                        <a href=""><i class="fas fa-chevron-left"></i></a> 
                                        <a href="" class="pages">1</a>
                                        <a href="" class="pages">2</a>
                                        <a href="" class="pages">3</a>
                                        <a href=""><i class="fas fa-chevron-right"></i></a> 
                                        </div>

                                    

                                    

                                    
                </div>

               

                
                <!--//MAIN CONTENT-->
                <div class="sidebar">
                      <!--facebook page plugin-->
                   
                      <!--//facebook page plugin-->

                    <div class="search section">
                        <h2 class="section-title">Search</h2>
                        <form action="index.html" method="post">
                            <input type="text" name="search-term" class="text-input" placeholder="Search...">
                        </form>
                    </div>

                    <div class="section popular">
                        <h2 class="section-title">Popular Post</h2>
                        <div class="post clearfix">
                            <img src="images/web.jpg" alt="">
                            <a href="" class="title">Two ways to host your website for free without paying for any fee</a>
                        </div>

                        <div class="post clearfix">
                            <img src="images/web.jpg" alt="">
                            <a href="" class="title">Two ways to host your website for free without paying for any fee</a>
                        </div>

                        <div class="post clearfix">
                            <img src="images/web.jpg" alt="">
                            <a href="" class="title">Two ways to host your website for free without paying for any fee</a>
                        </div>

                        <div class="post clearfix">
                            <img src="images/web.jpg" alt="">
                            <a href="" class="title">Two ways to host your website for free without paying for any fee</a>
                        </div>

                        <div class="post clearfix">
                            <img src="images/web.jpg" alt="">
                            <a href="" class="title">Two ways to host your website for free without paying for any fee</a>
                        </div>
    
    
                    </div>

                    <div class="section topics">
                        <h2 class="section-title">Categories</h2>
                             <ul>
                                <li><a href="">Tips and tricks</a></li>
                                <li><a href="">News</a></li>
                                <li><a href="">How to</a></li>
                                <li><a href="">Web Development</a></li>
                                <li><a href="">Design</a></li>
                                <li><a href="">Security</a></li>
                                <li><a href="">Programming</a></li>
                            </ul>
                    </div>
                </div>


             </div>



            <!--//content-->


        </div>
        <!--Page Wrapper-->
        <div class="footer">
            <div class="footer-content">
                <div class="footer-section about">
                    <h1 class="logo-text"><span>IProject</span> Blog</h1>
                    <p>
                        We are a Free-end-tech blog providing you practical guide on IT major platforms.
                         Follow for updates! Launched in 2020 as a community for creative engineers, system administrators, designers , 
                         and computer programmers, where everyone can write and share tried and tested guided solutions to solve problems.
                         this site is a quickly growing collective of go-getters from all around the world. 
                    </p>
                    <br>
                    <div class="contact">
                        <span><i class="fas fa-phone"></i>&nbsp; +2330555253975</span>
                        <span><i class="fas fa-envelope"></i>&nbsp; iprojectblog@gmail.com</span>
                    </div>
                    <div class="socials">
                        <a href=""><i class="fab fa-facebook"></i></a>
                        <a href=""><i class="fab fa-twitter"></i></a>
                        <a href=""><i class="fab fa-instagram"></i></a>
                        <a href=""><i class="fab fa-youtube"></i></a>

                    </div>
                </div>
                <div class="footer-section links">
                    <h2>Quick links</h2>
                <br>
                <ul>
                    <a href=""><li>Terms and Conditions</li></a>
                    <a href=""><li>Privacy</li></a>
                    <a href=""><li>Writters</li></a>
                    <a href=""><li>Write for us</li></a>
                    <a href=""><li>Mentors</li></a>
                    <a href=""><li>Advertise with us</li></a>
                    <a href=""><li>Events</li></a>

                </ul>
                </div>
                <div class="footer-section contact-form">
                    <h2>Contact Us</h2>
                    <br>
                    <form action="index.html" method="post">
                        <input type="email" name="email" class="text-input contact-input" placeholder="Your  email address...">
                        <textarea rows="4" name="message"class="text-input contact-input" placeholder="Your message....."></textarea>
                        <button type='submit' class="btn btn-big"><i class="fa fa-envelope"></i> Send</button>
                    </form>
                </div>

            </div>
            <div class="footer-bottom">
                &copy; 2020-IPROJECTBLOG.COM  
            </div>
            <a id="back2Top" title="Back to top" href="#">&#10148;</a>
        </div>
        <!--Footer-->
        


        <!--//Footer-->

     <!--JQuery-->
     <script src="jquery-3.4.1.min.js"></script>

     <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.4.1/jquery.min.js" integrity="sha256-CSXorXvZcTkaix6Yvo6HppcZGetbYMGWSFlBw8HfCJo=" crossorigin="anonymous"></script>
       
     <!--Slick carousel-->
     <script type="text/javascript" src="https://cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick.min.js"></script>

      <!--facebook cdn-->
      <div id="fb-root"></div>
      <script async defer crossorigin="anonymous" src="https://connect.facebook.net/en_US/sdk.js#xfbml=1&version=v5.0"></script>

     <!--Custom Click for menu bar-->
     <script src="JS/scripts.js"></script>
    </body>
</html>
