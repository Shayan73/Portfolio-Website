<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://kit.fontawesome.com/3e6cd7bd37.js" crossorigin="anonymous"></script>
</head>

<body>

    <div id="header">
        <div class="container">
            <nav>
                <img src="./images/logo.png" class="logo">
                <ul id="sidemenu">
                    <li><a href="#header">Home</a> </li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#portfolio">Portfolio</a></li>
                    <li><a href="#contact">Contact</a></li>
                    <i class="fas fa-times" onclick="closemenu()"></i>
                </ul>
                <i class="fas fa-bars" onclick="openmenu()"></i>
            </nav>
            <div class="header-text">
                <p>Website Developer</p>
                <h1>Hi I am <span>Abdul Hafeez</span> <br>from Pakistan</h1>
            </div>
        </div>
    </div>
    <!-- about -->
    <div id="about">
        <div class="container">
            <div class="row">
                <div class="about-col-1">
                    <img src="images/Mix_20250412_103120.jpg">
                </div>
                <div class="about-col-2">
                    <h1 class="sub-title">About Me</h1>
                    <p>Hi, I'm Abdul Hafeez — a passionate content creator, aspiring entrepreneur, and a computer
                        science student with a mission to make a meaningful impact. Whether it's through coding,
                        tutoring, or creating funny Punjabi dubbing content on my channel "Funkey Monkey Fun," I love
                        bringing creativity and value to people’s lives.

                        With a growing interest in web development, app development, data science, and cybersecurity,
                        I’m constantly learning and building things that solve real-world problems. My entrepreneurial
                        journey is driven by a desire to uplift my family, serve my community in Pakistan, and
                        eventually make a global difference.

                        I also teach students both locally and online, and I actively participate in social welfare
                        initiatives promoting peace, education, and positivity.

                        Let’s connect if you’re looking to collaborate, build, or simply talk ideas!</p>
                    <div class="tab-titles">
                        <p class="tab-links active-link" onclick="opentab('skills')">Skills</p>
                        <p class="tab-links" onclick="opentab('experience')">Experience</p>
                        <p class="tab-links" onclick="opentab('education')">Education</p>
                    </div>
                    <div class="tab-contents active-tab" id="skills">
                        <ul>
                            <li><span>UI/UX</span><br>Designing Web/App Interfaces</li>
                            <li><span>Web Development</span><br>Building Website</li>
                            <li><span>App Development</span><br>Building Andriod Applications</li>
                        </ul>
                    </div>
                    <div class="tab-contents" id="experience">
                        <ul>
                            <li><span>2021-Current</span><br>UI/UX Training at ET Institute</li>
                            <li><span>2019-2021</span><br>Team Lead at startup LLC</li>
                            <li><span>2016-17</span><br>Internship at Ekart Ecommerce</li>
                        </ul>
                    </div>
                    <div class="tab-contents" id="education">
                        <ul>
                            <li><span>2024-28</span><br>Pursuing BSCS at NUML</li>
                            <li><span>2021-23</span><br>Intermediate in Pre Engineering from Aspire College</li>
                            <li><span>2019-21</span><br>Matriculation From Govt MC High School</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- Services -->
    <div id="services">
        <div class="container">
            <h1 class="sub-title">My Services</h1>
            <div class="services-list">
                <div>
                    <i class="fa-solid fa-code"></i>
                    <h2>Web Design</h2>
                    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Dolores eligendi et nostrum unde vero
                        ex ullam quae autem! Ducimus ea nisi rerum. Alias vero ea earum! Aliquam quasi amet cumque!</p>
                    <a href="#">Learn more</a>
                </div>
                <div>
                    <i class="fa-solid fa-crop"></i>
                    <h2>UI/UX Design</h2>

                    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Dolores eligendi et nostrum unde vero
                        ex ullam quae autem! Ducimus ea nisi rerum. Alias vero ea earum! Aliquam quasi amet cumque!</p>
                    <a href="#">Learn more</a>
                </div>
                <div>
                    <i class="fa-brands fa-app-store-ios"></i>
                    <h2>App Design</h2>
                    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Dolores eligendi et nostrum unde vero
                        ex ullam quae autem! Ducimus ea nisi rerum. Alias vero ea earum! Aliquam quasi amet cumque!</p>
                    <a href="#">Learn more</a>
                </div>

            </div>
        </div>
    </div>
    <!-- Portfolio -->
    <div id="portfolio">
        <div class="container">
            <h1 class="sub-title">My Work</h1>
            <div class="work-list">
                <div class="work">
                    <img src="./images/work-1.png">
                    <div class="layer">
                        <h3>Online Shopping App</h3>
                        <p>The app connecs you to the talented people around the world.
                            Download the app now and start connecting with people.</p>
                        <a href="#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                        </p>
                    </div>
                </div>

                <div class="work">

                    <img src="./images/work-2.png">
                    <div class="layer">
                        <h3>Social Media App</h3>
                        <p>The app connecs you to the talented people around the world.
                            Download the app now and start connecting with people.</p>
                        <a href="#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                        </p>
                    </div>
                </div>

                <div class="work">
                    <img src="./images/work-3.png">
                    <div class="layer">
                        <h3>Music App</h3>
                        <p>The app connecs you to the talented people around the world.
                            Download the app now and start connecting with people.</p>
                        <a href="#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                        </p>
                    </div>
                </div>

            </div>
            <a href="#" class="btn">See More</a>
        </div>
    </div>
    <!-- Contact -->
    <div id="contact">
        <div class="container">
            <div class="row">
                <div class="contact-left">
                    <h1 class="sub-title">Contact Me</h1>
                    <p><i class="fas fa-paper-plane"></i>shayanmirza736@gmail.com</p>
                    <p><i class="fas fa-phone-square-alt"></i>+92 3286956197</p>
                    <div class="social-icons">
                        <a href="#"><i class="fa-brands fa-facebook"></i></a>
                        <a href="#"><i class="fa-brands fa-twitter-square"></i></a>
                        <a href="#"><i class="fa-brands fa-instagram"></i></a>
                        <a href="#"><i class="fa-brands fa-linkedin"></i></a>
                    </div>
                    <a href="images/Resume.pdf" download class="btn btn2">Download CV</a>
                </div>
                <div class="contact-right">
                    <form name="submit-to-google-sheet">
                        <input type="text" name="Name" id="" placeholder="Your Name" required>
                        <input type="email" name="Email" id="" placeholder="Your Email" required>
                        <textarea name="Message" rows="6" placeholder="Your Message"></textarea>
                        <button type="submit" class="btn btn2">Submit</button>

                    </form>
                    <span id="msg"></span>
                </div>
            </div>
        </div>
        <div class="copyright">
            <p>&copy; 2025 Shayan Mirza. All rights reserved.</p>

        </div>
    </div>
    <script>
        var tablinks = document.getElementsByClassName("tab-links");
        var tabcontents = document.getElementsByClassName("tab-contents");
        function opentab(tabname) {
            for (tablink of tablinks) {
                tablink.classList.remove("active-link");
            }
            for (tabcontent of tabcontents) {
                tabcontent.classList.remove("active-tab");
            }
            event.currentTarget.classList.add("active-link");
            document.getElementById(tabname).classList.add("active-tab");
        }
    </script>
    <script>
        var sidemenu = document.getElementById("sidemenu");
        function openmenu() {
            sidemenu.style.right = "0";
        }
        function closemenu() {
            sidemenu.style.right = "-200px";
        }
    </script>
    <script>
        const scriptURL = 'https://script.google.com/macros/s/AKfycbxdidFMrrOm58fQrfqUMbCh2sOu0lGcQBPy-DsekwOCoSloVdDRoOpAb-L9V4AMyH5AbQ/exec'
        const form = document.forms['submit-to-google-sheet']
        const msg = document.getElementById("msg")
        form.addEventListener('submit', e => {
            e.preventDefault()
            fetch(scriptURL, { method: 'POST', body: new FormData(form) })
                .then(response => {
                    msg.innerHTML = "Message sent successfully!"
                    setTimeout(function () {
                        msg.innerHTML = ""
                    }, 5000);
                    form.reset()
                })
                .catch(error => console.error('Error!', error.message))
        })
    </script>
</body>

</html>
