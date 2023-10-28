
IMG_20231027_183934.jpg

<html>
    <head>
        <title>Digital Portfolio</title>
        <style>
         body   {
                font-family: Arial, 'Times-New Roman';
                margin: 0;
                padding: 0;
                background-color: white;
            }
            header {
                background-color: #5f0f40;
                color: white;
                text-align: center;
                padding: 2rem 0;
                position: relative; /* Add this */
            }

            .header-content h1 {
                font-size: 2.5rem;
            }
            /* Add syles for the round profile picture */
            .profile-picture {
                width: 100px; /*Adjust the size as needed */
                height: 100px;
                border-radius: 75%; /* create a circular shape */
                object-fit: cover; /*To ensure the image fills the circular area */
                position: absolute; /* Add this */
                top: 75px; /*Adjust top position as needed */
                left: 75px; /*Adjust left position as needed */
            }
            nav {
                background-color: #5f0f40;
                color: whitesmoke;
                text-align: center;
            }

            nav u1 {
                list-style-type:circle;
                padding: 0;
            }

            nav ul li {
                display: inline;
                margin: 0 20px;
            }

            nav ul li a {
                text-decoration: none;
                color: white;
            }
            .section-content {
                background-color: white;
                padding: 2rem;
                margin: 1rem;
                border-radius: 20px;
                box-shadow: 0 0 10px rgb(73, 16, 31);
            }

            .download-button {
                background-color: rgb(197, 31, 31);
                color: #fff;
                padding: 0.5rem 1rem;
                text-decoration:  none;
                border-radius: 20px;
                display: inline-block;
                margin-top: 10px;
            }

            .download-button:hover{
                background-color: white;
            }

            footer {
                text-align: center;
                padding: 1rem 0;
                background-color: #333;
                color:#fff
            }

            ul {
                list-style-type: disc;
                padding-left: 20px;
            }
        </style>
    </head>
    <body>
        <header>
            <div class="header-content">
                <!--Add your profile picture here-->
                <img src="" alt="" class="">
                <h1>suvathi</h1>
                <p>I'm webdesigner</p>
            </div>
        </header>

        <nav>
            <u1>
                <li><a href="#about">About</a></li>
                <li><a href="#Skills">Skills</a></li>
                <li><a href="#Education">Education</a></li>
                <li><a href="#Contact">Contact</a></li>
            </u1>
        </nav>

        <section id="about">
            <div class="section-content">
                <h2>About Me</h2>
<p>Hello Everyone! I'm suvathi p I'm Final Year Undergraduate student in computer Application. <br> Having Knowledge in computer languages(C,C++,Java,SQL),photoshop. <br> Future Software programming and Web design specialist.</p>
            </div>
        </section>

        <section id="Skills">
            <div class="section-content">
                <h2>Skills</h2>
                <u1>
                    <li>Programming</li>
                    <li>Photoshop</li>
                    <li>Flash</li>
                    <li>Web Design</li>
                </u1>
            </div>
            </section>

            <section id="Education">
                <div class="section-content">
                    <h2>Education:</h2>
                    <ul>
                        <li>2021-2024 <br> Bachelor of Computer Appplication</li>
                        <li>Idhaya College For Women, <br> Bharathidasan University, <br> Kumbakonam-Tamilnadu</li>
                        <li>2020-2021, <br> Higher Secondary</li>
                        <li>Rice city, <br> Matric Higher Secondary School, <br> Aduthurai-Tamilnadu </li>
                    </ul>
                </div>
            </section>

            <section id="contact">
                <div class="section-content">
                    <h2>contact</h2>
                    <form>
                    <label for="email">Email</label>
                    <input type="text" id="email"> <br> <br>
                    <label for="number">Number</label>
                    <input type="number" id="number"> <br> <br>
                    <label for="Address">Address</label>
                    <input type="text" id="Address">
                </form>
              </div>
              </section>

         <footer>
                <p>&copy; 2023 suvathi</p>
        </footer>
    </body>
</html>
