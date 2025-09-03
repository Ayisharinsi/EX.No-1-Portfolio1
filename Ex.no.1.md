# Ex01 Portfolio
Name: Ayisha Rinsi k
Reg No: 212223040022
## Date:3-9-25

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
portfolio.html
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <div class="nav-bar">
        <div class="nav-title">
            <h2>Home</h2>
        </div>
        <div class="nav-icons">
            <ul>
                <li>EDUCATIONS</li>
                <li>SKILLS</li>
                <li>EXPERIENCE</li>
                <li>PROFILE</li>
                <li>CONTACTS</li>
            </ul>
        </div>
    </div>
    <div class="background">
        <img src="images/back.jpg" alt="">
        <div class="background-body">
            <h1>HELLO, I AM</h1>
            <h1 id="namechange">AYISHA RINSI</h1>
            <h1>WELCOME!</h1>
            <h2>Creative Frontend Engineer</h2>
            <button>Download Resume</button>
        </div>
    </div>
    <div class="about-title">
        <h1>ABOUT ME</h1>
    </div>
    <div class="aboutme">
        <div class="aboutme-details">
            <p>
                I am a passionate and ambitious Frontend Developer who loves bringing creative ideas to life through
                code. As a beginner in frontend development, I am constantly exploring new technologies and refining my
                skills in HTML, CSS, and JavaScript to build interactive, responsive, and visually appealing web
                experiences. I have a deep enthusiasm for modern UI/UX design and enjoy experimenting with different
                layouts, animations, and user-friendly components. Learning new frameworks like React and Tailwind CSS
                excites me, as I strive to create efficient and scalable applications that enhance user interaction.</p>
            <p>To strengthen my skills, I am actively working on multiple projects, ranging from simple landing pages to
                complex web applications. Each project allows me to improve my problem-solving abilities, implement new
                design patterns, and optimize web performance. I believe that hands-on practice is the best way to
                learn, and I dedicate time to learning best practices, debugging, and improving my code structure.
                Beyond coding, I love collaborating with other developers, exchanging ideas, and contributing to
                open-source projects. My ultimate goal is to become a skilled frontend engineer who can develop seamless
                and impactful web experiences while continuously evolving in the tech industry.

            </p>

            <hr>
            <div class="about-contact">
                <div>
                    <p><b>Phone No</b></p>
                    <p style="color: gray;">8974789250</p>
                </div>
                <div>
                    <p><b>Email</b></p>
                    <p style="color: gray;">rinzy12@gmail.com</p>
                </div>
                <div>
                    <p><b>Linkdin Profile</b></p>
                    <p style="color: gray;">www.linkdinrinzy</p>
                </div>
            </div>
        </div>
        <div class="picture">
            <img src="images/icon.jpg" alt="">
        </div>
    </div>
    <div class="education-title">
        <h1>EDUCATION</h1>
        <div class="education">
            <div class="detail1">
                <h4 style="color: black;">2011 - 2015</h4>
                <p>Elementary School</p>
                <hr>
                <h4 style="color: black;">EVNR GOV GIRLS HR SCHOOL</h4>
                <p>Vellore</p>
                <p>Army Public School (APS) Chennai, affiliated with CBSE, primarily serves children of
                    army personnel. Chintadripet Boys Higher Secondary School focuses on secondary and higher secondary
                    education for boys. Wesley Higher Secondary School provides quality education under the Tamil Nadu
                    State
                    Board.</p>
            </div>
            <div class="detail1">
                <h4 style="color: black;">2016 - 2022</h4>
                <p>Higher Secondary</p>
                <hr>
                <h4 style="color: black;">VELLORE MODAL SCHOOL</h4>
                <p>Vellore</p>
                <p>Arignar Anna Government Higher Secondary School in Chennai offers education from primary to higher
                    secondary levels. Army Public School (APS) Chennai, affiliated with CBSE, primarily serves children
                    of
                    army personnel. Chintadripet Boys Higher Secondary School focuses on secondary and higher secondary
                    education for boys. Wesley Higher Secondary School provides quality education under the Tamil Nadu
                    State
                    Board.</p>
            </div>
            <div class="detail1">
                <h4 style="color: black;">2023 - 2025</h4>
                <p>College/University Levels</p>
                <hr>
                <h4 style="color: black;">SAVEETHA ENGINEERING COLLEGE</h4>
                <p>Chennai</p>
                <p>Affiliated with Anna University, this autonomous institution offers undergraduate and postgraduate
                    programs in engineering. The college emphasizes an industry-ready curriculum designed to impart
                    21st-century skills, preparing students for emerging technological advancements.</p>
            </div>
        </div>
    </div>
    <div class="skills-title">
        <h1>SKILLS</h1>
        <div class="skill">
            <div class="skill_classification1">
                <div class="skills_1">
                    <h4>HTML 5</h4>
                    <progress value="97" max="100">97%</progress>
                </div>
                <div class="skills_2">
                    <h4>CSS#</h4>
                    <progress value="95" max="100"></progress>
                </div>
                <div class="skills_3">
                    <h4>JavaScript</h4>
                    <progress value="80" max="100"></progress>
                </div>
            </div>
            <div class="skill_classification2">
                <div class="skills_4">
                    <h4>VERSION CONTROL</h4>
                    <progress value="90" max="100"></progress>
                </div>
                <div class="skills_5">
                    <h4>COMMUNICATION</h4>
                    <progress value="90" max="100"></progress>
                </div>
                <div class="skills_6">
                    <h4>ADAPTIBILITY</h4>
                    <progress value="95" max="100"></progress>
                </div>
            </div>
        </div>
    </div>
    <div class="project-title">
        <h1>PROJECTS</h1>
        <div class="project">
            <div class="image-gallery">
                <h2 style="color: black;">IMAGE GALLERY</h2>
                <img src="images/image-gallery.png" alt="Image-gallery">
                <h3>DESCRIPTION</h3>
                <p>-Responsive Design - Works seamlessly on all screen sizes</p>
                <p>-Image Navigation - Browse images using interactive buttons</p>
                <p>-Smooth Transitions - Enhances user experience with animations</p>
                <p>-Lightweight & Fast - Optimized for better performance</p>
            </div>
            <div class="Book-sky">
                <h2 style="color: black;">BOOK SKY</h2>
                <img src="images/booksky.png" alt="Book-sky">
                <h3>DESCRIPTION</h3>
                <p>-Responsive Design - Works seamlessly on all screen sizes</p>
                <p>-Interactive UI - Modern card-based layout with a visually design.</p>
                <p>Persistent Storage - Saves book data using local storage for future access.</p>
                <p>-Lightweight & Fast - Optimized for better performance</p>
            </div>
        </div>
    </div>
    <div class="contact-title">
        <h1>CONTACT ME</h1>
        <div class="contact">
            <div class="contact-page">
                <div class="page1">
                    <input type="text" placeholder="NAME">
                    <input type="email" placeholder="EMAIL">
                </div>
                <div class="page2">
                    <textarea name="message" id="message" placeholder="MESSAGE"></textarea>
                    <button>SUBMIT</button>
                </div>
            </div>
            <div class="information">
                <div class="info1">
                    <h2>AYISHA RINSI</h2>
                    <h3 style="color: grey;">FRONTEND DEVELOPER</h3>
                </div>
                <div class="info1">
                    <h2>PHONE NO</h2>
                    <h3 style="color: grey;">8963753768</h3>
                </div>
                <div class="info1">
                    <h2>EMAIL</h2>
                    <h3 style="color: grey;">rinzy@gmail.com</h3>
                </div>
                <div class="info1">
                    <h2>Linkdin</h2>
                    <h3 style="color: grey;">rinsi@linkdin.com</h3>
                </div>
            </div>
        </div>
    </div>
