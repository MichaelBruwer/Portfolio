<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Michael Bruwer</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://kit.fontawesome.com/a076d05399.js"></script>
    <script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/typed.js/2.0.11/typed.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/waypoints/4.0.1/jquery.waypoints.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/owl.carousel.min.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/assets/owl.carousel.min.css"/>

</head>
<body>
    <div class="scroll-up-btn">
        <i class="fas fa-angle-up"></i>
    </div>
    <nav class="navbar">
        <div class="max-width">   
            <div>
                <ul class="menu">
                    <li><a href='https://github.com/MichaelBruwer' ><i class="fab fa-github fa-lg"></i></a></li>
                    <li><a href='https://www.linkedin.com/in/michael-bruwer-2806a41a9/'><i class="fab fa-linkedin fa-lg"></i></a></li>
                </ul>
            </div>         
            <ul class="menu">
                <li><a href="#home" class="menu-btn">Home</a></li>
                <li><a href="#about" class="menu-btn">About</a></li>                
                <li><a href="#skills" class="menu-btn">Skills</a></li>   
                <li><a href="#work" class="menu-btn">Work</a></li>              
                <li><a href="#contact" class="menu-btn">Contact</a></li>
            </ul>
            <div class="menu-btn">
                <i class="fas fa-bars"></i>
            </div>
        </div>
    </nav>

    <!-- home section start -->
    <section class="home" id="home">
        <div class="max-width">
            <div class="home-content">
                <div class="text-1">Hello, my name is</div>
                <div class="text-2">Michael Bruwer</div>
                <div class="text-3">And I'm a <span class="typing"></span></div>
                <div>  </div>
            </div>
        </div>
    </section>

    <!-- about section start -->
    <section class="about" id="about">
        <div class="max-width">
            <h2 class="title">About me</h2>
            <div class="about-content">
                <div class="column left">
                    <img src="images/picture.jpg" alt="">
                </div>
                <div class="column right">
                    <div class="text">I'm Michael and I'm a <span class="typing-2"></span></div>
                    <p class='spacefix'>
                        I am an aspiring Developer with a passion for gaming.
                        i am a trustworthy, respectful, organized, adaptable and truthful person
                        who is looking to pursue a long-term career in IT and meet some
                        new and interesting people along the way. I have been around computers
                        most of my life mainly dealing with hardware but also occasionally
                        loading software for people aswell as having some family that are Developers.
                        This close contact has fuelled the passion for coding.</p>
                    <a href="Portfolio01/images/Michael Bruwer Resume.pdf">Download CV</a>
                </div>
            </div>
        </div>
    </section>

    <!-- skills section start -->
    <section class="skills" id="skills">
        <div class="max-width">
            <h2 class="title">My skills</h2>
            <div class="skills-content">
                <div class="column left">
                    <div class="text">My skills & experiences.</div>
                    <p>i'm an Intern Developer at LC-Studio,
                         and i work with Web based applications normally
                          with React Js as a front end and a python backend
                           sometimes using the Django framework</p>

                </div>
                <div class="column right">
                    <div class="bars">
                        <div class="info">
                            <span>HTML</span>
                            <span>90%</span>
                        </div>
                        <div class="line html"></div>
                    </div>
                    <div class="bars">
                        <div class="info">
                            <span>CSS</span>
                            <span>60%</span>
                        </div>
                        <div class="line css"></div>
                    </div>
                    <div class="bars">
                        <div class="info">
                            <span>ReactJs</span>
                            <span>80%</span>
                        </div>
                        <div class="line js"></div>
                    </div>
                    <div class="bars">
                        <div class="info">
                            <span>Python</span>
                            <span>50%</span>
                        </div>
                        <div class="line python"></div>
                    </div>
                    <div class="bars">
                        <div class="info">
                            <span>Mysql</span>
                            <span>20%</span>
                        </div>
                        <div class="line mysql"></div>
                    </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- work section start -->
    <section class="work" id="work">
        <div class="max-width">
            <h2 class="title">My work</h2>
            <div class="carousel owl-carousel">
                <div class="card">
                     <div class="box">
                      <a href='https://nostalgic-hypatia-799ca7.netlify.app/' >
                          <img src="images/tes-clone.JPG" alt="Tesla-clone">
                        </a>
                        <div class="text">Tesla-clone</div>
                        <p>A Tesla Home-page clone done with reactJs</p>
                    </div>
                </div>
                <div class="card">
                    <div class="box">
                    <a href='https://weatherwidgetmicb.netlify.app/' >
                         <img src="images/weather.JPG" alt="WeatherWidget">
                         </a>
                        <div class="text">Weather Widget</div>
                        <p>A Widget that displays the weather details.</p>
                    </div>

                </div>
                <div class="card">
                    <div class="box">
                     <a href='https://relaxed-poincare-f10de0.netlify.app/' >
                         <img src="images/gitfinder.JPG" alt="gitfinder">
                        </a>
                        <div class="text">Github Finder</div>
                        <p> A Github account Finder Built useing ReactJs.</p>
                    </div>
                </div>
                <!-- <div class="card">
                    <a href='/#' >
                    <div class="box">
                        <img src="images/" alt="">
                        <div class="text">Project Name</div>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                </a>
                </div>
                <div class="card">
                    <a href='/#' >
                    <div class="box">
                        <img src="images/" alt="">
                        <div class="text">Project Name</div>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                </a>
                </div>
            </div> -->
        </div>
    </section>

    <!-- contact section start -->
    <section class="contact" id="contact">
        <div class="max-width">
            <h2 class="title">Contact me</h2>
            <div class="contact-content">
                <div class="column left">

                   <div class="icons">
                        <div class="row">
                            <i class="fas fa-user"></i>
                            <div class="info">
                                <div class="head">Name</div>
                                <div class="sub-title">Michael Bruwer</div>
                            </div>
                        </div>
                        <div class="row">
                            <i class="fas fa-map-marker-alt"></i>
                            <div class="info">
                                <div class="head">Address</div>
                                <div class="sub-title">Cape Town, South Africa</div>
                            </div>
                        </div>
                        <div class="row">
                            <i class="fas fa-envelope"></i>
                            <div class="info">
                                <div class="head">Email</div>
                                <div class="sub-title">michaelbruwer21@gmail.com</div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="column right">
                    <div class="text">Message me</div>
                    <form action="mailto:michaelbruwer21@gmail.com" method="post" enctype="text/plain">
                        <div class="fields">
                            <div class="field name">
                                <input type="text" name="name" placeholder="Name" required>
                            </div>
                            <div class="field email">
                                <input type="email" name="email" placeholder="Email" required>
                            </div>
                        </div>
                        <div class="field">
                            <input type="text" name="subject" placeholder="Subject" required>
                        </div>
                        <div class="field textarea">
                            <textarea cols="30" rows="10" name="message" placeholder="Message.." required></textarea>
                        </div>
                        <div class="button">
                            <button type="submit">Send message</button>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <script src="script.js"></script>

</body>
</html>
