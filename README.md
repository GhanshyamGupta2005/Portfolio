# Portfolio

Welcome to my portfolio! This repository showcases my skills, projects, and a bit about myself.

## About Me

Hi, I'm Ghanshyam Gupta, a passionate software developer currently pursuing a Bachelor's degree in Computer Science and Engineering. This portfolio is a reflection of my journey, projects, and skills.

## Technologies Used

- HTML
- CSS
- JavaScript

## Projects

### 1. [RPG Game]([link-to-project1](https://github.com/GhanshyamGupta2005/RPG))

I've created a text-based RPG game using C++. It's a project that showcases my programming

### 2. [Solidity Contract ]([link-to-project2](https://github.com/GhanshyamGupta2005/Smart_Contract_Using_Solidity))

Decentralized lottery smart contract on Ethereum.



## Getting Started

If you want to check out my portfolio locally or contribute, follow these steps:

1. Clone this repository.
2. Open the `index.html` file in your browser.

Feel free to explore and reach out if you have any questions or suggestions!

## Contact

- Email: ghanshyamg.cs.22@nitj.ac.in
- LinkedIn: [[ LinkedIn Profile](https://www.linkedin.com/in/ghanshyam-gupta-a5744528a/)]
- GitHub: [ [Github](https://github.com/ghanshyamgcs22)]


## HTML Code

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ghanshyam</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
    <script src="https://kit.fontawesome.com/0a85766be0.js" crossorigin="anonymous"></script>
    <link rel="icon" href="logo.png" style="height: auto; width: auto;" >
    <style>
        * {
            margin: 0;
            padding: 0;
        }

        body {
            background-color: rgb(0, 0, 30);
            color: white;
            font-family: "Poppins", sans-serif;
        }
        
    </style>
</head>

<body>
    <header class="header">
        <nav>
            <div class="left"> <img src="logo.png" style="height: 130px; width: 200px; "></div>
            <div class="right " >
                <ul id="sidemenu">
                    <li> <a href="#header">Home </a></li>
                    <br>
                    <li> <a href="#about">About </a></li>
                    <br>
                    <li> <a href="#services">Services </a></li>
                    <br>
                    <li> <a href="#port">Projects </a></li>
                    <br>
                    <li> <a href="#contact">Contact </a></li>
                    <br>
                    <i class="fa-solid fa-times" onclick="closemenu()"></i>
                    
                </ul>
                <i class="fa-solid fa-bars" onclick="openmenu()"></i>
            </div>
        </nav>
    </header>
    <main>
        <section class="firstSec">
            <div class="leftSec">
                <div >Hi, My Name is</div>
                <div class="purple">Ghanshyam</div>
                <div>I am a passionate </div>
                <!-- <div> python devloper</div> -->
                <span id="element"></span>
              
            </div>
            <div class="rightSec">
                <img src="bg.png" alt="">
            </div>
        </section>

        <div id="about">
            <div class="container">
                <div class="row">
                    <div class="about-col-1">
                        <!-- <img class="bgimg" src="2nd.png" alt=""> -->
                    </div>
                    <div class="about-col-2">
                        <h1 class="subtitle">About Me</h1>
                        <!-- <p>Greetings! I'm a Passionate Software Developer skilled in C, C++, and Python. Excited about AI-ML and Blockchain (Solidity). Frontend adept with HTML, CSS, and JavaScript. Committed to innovation and staying updated in software development</p> -->
                        <span id="aboutme"></span>
                        <div class="tab-titles">
                            <p class="tab-link active-link" onclick="opentab('skills')">Skills</p>
                            <!-- <p class="tab-link" onclick="opentab('experience')">Experience</p> -->
                            <p class="tab-link" onclick="opentab('education')">Education</p>
    
                        </div>
                        <div class="tab-contents active-tab " id="skills">
                            <ul>
                                <li><span>C/C++</span><br>DSA</li>
                                <li><span>Python</span><br>Opencv,Pandas, Numpy</li>
                                <li><span>Solidty</span><br>Eth-Contracts</li>
                                <li><span>JS</span><br>Frontend</li>
                            </ul>
                        </div>
                        <!-- <div class="tab-contents" id="experience">
                            <ul>
                                <li><span>C/C++</span><br></li>
                                <li><span>Python</span><br></li>
                                <li><span>Solidty</span><br></li>
                                <li><span>JS</span><br></li>
                            </ul>
                        </div> -->
                        <div class="tab-contents" id="education">
                            <ul>
                                <li><span>2022-Current</span><br>Pursuing a Bachelor of Technology in Computer Science and Engineering at Dr. B. R. Ambedkar National Institute of Technology Jalandhar, Punjab, India </li>
                                <li><span>2021-2022</span><br>Senior secondary education at Engineers Point Senior Secondary School in Alwar, Rajasthan</li>
                                <li><span>2019-2020</span><br>Secondary education at Engineers Point Senior Secondary School in Alwar, Rajasthan</li>
                    
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    <!-- services -->
        <div id="services">
            <div class="container">
                <h1 class="subtitle">My Services</h1>
                <div class="services-list">
    
                    <div>
                        <!-- <i class="fa-solid fa-c"></i> -->
                        <i class="fa-solid fa-code"></i>
                        <h2>Debuging</h2>
                        <p>As a debugger, I'm here to fix problems in your code! I'm good at finding and resolving coding issues, making sure your programs work smoothly. If you need help making your code bug-free,You can contact me anytime.</p>
                        <a href="#">Learn more</a>
                    </div>
                    <div>
                        <i class="fa-brands fa-python"></i>
                        <h2>Python Devloper</h2>
                        <p>Aspiring Python developer keen on expanding skills in web development and data analysis. Eager to learn and take on new challenges, I am dedicated to enhancing my proficiency in creating websites and extracting meaningful insights from data using Python. Open to collaboration and excited about the journey of continuous improvement and growth in the world of programming.

                        </p>
                        <a href="#">Learn more</a>
                    </div>
                    <div>
                        <i class="fa-brands fa-ethereum"></i>
                        <h2>Eth-Contracts</h2>
                        <p>I can create special codes for Ethereum using a language called Solidity. These codes make sure everything on the Ethereum blockchain works smoothly and securely. If you want a safe and customized blockchain solution, I'm here to help! Let's make your project stand out with advanced blockchain technology and secure transactions.</p>
                        <a href="#">Learn more</a>
                    </div>
                </div>
    
            </div>
    
        </div>


         <!-- Potfolio -->
<div id="port">
    <div class="container">
        <h1 class="subtitle">My projects</h1>
        <div class="work-list">
            <div class="work">
                <img src="work-1.png">
                <div class="layer">
                    <h3>RPG Game</h3>
                    <p>I've created a text-based RPG game using C++. It's a project 
                        that showcases my programming </p>
                    <a href="https://github.com/ghanshyamgcs22/RPG-Console-Game" target="_blank"><i class="fa-solid fa-up-right-from-square"></i></a>
                </div>
            </div>
            <div class="work">
                <img src="work-2.png">
                <div class="layer">
                    <h3>Video Processing</h3>
                    <p>I'm currently working on a project using Python for video processing.</p>
                    <a href="https://github.com/ghanshyamgcs22/Study-Ready-State" target="_blank"><i class="fa-solid fa-up-right-from-square"></i></a>
                </div>
            </div>
            <div class="work">
                <img src="work-3.png">
                <div class="layer">
                    <h3>Solidity Contarct</h3>
                    <p>I specialize in developing and deploying Solidity contracts for blockchain applications.</p>
                    <a href="https://github.com/ghanshyamgcs22/Lottery-Smart-Contract" target="_blank"><i class="fa-solid fa-up-right-from-square"></i></a>
                </div>
            </div>
        </div>
        <a href="#" class="btn">See more</a>
    </div>
</div>

<div id="contact">
    <div class="container">
        <div class="row">
            <div class="contact-left">
                <h1 class="subtitle">Contact Me</h1>
                <p><i class="fa-solid fa-envelope"></i>  ghanshyamg.cs.22@nitj.ac.in</p>
                <p><i class="fa-solid fa-phone"></i>8875*****7</p>
                <div class="social-icons">
                    <a href="https://www.instagram.com/gupta__shyam__rajasthan/" target="_blank" rel="noopener noreferrer"><i class="fa-brands fa-instagram"></i></a>
                    <a href="https://www.linkedin.com/in/ghanshyam-gupta-a5744528a/" target="_blank" rel="noopener noreferrer"><i class="fa-brands fa-linkedin"></i></a>
                    <a href="https://github.com/ghanshyamgcs22" target="_blank" rel="noopener noreferrer"><i class="fa-brands fa-github"></i></a>
                                    </div>
                <a href="https://docs.google.com/document/d/1azwC_KnV6OB6DeBDf_il-CWH8NiouNgyhlgQeqi2rJU/edit" target="_blank"class="btn btn2">Resume</a>
            </div>
            <div class="contact-right">
            <form name="submit-to-google-sheet">
                <input type="text" name="Name" placeholder="Your Name" required>
                <input type="email" name="email" id="" placeholder="Your Email" required>
                <textarea name="Message" id="" rows="6" placeholder="Your message"></textarea>
                <button type="submit" class="btn btn2">Submit</button>
            </form>
            <span id="msg"></span>
        </div>
        </div>
    </div>
    <div class="copyright">
        <p>Copyright @ghanshyam</p>
    </div>
</div>
<script>

    var tabLinks = document.getElementsByClassName('tab-link');
    var tabContents = document.getElementsByClassName('tab-contents');
    function opentab(tabName) {
        for (tabLink of tabLinks) {
            tabLink.classList.remove("active-link");

        }
        for (tabContent of tabContents) {
            tabContent.classList.remove("active-tab");

        }

        event.currentTarget.classList.add('active-link');
        document.getElementById(tabName).classList.add('active-tab');
    }



</script>
<script>
    // var sidemenu = document.getElementById('sidemenu');

    // function openmenu() {
    //     sidemenu.style.width = '200px';
    // }

    // function closemenu() {
    //     sidemenu.style.width = '0';
    // }

    var sidemenu = document.getElementById('sidemenu');

function openmenu() {
    sidemenu.style.width = '200px';
}

function closemenu() {
    sidemenu.style.width = '0';
}

function scrollToSection(sectionId) {
    var section = document.getElementById(sectionId);
    if (section) {
        section.scrollIntoView({ behavior: 'smooth' });
        closemenu(); // close the side menu after scrolling
    }
}

// Attach click event listeners to the side menu items
var sideMenuItems = document.querySelectorAll('#sidemenu a');
sideMenuItems.forEach(function (item) {
    item.addEventListener('click', function (event) {
        event.preventDefault();
        var sectionId = item.getAttribute('href').substring(1);
        scrollToSection(sectionId);
    });
});
</script>




<script>
const scriptURL = 'https://script.google.com/macros/s/AKfycbxP4Ik3fWi54vAc2Jm5HX212GJjJm_LX4ghiW2UPrOLYbgb88GbW2vP_QQ4iYPCCTrO/exec'
const form = document.forms['submit-to-google-sheet']
const msg=document.getElementById('msg')
form.addEventListener('submit', e => {
  e.preventDefault()
  fetch(scriptURL, { method: 'POST', body: new FormData(form)})
    .then(response => {msg.innerHTML="Message sent successfully"
setTimeout(function (){
    msg.innerHTML=''
},5000)
form.reset();
})
    .catch(error => console.error('Error!', error.message))
})
</script>
    <script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>

    <!-- Setup and start animation! -->
    <script>
        var typed = new Typed('#element', {
            strings: ['Frontend Devloper', 'Python Devloper', 'Blockchain Devloper'],
            typeSpeed: 50,
        });
    </script>

<script>
    var typed = new Typed('#aboutme', {
        strings: ["Greetings! I'm a Passionate Software Developer skilled in C, C++, and Python. Excited about AI-ML and Blockchain (Solidity). Frontend adept with HTML, CSS, and JavaScript. Committed to innovation and staying updated in software development."],
        typeSpeed: 50,
    });
</script>
</body>

</html>


