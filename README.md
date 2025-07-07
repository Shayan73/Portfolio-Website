// HTML Section
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


// CSS Section
* {
    margin: 0;
    padding: 0;
    font-family: 'Poppins', sans-serif;
    box-sizing: border-box;

}

body {
    background-color: #080808;
    color: #fff;


}

html {
    scroll-behavior: smooth;

}

#header {
    width: 100%;
    height: 100vh;
    background-image: url(images/background.png);
    background-size: cover;
    background-position: center;

}

.container {
    padding: 10px 10%;



}

nav {

    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
}

.logo {
    width: 140px;

}

nav ul li {
    display: inline-block;
    list-style: none;
    margin: 10px 20px;
}

nav ul li a {
    text-decoration: none;
    color: #fff;
    font-size: 18px;
    position: relative;

}

nav ul li a::after {
    content: '';
    width: 0;
    height: 3px;
    background-color: #ff004f;
    position: absolute;
    left: 0;
    bottom: -6px;
    transition: 0.5s;
}

nav ul li a:hover::after {
    width: 100%;

}

.header-text {
    margin-top: 20%;
    font-size: 30px;

}

.header-text h1 {
    font-size: 60px;
    margin-top: 20px;

}

.header-text h1 span {
    color: #ff004f;

}

/* about */
#about {
    padding: 80px 0px;

    color: #ababab;

}

.row {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;

}

.about-col-1 {
    flex-basis: 35%;

}

.about-col-1 img {
    width: 100%;

    border-radius: 15px;

}

.about-col-2 {
    flex-basis: 60%;

}

.sub-title {
    font-size: 60px;
    font-weight: 600;
    color: white;
}

.tab-titles {
    display: flex;
    margin: 25px 0px 40px;
}

.tab-links {
    margin-right: 50px;
    font-size: 18px;
    font-weight: 500;
    cursor: pointer;
    position: relative;
}

.tab-links::after {
    content: '';
    width: 0;
    height: 3px;
    color: #ff004f;
    position: absolute;
    left: 0;
    bottom: -8px;
    transition: 0.5s;
}

.tab-links.active-link::after {
    width: 50%;
    background-color: #ff004f;

}

.tab-contents ul li {
    list-style: none;
    margin: 10px 0px;
}

.tab-contents ul li span {
    color: #b54769;
    font-size: 14px;
}

.tab-contents {
    display: none;
}

.tab-contents.active-tab {
    display: block;

}

/* services */
#services {
    padding: 30px 0px;


}

.services-list {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    grid-gap: 40px;
    margin-top: 50px;

}

.services-list div {
    background: #262626;
    padding: 40px;
    font-size: 13px;
    font-weight: 300;
    border-radius: 10px;
    transition: background 0.5s, transform 0.5s;
}

.services-list div i {
    font-size: 40px;

    margin-bottom: 30px;

}

.services-list div h2 {
    font-size: 30px;
    font-weight: 500;
    margin-bottom: 15px;

}

.services-list div a {
    text-decoration: none;
    color: #fff;
    margin-top: 20px;
    font-size: 12px;
    display: inline-block;
}

.services-list div:hover {
    background: #ff004f;
    transform: translateY(10px);

}

/* portfolio */
#portfolio {
    padding: 50px 0px;

}

.work-list {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    grid-gap: 40px;
    margin-top: 50px;


}

.work {
    border-radius: 10px;
    position: relative;
    overflow: hidden;

}

.work img {
    width: 100%;
    border-radius: 10px;
    display: block;
    transition: transform 0.5s, height 0.5s;

}

.layer {
    width: 100%;
    height: 0;
    background: linear-gradient(rgba(0, 0, 0, 0.6), #ff004f);
    border-radius: 10px;
    position: absolute;
    bottom: 0;
    left: 0;
    overflow: hidden;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    padding: 0 40px;
    text-align: center;
    font-size: 14px;
    transition: height 0.5s;

}

.layer h3 {
    font-weight: 500;
    margin-bottom: 20px;

}

.layer a {
    margin-top: 20px;
    text-decoration: none;
    font-size: 18px;
    color: #ff004f;
    background: white;
    line-height: 60px;
    width: 60px;
    height: 60px;
    border-radius: 50%;
    text-align: center;
}

.work:hover img {
    height: 100%;
    transform: scale(1.1);
    transition: height 0.5s;

}

.work:hover .layer {
    height: 100%;
    transition: height 0.5s;

}

.btn {
    display: block;
    margin: 50px auto;
    width: fit-content;
    border: 1px solid #ff004f;
    padding: 14px 50px;
    border-radius: 6px;
    text-decoration: none;
    color: white;
    transition: background 0.5s, color 0.5s;

}

.btn:hover {
    background: #ff004f;

}

/* <!-- Contact --> */
.contact-left {
    flex-basis: 35%;
}

.contact-right {
    flex-basis: 60%;
}

.contact-left p {
    margin-top: 30px;
}

.contact-left p i {
    color: #ff004f;
    margin-right: 15px;
    font-size: 25px;
}

.social-icons {

    margin-top: 20px;
}

.social-icons a {
    text-decoration: none;
    color: #ababab;
    display: inline-block;
    font-size: 30px;
    margin-right: 15px;
    transition: transform 0.5s;
}

.social-icons a:hover {
    color: #ff004f;
    transform: translateY(-5px);
}

.btn.btn2 {
    display: inline-block;
    background: #ff004f;

}

.contact-right form {
    width: 100%;


}

form input,
form textarea {
    width: 100%;
    padding: 15px;
    border-radius: 6px;
    margin: 15px 0;
    border: 0;
    outline: none;
    color: #fff;
    border-radius: 6px;
    font-size: 18px;
    background: #262626;

}

form .btn2 {
    padding: 14px 60px;
    font-size: 18px;
    margin-top: 20px;
    cursor: pointer;
}

.copyright {
    text-align: center;
    padding: 25px 0;
    background: #262626;
    width: 100%;
    font-weight: 300;
    margin-top: 20px;

    font-size: 14px;
}

nav .fas {
    display: none;

}

/* css for small screens */
@media only screen and (max-width: 600px) {
    #header {
        background-image: url(images/phone-background.png);
    }

    .header-text {
        margin-top: 100%;

        font-size: 16px;
    }

    .header-text h1 {
        font-size: 30px;
    }

    nav .fas {
        display: block;
        font-size: 25px;
    }

    nav ul {
        position: fixed;
        top: 100%;
        right: -200;
        top: 0;
        width: 200px;
        height: 100vh;
        background: #ff004f;
        padding-top: 50px;
        z-index: 2;
        transition: right 0.5s;
    }

    nav ul li {
        display: block;
        margin: 25px;

    }

    nav ul .fas {
        position: absolute;
        top: 25px;
        left: 25px;
        cursor: pointer;
    }

    .sub-title {
        font-size: 40px;

    }

    .about-col-1,
    .about-col-2 {
        flex-basis: 100%;

    }

    .about-col-1 {
        margin-bottom: 30px;

    }

    .about-col-2 {
        font-size: 14px;

    }

    .tab-links {
        font-size: 16px;
        margin-right: 20px;

    }

    .contact-left,
    .contact-right {
        flex-basis: 100%;
    }

    .copyright {
        font-size: 14px;
    }

}

#msg {
    color: #61b752;
    margin-top: -40px;
    display: block;

}