</body>

</html>
```
style.css
```
* {
    margin: 0;
    padding: 0;
}

.nav-bar {
    display: flex;
    height: auto;
    padding: 10px;
    justify-content: space-between;
}

.nav-title h2 {
    padding: 10px;
    color: black;
    font-size: 25px;
    font-style: normal;
}

.nav-icons ul {
    display: flex;
    justify-content: center;
    gap: 30px;
    padding: 10px;
}

.nav-icons ul li {
    list-style: none;
    font-weight: bolder;
}

.background img {
    position: absolute;
    width: 100%;
    height: 678px;
    object-fit: cover;
}

#namechange {
    font-size: 40px;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}

.background-body {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    gap: 30px;
    height: 100vh;
}

.background-body h1,
h2,
button {
    z-index: 1;
    color: white;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    font-weight: bolder;
    font-size: 2vw;
}

button {
    background-color: white;
    color: black;
    width: 15%;
    font-size: large;
    height: 50px;
    border-radius: 10px;
}

.aboutme{
    display: flex; 
    justify-content: space-around;  
    align-items: center;
    box-sizing: border-box;
}
.aboutme-details{
    display: flex;
    position: relative;
    left: 100px;
    flex-direction: column;
    padding: 10px;
    margin: 5px 5px 5px 5px;
    gap: 50px;
}
.about-contact{
    display: flex;
    justify-content: space-evenly;
    padding: 5px;
    margin: 5px 0 0 5px;
}
.picture img{
    width: 50%;
    border-radius: 50%;
    box-shadow: 5px 5px 10px rgba(0, 0, 0, 0.6);
}
.picture{
    display: flex;
    justify-content:center;
}
.about-title, .education-title h1{
    text-align: center;
    margin-bottom: 50px;
    margin-top: 40px;
    padding: 20px;
}

