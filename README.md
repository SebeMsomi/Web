<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <link rel="stylesheet" href="C:\Users\Sebza\Desktop\Personal Website\css\style.css">

    <!-- =====BOX ICONS===== -->
    <link href='https://cdn.jsdelivr.net/npm/boxicons@2.0.5/css/boxicons.min.css' rel='stylesheet'>

    <title>Sebe Msomi's Portfolio</title>
</head>
<body>
    <!--===== HEADER =====-->
    <header class="l-header">
        <nav class="nav bd-grid">
            <div>
                <a href="#" class="nav__logo">Sebe</a>
            </div>

            <div class="nav__menu" id="nav-menu">
                <ul class="nav__list">
                    <li class="nav__item"><a href="#home" class="nav__link active">Home</a></li>
                    <li class="nav__item"><a href="#about" class="nav__link">About</a></li>
                    <li class="nav__item"><a href="#skills" class="nav__link">Skills</a></li>
                    <li class="nav__item"><a href="#work" class="nav__link">Work</a></li>
                    <li class="nav__item"><a href="#contact" class="nav__link">Contact</a></li>
                </ul>
            </div>

            <div class="nav__toggle" id="nav-toggle">
                <i class='bx bx-menu'></i>
            </div>
        </nav>
    </header>

    <main class="l-main">
        <!--===== HOME =====-->
        <section class="home bd-grid" id="home">
            <div class="home__data">
                <h1 class="home__title">Hello world,<br>I'am <span class="home__title-color">Sebe Msomi </span><br> Software Developer</h1>

                <a href="#contact" class="button">Contact</a>
            </div>

            <div class="home__social">
                <a href="https://www.linkedin.com/in/sebe-msomi-ba81aa169/" class="home__social-icon"><i class='bx bxl-linkedin'></i></a>
              <!---- <a href="" class="home__social-icon"><i class='bx bxl-behance'></i></a> -->
                <a href="https://www.Github.com/sebemsomi/" class="home__social-icon"><i class='bx bxl-github'></i></a>
            </div>

            <div class="home__img">
                <img src="C:\Users\Sebza\Desktop\Personal Website\images/sw.jpg" width="auto" height="auto" alt="sebe">
            </div>
        </section>

        <!--===== ABOUT =====-->
        <section class="about section " id="about">
            <h2 class="section-title">About</h2>

            <div class="about__container bd-grid">
                <div class="about__img">
                    <img src="C:\Users\Sebza\Desktop\Personal Website\images/seb.jpg" alt="">
                </div>

                <div>
                    <h2 class="about__subtitle">I'am Sebe</h2>
                    <p class="about__text">
                        I was born in 1994. I live in Cape Town and work as a Software Developer.
                        I’ve been a professional developer for more than 8 months.

                        I’ve mostly worked with Java Spring Frameworks, Microsoft PowerApps, NoSQL,
                        HTML, CSS, JavaScript and Android but also a little bit with Python, C# and PHP.

                    </p><br />
                    <p class="about__text">
                        <b> I like building new stuff and work with other people – nothing really fascinating is ever built alone</b>

                    </p><br/>
                        <h3>My main interests are: </h3>
                        <p>
                            – Software architecture<br />
                            – C#<br />
                            – Distributed Systems<br />
                            – Java/JVM/Kotlin<br />
                            – Python<br />
                            – Machine Learning<br />
                            – Artificial Intellegence<br />
                            – Reactive Programming<br />
                            – Learning new programming languages<br />
                        </p>

                </div>
            </div>
        </section>

        <!--===== SKILLS =====-->
        <section class="skills section" id="skills">
            <h2 class="section-title">Skills</h2>

            <div class="skills__container bd-grid">
                <div>
                    <h2 class="skills__subtitle">Profesional Skills</h2>
                    <p class="skills__text" Created multiple web apps starting with requirements gathering, designing, developing,
                       refactoring, and code implementation</p>
                    <div class="skills__data">
                        <div class="skills__names">
                            <i class='bx bxl-html5 skills__icon'></i>
                            <span class="skills__name">HTML5</span>
                        </div>
                        <div class="skills__bar skills__html">

                        </div>
                        <div>
                            <span class="skills__percentage">95%</span>
                        </div>
                    </div>
                    <div class="skills__data">
                        <div class="skills__names">
                            <i class='bx bxl-Java skills__icon'></i>
                            <span class="skills__name">Java</span>
                        </div>
                        <div class="skills__bar skills__html">

                        </div>
                        <div>
                            <span class="skills__percentage">85%</span>
                        </div>
                    </div>
                    <div class="skills__data">
                        <div class="skills__names">
                            <i class='bx bxl-MS powerapps skills__icon'></i>
                            <span class="skills__name">MS PowerApps</span>
                        </div>
                        <div class="skills__bar skills__html">

                        </div>
                        <div>
                            <span class="skills__percentage">65%</span>
                        </div>

                    </div>
                    <div class="skills__data">
                        <div class="skills__names">
                            <i class='bx bxl-css3 skills__icon'></i>
                            <span class="skills__name">CSS3</span>
                        </div>
                        <div class="skills__bar skills__css">

                        </div>
                        <div>
                            <span class="skills__percentage">85%</span>
                        </div>
                    </div>
                    <div class="skills__data">
                        <div class="skills__names">
                            <i class='bx bxl-android skills__icon'></i>
                            <span class="skills__name">Android Applications</span>
                        </div>
                        <div class="skills__bar skills__html">

                        </div>
                        <div>
                            <span class="skills__percentage">75%</span>
                        </div>
                    </div>
                    <div class="skills__data">
                        <div class="skills__names">
                            <i class='bx bxl-javascript skills__icon'></i>
                            <span class="skills__name">JAVASCRIPT</span>
                        </div>
                        <div class="skills__bar skills__js">

                        </div>
                        <div>
                            <span class="skills__percentage">65%</span>
                        </div>
                    </div>
                    <div class="skills__data">
                        <div class="skills__names">
                            <i class='bx bxs-paint skills__icon'></i>
                            <span class="skills__name">UX/UI</span>
                        </div>
                        <div class="skills__bar skills__ux">

                        </div>
                        <div>
                            <span class="skills__percentage">75%</span>
                        </div>
                    </div>
                </div>

                <div>
                    <img src="C:\Users\Sebza\Desktop\Personal Website\images/sx.jpg" width =" auto" height =" auto"alt="" class="skills__img">

                </div>
            </div>
        </section>

        <!--===== WORK =====-->
        <section class="work section" id="work">
            <h2 class="section-title">Work</h2>

            <div class="work__container bd-grid">
                <div class="work__img">
                    <img src="C:\Users\Sebza\Desktop\Personal Website\images/p.png" alt="">
                </div>
                <div class="work__img">
                    <img src="C:\Users\Sebza\Desktop\Personal Website\images/d.jpg" alt="">
                </div>
                <div class="work__img">
                    <img src="C:\Users\Sebza\Desktop\Personal Website\images/ses.jpg" alt="">
                </div>
                <div class="work__img">
                    <img src="C:\Users\Sebza\Desktop\Personal Website\images/sws.png" alt="">
                </div>
                <div class="work__img">
                    <img src="C:\Users\Sebza\Desktop\Personal Website\images/ma.png" alt="">
                </div>
                <div class="work__img">
                    <img src="C:\Users\Sebza\Desktop\Personal Website\images/work6.jpg" alt="">
                </div>
            </div>
        </section>

        <!--===== CONTACT =====-->
        <section class="contact section" id="contact">
            <h2 class="section-title">Contact</h2>

            <div class="contact__container bd-grid">
                <form action="" class="contact__form">
                    <input type="text" placeholder="Name" class="contact__input">
                    <input type="mail" placeholder="Email" class="contact__input">
                    <textarea name="" id="" cols="0" rows="10" class="contact__input"></textarea>
                    <input type="button" value="Submit" class="contact__button button">
                </form>
            </div>
        </section>
    </main>

    <!--===== FOOTER =====-->
    <footer class="footer">
        <p class="footer__title">Sebe Msomi</p>
        <div class="footer__social">
            <a href="https://www.Facebook.com/sebemsomi/" class="footer__icon"><i class='bx bxl-facebook'></i></a>
            <a href="https://www.Instagram.com/sebemsomi/" class="footer__icon"><i class='bx bxl-instagram'></i></a>
            <a href="https://www.Twitter.com/sebemsomi/" class="footer__icon"><i class='bx bxl-twitter'></i></a>
        </div>
        <p>&#169; 2020 copyright all right reserved</p>
    </footer>


    <!--===== SCROLL REVEAL =====-->
    <script src="https://unpkg.com/scrollreveal"></script>

    <!--===== MAIN JS =====-->
    <script src="C:\Users\Sebza\Desktop\Personal Website/main.js"></script>
</body>
</html>
