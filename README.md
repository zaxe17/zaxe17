# My Website
This is my Website [zaxe17.github.io/hello/](https://zaxe17.github.io/hello/), which you can visit anytime.

Visit my PHP project [Techtilanotes](https://techtilanotes.22web.org) a note taking.


![logo](https://media.tenor.com/CKIexctq4C8AAAAi/arisu-blue-archive.gif)

## About
I'm Jan Marc, and I want to work as a web developer.

## Languages and Tools
<p align="left"> 
  <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> 
  </a> 
  <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> 
  </a> 
  <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> 
  </a> 
  <a href="https://www.java.com" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> 
  </a> 
  <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> 
  </a> 
  <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> 
  </a> 
  <a href="https://www.php.net" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="php" width="40" height="40"/> 
  </a> 
  <a href="https://reactjs.org/" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/> 
  </a> 
</p>

.skills {
    min-height: auto;
    padding-bottom: 7rem;
}

.skills .skills-row {
    display: flex;
    flex-wrap: wrap;
    gap: 5rem;
}

.skills-row .skills-column {
    flex: 1 1 40rem;
}

.skills-column h3 {
    color: var(--tLink);
}

.skills-column .title {
    text-transform: uppercase;
    font-size: 2.5rem;
    margin: 0 0 1.5rem;
    text-align: center;
}

.skills-box .skills-content {
    position: relative;
    -webkit-box-shadow: 18px 18px 46px 12px rgba(0,0,0,0.40);
    -moz-box-shadow: 18px 18px 46px 12px rgba(0,0,0,0.40);
    box-shadow: 18px 18px 46px 12px rgba(0,0,0,0.40);
    border-radius: .6rem;
    padding: .5rem 1.5rem;
    z-index: 1;
    overflow: hidden;
}

.skills-box .skills-content::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 0;
    height: 100%;
    background: rgb(23, 31, 45, .50);
    z-index: -1;
    transition: .3s;
}

.skills-box .skills-content:hover::before {
    width: 100%;
}

/* SKILLS BAR */
.skills-content .progress {
    padding: 1rem 0;
}

.skills-content .progress h3 {
    font-size: 1.7rem;
    display: flex;
    align-items: center;
    font-family: 'Kanit', sans-serif;
}

.skills-content .progress h3 img {
    width: 3rem;
    margin-right: 10px;
}

.skills-content .progress h3 span {
    color: var(--TextColor);
    margin-left: auto;
}

.skills-content .progress .bar {
    height: 2rem;
    border: .2rem solid var(--TextColor);
    border-radius: .6rem;
    padding: .3rem;
    margin: 1rem 0;
}

.skills-content .progress .bar span {
    display: block;
    height: 100%;
    border-radius: .3rem;
    background: var(--TextColor);
    transition: .3s;
    width: var(--w);
}

<section class="skills" id="page3">
    <h2 class="heading">My <span>Skills</span></h2>
    <div class="skills-row">
        <div class="skills-column">
            <h3 class="title">front-end</h3>
            <div class="skills-box">
                <div class="skills-content">
                    <div class="progress">
                        <h3><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg"> HTML <span>80%</span></h3>
                        <div class="bar"><span style="--w:80%" data-width="80"></span></div>
                    </div>
                    <div class="progress">
                        <h3><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg"> CSS <span>90%</span></h3>
                        <div class="bar"><span style="--w:90%" data-width="90"></span></div>
                    </div>
                    <div class="progress">
                        <h3><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg"> JavaScript <span>50%</span></h3>
                        <div class="bar"><span style="--w:50%" data-width="50"></span></div>
                    </div>
                    <div class="progress">
                        <h3><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg"> React.js <span>30%</span></h3>
                        <div class="bar"><span style="--w:30%" data-width="30"></span></div>
                    </div>
                </div>
            </div>
        </div>
        <div class="skills-column">
            <h3 class="title">back-end</h3>
            <div class="skills-box">
                <div class="skills-content">
                    <div class="progress">
                        <h3><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg"> PHP <span>75%</span></h3>
                        <div class="bar"><span style="--w:75%" data-width="75"></span></div>
                    </div>
                    <div class="progress">
                        <h3><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg"> Node.js <span>54%</span></h3>
                        <div class="bar"><span style="--w:54%" data-width="54"></span></div>
                    </div>
                    <div class="progress">
                        <h3><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg"> Java <span>48%</span></h3>
                        <div class="bar"><span style="--w:48%" data-width="48"></span></div>
                    </div>
                    <div class="progress">
                        <h3><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg"> C++ <span>40%</span></h3>
                        <div class="bar"><span style="--w:40%" data-width="40"></span></div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

## 🔗Links
[![Instagram](https://img.shields.io/badge/Follow%20on%20Instagram-%23E4405F.svg?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/zaxe.jm/)
