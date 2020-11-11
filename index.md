<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <title>Luc Heaton</title>
        <script src="https://kit.fontawesome.com/06c0747e2d.js" crossorigin="anonymous"></script>
        <link rel="stylesheet" href="styles.css">
        <link rel="icon" type="image/png" sizes="32x32" href="favicon-32.png">
        <link rel="icon" type="image/png" sizes="16x16" href="favicon-16.png">
    </head>
    <body>

        <header>
            <a class="header-item" href="index.md#portfolio">portfolio</a>
            <a class="divider"> / </a>
            <a class="header-item" href="index.md#experience">experience</a>
            <a class="divider"> / </a>
            <a class="header-item" href="index.md#about">about</a>
            <a class="divider"> / </a>
            <a class="header-item" href="index.md#contact">contact</a>
            <div>
                <div id="progBar"></div>
            </div>
        </header>

        <div class="social-bar">
            <div><a href="https://github.com/Luuccc"><i class="fab fa-github"></i></a></div>
            <div><a href="https://twitter.com/HeatonLuc"><i class="fab fa-twitter"></i></a></div>
            <div><a href="mailto:luc@lucheaton.com"><i class="fas fa-envelope"></i></a></div>
        </div>

        <div class="main-container">
            <section>

                <div class="title-container">
                    <h1>Luc Heaton</h1>
                    <h2><u>Programmer</u></h2>
                </div>

                <div class="short-info ">
                    <p>Hi, I'm Luc, a programmer of things.<br><br>I build programs for AVR microcontrollers, produce small<br>desktop / terminal applications, sometimes the odd<br>little game, and everything in between.<p>
                    <table>
                        <tr>
                            <td>
                                <div>
                                    <canvas id="canvas-grid" width="200" height="200">Your browser does not support the canvas element.</canvas>
                                </div>
                                <div class="sub-container">
                                    <button onclick="Draw()" type="button">Generate</button>
                                </div>
                            </td>
                        </tr>
                    </table>
                </div>
            </section>

            <section id="portfolio">

                <div class="section-header">
                    <h3><u>.portfolio</u></h3>
                    <p>Some projects I'd like to give attention to</p>
                </div>

                <div class="project">
                    <a target="_blank" href="https://www.hiveindustries.com/audio-products-menu/product/115-cio2/category_pathway-23.html" >
                        <img src="images/CIO2.jpg">
                    </a>
                    <h3>Featured Project</h3>
                    <h2>VU Meter</h2>
                    <p>Developed the code for a VU Meter representing a signal level between -40dB and -2dB through Charlieplexed LEDs, which can be seen on the CiO² product from Hive Industries.</p>
                    <h4>C AVR  16/12/2018</h4>
                </div>
                <div class="project">
                    <a>
                        <img src="images/Stack.jpg">
                    </a>
                    <h3>Featured Project</h3>
                    <h2>Stackoverflow feed</h2>
                    <p>While trying to be somewhat helpful on Stackoverflow, I didn't want to sit on the webpage refreshing every so often, looking for questions that I might be able to answer.<br><br>
                        So I developed a small Winforms application that displays the latest questions under a given tag, as links to the web post. Refreshing every five minutes, grabbing entries from the RSS feed.</p>
                    <h4>C# Winforms  15/09/2020</h4>
                </div>
                <div class="project">
                    <a target="_blank" href="https://github.com/Luuccc/PythonScrabble" >
                        <img src="images/Scrabble.jpg">
                    </a>
                    <h3>Featured Project</h3>
                    <h2>Text-based Scrabble</h2>
                    <p>An ASCII recreation of the board game Scrabble, developed for my A-Level Computer Science coursework.<br><br>Including: Premium scoring cells, Horizontal and vertical placement,
                        Blank tiles, A dictionary validation check around the letter(s) placement, Multi-word scoring, and more</p>
                    <h4>Python  16/12/2018</h4>
                </div>
                <div class="project">
                    <a>
                        <img src="images/DBot.jpg">
                    </a>
                    <h3>Featured Project</h3>
                    <h2>Discord Bot</h2>
                    <p>I built a small bot for the messaging/VoIP application Discord, that would allow me to add some extra features to the server, that me and my friends share.<br><br>
                        It works by responding to defined commands, such as the command diceroll, with a forward-slash command prefix, entering this will simply return a number between one and six. <br><br>
                        To add some progression to the bot, I implemented a load/save system, storing data with a JSON file. Doing this allowed me to keep track of a virtual currency which led to the addition of
                        a roulette roll, a coinflip, a leaderboard. As well as a case opening clone from the game CSGO, which allows a player to open a "case" using virtual currency, storing the unboxed item of varying quality within their
                        inventory, which can then be sold, or kept. For this bot to work however, it relied on my computer running. So naturally, I moved the bot onto a RaspberryPI which I could then leave on almost 24/7.</p>
                    <h4>Python RaspberryPI Json  26/09/2018</h4>
                </div>

                <div class="project-extra">
                    <h4>The other things</h4>
                    <a class="vault-link" href="vault.md"><u>View the vault</u></a>
                    <div class="grid">
                        <div class="mini-project">
                            <span><i class="far fa-sticky-note"></i></span>
                            <div class="mini-data">
                                <h2>AutoTagger</h2>
                                <p>Cycle through audio files within a directory, correctly assigning ID3 metadata by comparing artist name(s) against a JSON file, which grows dynamically with each new artist it encounters. Used for clear formatting when using media players.</p>
                                <h4>Python Json  09/07/2019</h4>
                            </div>
                        </div>
                        <div class="mini-project">
                            <span><i class="far fa-sticky-note"></i></span>
                            <div class="mini-data">
                                <h2>TFT LCD text</h2>
                                <p>Building upon a standard graphics library for a series of displays, I built a method of drawing character arrays to the screen, taking into account font size, and character spacing, as well as a horizontal aligner, that centers a rect, based on the display width.</p>
                                <h4>C Arduino  01/03/2020</h4>
                            </div>
                        </div>
                        <div class="mini-project">
                            <span><i class="far fa-sticky-note"></i></span>
                            <div class="mini-data">
                                <h2>M3U Creator</h2>
                                <p>A small program that webscapes title names from a youtube playlist, matching it to a file name within a directory. Building up an M3U file following the same order as the youtube playlist.</p>
                                <h4>Python  15/06/2019</h4>
                            </div>
                        </div>
                        <div class="mini-project">
                            <span><i class="far fa-sticky-note"></i></span>
                            <div class="mini-data">
                                <h2>NodeJS UDP</h2>
                                <p>A small dive into understanding the UDP protocol, sending and recieving small amounts of data to/from local and remote servers</p>
                                <h4>NodeJS  20/02/2020</h4>
                            </div>
                        </div>
                    </div>
                </div>
            </section>

            <section id="experience">
                <div class="section-header">
                    <h3><u>.experience</u></h3>
                    <p>Areas of gained knowledge that can be categorised</p>
                </div>
                <div>
                    <div class="entry exp-info">
                        <button type="button" onClick="ToggleDesc(this)"><i class="fas fa-caret-right"></i>Hive Industries<i class="fas fa-caret-down"></i></button>
                        <div>
                            <p><i class="fas fa-caret-right"></i>Developing the functionality of microcontrollers for prototypes and products</p>
                            <p><i class="fas fa-caret-right"></i>Designing the user interfaces for products incorporating a Nextion display</p>
                            <p><i class="fas fa-caret-right"></i>Lots of discussion and adaptation during the development process</p>
                            <span>2019-Present</span>
                        </div>
                    </div>
                    <div class="entry exp-info">
                        <button type="button" onClick="ToggleDesc(this)"><i class="fas fa-caret-right"></i>Switch Computer Support<i class="fas fa-caret-down"></i></button>
                        <div>
                            <p><i class="fas fa-caret-right"></i>Lots of general computer support incorporating the mystical "PC Medical"</p>
                            <p><i class="fas fa-caret-right"></i>Learnt how to replace faulty components within some phones and tablets</p>
                            <p><i class="fas fa-caret-right"></i>Did a small amount of customer interaction at the desk</p>
                            <p><i class="fas fa-caret-right"></i>Of course providing the essential tea and coffees, when needed most</p>
                            <p><i class="fas fa-caret-right"></i>Meeting Richard whom of which I learnt alot about web dev from, who can be found at <a href="http://handcoded.co.uk/">handcoded.co.uk</a></p>
                            <span>2017-2018</span>
                        </div>
                    </div>
                    <div class="entry exp-info">
                        <button type="button" onClick="ToggleDesc(this)"><i class="fas fa-caret-right"></i>Local computer support<i class="fas fa-caret-down"></i></button>
                        <div>
                            <p><i class="fas fa-caret-right"></i>Helping friends and family with building computers, giving recommendations and advice</p>
                            <p><i class="fas fa-caret-right"></i>Small repairs on general devices, hardware or software</p>
                            <span>2016-Present</span>
                        </div>
                    </div>
                </div>
            </section>

            <section id="about">

                <div class="section-header">
                    <h3><u>.about</u></h3>
                    <p>A little bit about myself</p>
                </div>

                <div class="about-me">
                    <div class="about-data">
                        <p>I guess one way that you could put it, is that I enjoy making things work, whether it's a microcontroller,
                            a small desktop application, a website (like this one), or even the odd little game.
                            I also do enjoy drawing things, but for the most part it's of circuit diagrams and ideas<br><br>
                            Since a young age I've enjoyed using my knowledge to try and resolve computing and electrical issues,
                            although it's safe to say I'm much better at it now, than I used to be.<br><br>
                            Some of the languages that I'm currently comfortable with include:
                        </p>
                        <div class="languages">
                            <p><i class="fas fa-caret-right"></i>C</p>
                            <p><i class="fas fa-caret-right"></i>C#</p>
                            <p><i class="fas fa-caret-right"></i>Python</p>
                            <p><i class="fas fa-caret-right"></i>HTML & CSS</p>
                        </div>
                        <p>During my further schooling I studied:</p>
                        <div class="languages">
                            <p><i class="fas fa-caret-right"></i>Computer Science</p>
                            <p><i class="fas fa-caret-right"></i>Digital Illustration</p>
                            <p><i class="fas fa-caret-right"></i>Physics</p>
                        </div>
                    </div>
                    <img src="images/drawn-me.png">
                </div>

            </section>

            <section id="contact">

                <div class="section-header">
                    <h3><u>.contact</u></h3>
                    <p>If you would like to get hold of me, <br>you can reach me at my inbox below</p>
                </div>

                <div class="contact-me">
                    <a href="mailto:luc@lucheaton.com">Contact Me</a>
                </div>

            </section>

            <footer>
                <p>Designed and Built by Luc Heaton</p>
            </footer>
        </div>

        <script>
            window.onscroll = function() {Progress()};

            function Progress() {
                var winScroll = document.body.scrollTop || document.documentElement.scrollTop;
                var height = document.documentElement.scrollHeight - document.documentElement.clientHeight;
                var scrolled = (winScroll / height) * 100;
                document.getElementById("progBar").style.width = scrolled + "%";
            }
        </script>

        <script>
            function ToggleDesc(ref){
                var content = ref.nextElementSibling;
                if (content.style.display === "block") {
                    content.style.display = "none";
                } else {
                    content.style.display = "block";
                }
            }
        </script>

        <script>
            var size = 200;
            var fillAmount = 200;
            function Draw()
            {
                let startPos = [size/2,size/2];
                var canvas = document.getElementById("canvas-grid");
                var ctx = canvas.getContext("2d");
                ctx.clearRect(0, 0, canvas.width, canvas.height);
                ctx.fillStyle = "#f97979";
                for (var i = 0; i < fillAmount; i++)
                {
                    ChangeDir(startPos);
                    ctx.fillRect(startPos[0],startPos[1],10,10);
                }
            }
            function ChangeDir(i){var a=Math.floor(21*Math.random());a<5?i[0]==size-10?i[0]=0:i[0]+=10:a<10?0==i[0]?i[0]=size-10:i[0]-=10:a<15?i[1]==size-10?i[1]=0:i[1]+=10:0==i[1]?i[1]=size-10:i[1]-=10}
        </script>
    </body>
</html>