.education{
    display: flex;
    justify-content: space-around;
    margin: 5px;
    padding: 50px;
    gap: 50px;
}
.education-title{
    background-color:whitesmoke;
}
.detail1 p{
    margin-bottom: 10px;
}
.detail1 h4{
    padding-top: 10px;
}

.skills-title{
    text-align: center;
    margin: 20px;
}
.skill{
    display: flex;
    justify-content: space-around;
    height: 300px;
}

.skill_classification1, .skill_classification2{
    display: flex;
    flex-direction: column;
    justify-content: center;
    gap: 20px;
    margin-top: 20px;
    width: 30%;
}

progress {
    width: 400px;
    height: 10px;
    background-color:darkblue;
}

progress::-webkit-progress-value {
    background-color: rgb(15, 103, 244)
}

::-webkit-progress-bar {
    background: rgba(209, 226, 234, 0.858)
}

.project-title h1,.project-title    {
    text-align: center;
    margin-top: 50px;
    margin-bottom: 50px;
    padding: 20px;
    background-color: whitesmoke;
}
.project{
    display: flex;
    justify-content:center;
    align-items: center;
}

.image-gallery img,.Book-sky img{
    height: 350px;
    width: 80%;
    border-radius: 10px;
}
.image-gallery,.Book-sky{
    display: flex;
    flex-direction: column;
    align-items: self-start;
    justify-content: center;
    gap: 6px;
    margin-left: 150px;
}

.contact-title h1{
    text-align: center;
    padding: 20px;
}
.contact{
    display: flex;
    justify-content: center;
    gap: 100px;
    height: 400px;
}

.contact-page{
    display: flex;
    flex-direction: column;
}

.page1{
    display: flex;
    gap: 20px;
    padding: 10px;
}

.page2{
    display: flex;
    flex-direction: column;
    gap: 20px;
    padding: 10px;  
}

.page1 input,.page2 textarea,.page2 button{
    width: 100%;
    height: 30px;
    padding: 8px;
}
.page2 textarea{
    height: 150px;
}

.information{
    display: flex;
    flex-direction: column;
    gap: 10px;
}
.info1{
    display: flex;
    flex-direction: column;
    gap: 10px;

}

.info1 h2{
    color: black;
    font-family: Georgia, 'Times New Roman', Times, serif;
    font-style: normal;
    font-size: large;
}
.page2 button{
    height: 60px;
    width: 100%;
    background-color: blueviolet;
    padding: 10px;
    margin-bottom: 10px;
}
```

## OUTPUT
<img width="1826" height="914" alt="image" src="https://github.com/user-attachments/assets/e78e9943-2155-4f0c-bf64-21f226cd4682" />
<img width="1829" height="887" alt="image" src="https://github.com/user-attachments/assets/84acd556-39c4-4aae-a14c-4228d7dcd16f" />
<img width="1845" height="923" alt="image" src="https://github.com/user-attachments/assets/2e60a09a-1b95-47c0-897f-59dd0f4f154e" />
<img width="1833" height="893" alt="image" src="https://github.com/user-attachments/assets/5b122776-a6e5-48d6-a07c-43778b6ec19d" />
<img width="1796" height="613" alt="image" src="https://github.com/user-attachments/assets/cddaf999-d5e4-4755-9405-3e4f3a04dd53" />

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
