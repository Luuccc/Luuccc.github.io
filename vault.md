<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <title>Luc Heaton</title>
        <script src="https://kit.fontawesome.com/06c0747e2d.js" crossorigin="anonymous"></script>
        <link rel="stylesheet" href="styles.css">
        <script>
			function ToggleDesc(ref)
			{
				var content = ref.nextElementSibling;
				if (content.style.display === "block") {
					content.style.display = "none";
				} else {
					content.style.display = "block";
				}
			}
		</script>
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

            <section id="vault">

                <div class="section-header">
                    <h3><u>.vault</u></h3>
                    <p>Just a long list of things I've been up to (some with images)</p>
                </div>

                <div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>26/10/2020<span>]</span> SSD1306 <i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">
                            <p>Just more styling while populating the website with STUFF, although alot of cleaning up can be done</p>
                            <span>HTML & CSS</span>
                            <span>JS</span>
                            <span>Myself</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>17/10/2020<span>]</span> Almost finished populating this site<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">
                            <p>Just more styling while populating the website with STUFF, although alot of cleaning up can be done</p>
                            <span>HTML & CSS</span>
                            <span>JS</span>
                            <span>Myself</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>16/10/2020<span>]</span> Brought Discord bot back to life<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">
                            <img src="images/DBot.jpg">

                            <p>The version of Python that this bot was build on is nolonger supported by the discord module. Also the JSON file saves were nolonger compatible. I may rebuild this at some point,
                                as a lot of the old methods I've used are outdated</p>
                            <span>Python</span>
                            <span>Json</span>
                            <span>Myself</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>01/08/2020<span>]</span> Steam library sorting<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">
                            <img src="images/SteamSize.JPG">

                            <p>As the Steam library doesn't support the sorting of uninstalled games, I sorted through the XML from the Steam Web API, visualising the data with a csv file</p>
                            <span>Python</span>
                            <span>Myself</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>04/10/2020<span>]</span> Ebook name formatting<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">

                            <p>When downloading my ebooks, the file name is rarly formatted correctly. So I built a small utility to cleanup the title name within certain ebook readers</p>
                            <span>Python</span>
                            <span>Myself</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>23/09/2020<span>]</span> Nintendo DS Lite power switch<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">
                            <img src="images/DS.JPG">

                            <p>I recently replaced a faulty Nintendo DS Lite power switch for my cousin, as the switch mechanism had snapped</p>
                            <span>Electronics</span>
                            <span>Myself</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>04/07/2020<span>]</span> Terminal Access Minigame<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">
                            <img src="images/TA.JPG">

                            <p>Not being able todo very much with my not-so-great internet connection, I decided to recreate the terminal hacking minigame from Fallout 4 for my phone.
                                I ended up building a version that took most of the visuals, but scored slightly differently to the original game (which was a bad idea), scoring two
                                points for the guessed word containing a correct letter in the correct position, and one point for containing a correct letter, but not in the right spot.
                                In short, it was more confusing, and less intuative than the original.</p>
                            <span>C#</span>
                            <span>Unity</span>
                            <span>Myself</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>14/09/2020<span>]</span> Stackoverflow feed app<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">
                            <img src="images/Stack.gif">

                            <p>While trying to be somewhat helpful on Stackoverflow, I didn't want to sit on the webpage refreshing every so often, looking for questions that I might be able to answer.<br><br>
                                So I developed a small Winforms application that displays the latest questions under a given tag, as links to the web post. Refreshing every five minutes, grabbing entries from the RSS feed.
                                I may build upon this with extra info like views, votes, etc, as well as other features like page navigation</p>
                            <span>Winforms</span>
                            <span>C#</span>
                            <span>Myself</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>05/05/2020<span>]</span> NoteTaking app<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">
                            <img src="images/Note.JPG">
                            <img src="images/ListNotes.jpg">

                            <p>I thought it might be a nice idea to create a simple sort-of diary console application, which can take in a new note (some text, datetime, and a bit of data), storing it within a JSON file,
                                which can also then be deserialised, formatted and displayed on screen. Also with the option to display notes by a specific month / year / all, also crudely adding it as an autoexec at a set
                                time everyday through Task Scheduler</p>
                            <span>C#</span>
                            <span>Visual Studio</span>
                            <span>Myself</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>09/08/2020<span>]</span> Comms over USB to Arduino<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">

                            <p>Just wanted to experiment with serial data transfer over USB, which may be useful for future ideas</p>
                            <span>C#</span>
                            <span>Electronics</span>
                            <span>Myself</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>08/07/2020<span>]</span> Mastermind game<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">

                            <p>Hearing how similar this old board game is to Fallout's terminal minigame, I decided to also recreate a version of it as a console application, to give it a try</p>
                            <span>C#</span>
                            <span>Visual Studio</span>
                            <span>Myself</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>09/03/2020<span>]</span> ASCII heightmaps<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">

                            <p>While playing around with generating heightmaps based on surrounding cells, I ended up building what I thought was a nice little pattern generator. Which I ended up moving over to Javascript to
                                be embeded within my site</p>
                            <span>Python</span>
                            <span>JS</span>
                            <span>Myself</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>03/07/2020<span>]</span> Thaumcraft solver<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">
                            <img src="images/Thaum.jpg">

                            <p>While playing a little bit of some old school Modded Minecraft, you come across a mod named Thaumcraft, where a main mechanic is linking "Aspects" which can only connect to a specific set of
                                other Aspects, to progress through the mod. So naturally I built a small application that finds all (most) connections that can be made, from the starting to an ending Aspect</p>
                            <span>C#</span>
                            <span>Visual Studio</span>
                            <span>Myself</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>11/05/2020<span>]</span> Desktop VU Meter<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">
                            <img src="images/DesktopVU.JPG">
                            <img src="images/DesktopVU1.JPG">

                            <p>Produced a prototype version of a desktop VU Meter, which monitors multiple devices (current limit of 5) at once, scaling the form accordingly, with the options to add / remove monitors, and clear all</p>
                            <span>C#</span>
                            <span>Winforms</span>
                            <span>Myself</span>
                        </div>
                    </div>

                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>16/09/2020<span>]</span> Battery Tester<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">
                            <img src="images/Charlieplex.jpg">
                            <img src="images/Charlieplex1.jpg">

                            <p>I created a Charlieplexed indicator script to display the status of a battery. Instead of recreating the circuit every time on a breadboard, I finally built a perfboard version</p>
                            <span>C</span>
                            <span>Arduino</span>
                            <span>Electronics</span>
                            <span>Hive Industries</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>08/21/2020<span>]</span> Door Count<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">

                            <p>I built a script for an AVR microcontroller reading in sensor data, to determine the number of people within a building, indicated through a UART interface. Also with an adjustable limit of customers</p>
                            <span>C</span>
                            <span>AVR</span>
                            <span>Arduino</span>
                            <span>Hive Industries</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>06/03/2020<span>]</span> RSSI Signal Strength<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">

                            <p>Calling for an interupt from the device, then asking for the signal strength value, using SPI. Indicating the current signal strength value with an LCD display</p>
                            <span>C</span>
                            <span>Arduino</span>
                            <span>Hive Industries</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>01/03/2020<span>]</span> TFT LCD text<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">

                            <p>Building upon a standard graphics library for a series of displays, I built a method of drawing character arrays to the screen, taking into account font size, and character spacing, as well as a horizontal
                                aligner, that centers a rect, based on the display width.</p>
                            <span>C</span>
                            <span>Arduino</span>
                            <span>Myself</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>29/02/2020<span>]</span> Shutdown Recovery<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">

                            <p>If the PWR line goes LOW due to an external sleep function, indicate this event, and restart the device. Otherwise, indicate the device is powered up with a heartbeat effect</p>
                            <span>C</span>
                            <span>Arduino</span>
                            <span>Electronics</span>
                            <span>Hive Industries</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>24/02/2020<span>]</span> Looking into Companion<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">

                            <p>As an extra feature of the MC7, it would be nice to control it from a local StreamDeck, for example. Which would be possible by creating a module for the Companion app</p>
                            <span>Javascript</span>
                            <span>Hive Industries</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>23/02/2020<span>]</span> Pesky RGB565<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">

                            <p>After being unable to correctly colour a certain display, I learnt that the display relied on the RGB565 byte format:/</p>
                            <span>C</span>
                            <span>Arduino</span>
                            <span>Hive Industries</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>22/02/2020<span>]</span> Drawing to a TFT display<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">

                            <p>Learning the basics of the SPI interface to communicate to the display</p>
                            <span>C</span>
                            <span>Arduino</span>
                            <span>Myself</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>20/02/2020<span>]</span> NodeJS UDP<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">

                            <p>A small dive into understanding the UDP protocol, sending and recieving small amounts of data to/from local and remote servers</p>
                            <span>NodeJS</span>
                            <span>Myself</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>23/01/2020<span>]</span> MC7 prototype pages<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">

                            <p>For the upcoming exhibition, I designed and produced the pages that would be the base of the MC7 interface. After many iterations, a preffered style, and layout
                                for an early version of the MC7 display was produced, ready from its first showing</p>
                            <span>Artwork</span>
                            <span>Nextion</span>
                            <span>Hive Industries</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>31/12/2019<span>]</span> More web scrapers<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">

                            <p>Picking up more of an understanding on web scraping. Involving grabbing data from webpages, to populate spreadsheets with data and images</p>
                            <span>Python</span>
                            <span>Myself</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>23/11/2019<span>]</span> A first with rotary encoders<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">

                            <p>Learning the fundamentals of interpretting the rotation of an encoder</p>
                            <span>C</span>
                            <span>Arduino</span>
                            <span>Electronics</span>
                            <span>Myself</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>01/10/2019<span>]</span> A quick look at Ultrasound<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">

                            <p>Decided to have a look at the HC-SR04, to calculate distances to nearby objects</p>
                            <span>C</span>
                            <span>Arduino</span>
                            <span>Myself</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>24/06/2019<span>]</span> Nextion Countdown Touch<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">
                            <img src="images/Countdown.JPG">

                            <p>Building upon other projects from Hive Industries, I produced a combination of features. Incorporating the digit shift module I produced, and timer input, as well as my page designs for the Nextion </p>
                            <span>C</span>
                            <span>Arduino</span>
                            <span>Nextion</span>
                            <span>Hive Industries</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>19/06/2019<span>]</span> Nextion touchscreen displays<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">

                            <p>Moving away from just text elements, I learnt how to build images, and interactive elements (that listen for touch events) into the display</p>
                            <span>Nextion</span>
                            <span>Myself</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>26/09/2019<span>]</span> Building a Discord bot<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">
                            <img src="images/DBot.jpg">

                            <p>I built a small bot for the messaging/VoIP application Discord, that would allow me to add some extra features to the server, that me and my friends share.
                                It works by responding to defined commands, such as the command diceroll, with a forward-slash command prefix, entering this will simply return a number between one and six.
                                To add some progression to the bot, I implemented a load/save system, storing data with a JSON file. Doing this allowed me to keep track of a virtual currency which led to the
                                addition of a roulette roll, a coinflip, a leaderboard. As well as a case opening clone from the game CSGO, which allows a player to open a "case" using virtual currency, storing
                                the unboxed item of varying quality within their inventory, which can then be sold, or kept. For this bot to work however, it relied on my computer running. So naturally, I moved
                                the bot onto a RaspberryPI which I could then leave on almost 24/7.</p>
                            <span>Python</span>
                            <span>RaspberryPI</span>
                            <span>Json</span>
                            <span>Myself</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>26/09/2019<span>]</span> Colonists minigame<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">
                            <img src="images/Castle.gif">
                            <img src="images/Castle1.gif">
                            <img src="images/Castle2.gif">
                            <img src="images/Castle3.gif">
                            <img src="images/Castle4.gif">

                            <p>I didn't really have a plan for this. I just wanted to build a colony game where you manage little people, with opposing faction(s). You're able to select a member from your faction,
                                then click a position for them to move towards, or select a resource for them to gather. If they come within a vision range of the enemy faction the two colonists will "battle"
                                (currently bumping eachother to the death)</p>
                            <span>C#</span>
                            <span>Unity</span>
                            <span>MagicaVoxel</span>
                            <span>Myself</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>03/08/2019<span>]</span> The nRF24L01<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">

                            <p>For my first introduction to transmitting data over RF, I learnt how to transmit small messages to a 16x2 char display, using the nRF24L01</p>
                            <span>C</span>
                            <span>Arduino</span>
                            <span>Myself</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>29/07/2019<span>]</span> Mapping analog input across LEDs<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">

                            <p>Using a POT as the input device, and mapping the 0-1023 voltage range across multiple LEDs. Including deadzones between each LED, and before the first LED.
                                As you turn the potentiometer the brightness of the first LED will increase, until reaching full brightness, then the next LED in sequence will light up (after passing the deadzone)
                                until max, and so on</p>
                            <span>C</span>
                            <span>Arduino</span>
                            <span>Myself</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>09/07/2019<span>]</span> AutoTagger<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">

                            <p>Cycle through audio files within a directory, correctly assigning ID3 metadata by comparing artist name(s) against a JSON file, which grows dynamically with each new artist it encounters.
                                Used for clear formatting when using media players</p>
                            <span>Python</span>
                            <span>Json</span>
                            <span>Myself</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>08/07/2019<span>]</span> MicroCue power control<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">

                            <p>Determining if a pin is inactive, if so power cycle the device a set amount of times. If the device doesn't "stablise", further checks are not made, and the device is disconnected</p>
                            <span>C</span>
                            <span>AVR</span>
                            <span>Hive Industries</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>03/07/2019<span>]</span> Power regulator<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">

                            <p>Grabbing samples of line voltage, performing power checks if certain conditions aren't met. Also calling a reset if required, which is indicated by LEDs, preventing further damage to the main device</p>
                            <span>C</span>
                            <span>Arduino</span>
                            <span>Hive Industries</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>03/07/2019<span>]</span> ATtiny VU Meter<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">

                            <p>Take in a sample, and reference voltage reading, converted to a dB range, which is then indicated using charlieplexed LEDs</p>
                            <span>C</span>
                            <span>Arduino</span>
                            <span>Hive Industries</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>23/06/2019<span>]</span> Microwave style digit shifting<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">

                            <p>Produced a method that takes in a numeric digit, shifting the four digits infront of it, removing the overflowed digit. Displaying the digits on a Nextion display</p>
                            <span>C</span>
                            <span>Arduino</span>
                            <span>Nextion</span>
                            <span>Hive Industries</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>23/06/2019<span>]</span> Nextion callbacks<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">

                            <p>Understanding the flow of onrelease/ontouch callbacks given by the Nextion</p>
                            <span>C</span>
                            <span>Arduino</span>
                            <span>Nextion</span>
                            <span>Myself</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>20/06/2019<span>]</span> Nextion calculator<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">

                            <p>For my first project using the Nextion, I built a small touch screen keypad, with operators, to input a calculation, for an Arduino to then calculate and return</p>
                            <span>C</span>
                            <span>Arduino</span>
                            <span>Nextion</span>
                            <span>Myself</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>18/06/2019<span>]</span> Learning about the Nextion<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">

                            <p>Figuring out how to communicate with the Nextion using the TX/RX pins, as well as understanding the Nextion Editor</p>
                            <span>C</span>
                            <span>Arduino</span>
                            <span>Nextion</span>
                            <span>Myself</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>18/06/2019<span>]</span> Power Indicator based on PWR down delay<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">

                            <p>Detect, and indicate if a pin goes LOW for Xms. If so, reset the device, and if this occurs an amount of times within a period of time, disconnect the device</p>
                            <span>C</span>
                            <span>AVR</span>
                            <span>Hive Industries</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>15/06/2019<span>]</span> M3U Creator<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">

                            <p>A small program that webscapes title names from a youtube playlist, matching it to a file name within a directory. Building up an M3U file following the same order as the youtube playlist</p>
                            <span>Python</span>
                            <span>Myself</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>04/05/2019<span>]</span> ATtiny Port manipulation<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">

                            <p>Learning about ATtiny Port manipulation, and the registers involved to control functions of the chip</p>
                            <span>C</span>
                            <span>AVR</span>
                            <span>Myself</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>11/04/2019<span>]</span> RWs to EEPROM<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">

                            <p>Learning how to store and read small amount of data within EEPROM</p>
                            <span>C</span>
                            <span>AVR</span>
                            <span>Myself</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>03/01/2019<span>]</span> Char display calculator<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">
                            <img src="images/Calc.jpg">
                            <img src="images/Calc1.jpg">

                            <p>Using way too many momentary buttons, I built a program that allows you to cycle through the values 0-9 to enter a basic calculation. Entering the first single digit value, the operator,
                                then the second value. Then displaying the result on a 16x2 char display</p>
                            <span>C</span>
                            <span>AVR</span>
                            <span>Myself</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>03/01/2019<span>]</span> Fading through multiple LEDs<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">

                            <p>When holding down a button, the brightness of the first LED would increase from min to max, then move onto the next LED, and so on. Releasing and holding the button again would cause the opposite to occur</p>
                            <span>C</span>
                            <span>Arduino</span>
                            <span>Myself</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>03/01/2019<span>]</span> Seven-segment display<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">
                            <img src="images/Segment.gif">

                            <p>Illuminating LEDs to display numbers 0-9, making use of Charlieplexing</p>
                            <span>C</span>
                            <span>Arduino</span>
                            <span>Myself</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>03/01/2019<span>]</span> Fading LEDs using the ATtiny<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">

                            <p>Using the registers of the ATtiny45 to read-in analog inputs, and fade an LED</p>
                            <span>C</span>
                            <span>AVR</span>
                            <span>Myself</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>03/01/2019<span>]</span> ADC with the ATtiny<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">

                            <p>Learning how the tiny interprets analog inputs, and how to write basic programs to an IC that can perform digital read/writes</p>
                            <span>C</span>
                            <span>AVR</span>
                            <span>Myself</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>16/12/2018<span>]</span> Text-based Scrabble<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">
                            <img src="images/Scrabble.jpg">
                            <img src="images/Scrabble1.png">

                            <p>An ASCII recreation of the board game Scrabble, developed for my A-Level Computer Science coursework. Including: Premium scoring cells,
                                Horizontal and vertical placement, Blank tiles, A dictionary validation check around the letter(s) placement, Multi-word scoring, and more.
                                I also wanted to give a huge thanks to my incredible teacher, Mr May for being so interesting to talk to, as well as fuelling my interest in computers</p>
                            <span>Python</span>
                            <span>Myself</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>08/10/2018<span>]</span> Digital Illustration<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">
                            <img src="images/Rubix.png">
                            <img src="images/Cat.png">
                            <img src="images/Planets.png">
                            <img src="images/Neon.jpg">
                            <img src="images/Arctic.jpg">
                            <img src="images/Z.jpg">
                            <img src="images/Glasses.jpg">

                            <p>As well as studying Computer Science, I studied Digital Illustration for A-Levels. Which involved lots of short studies into different topics which we could interpret in our own ways,
                                which you can see above. With yet another great teacher being Mr Eyre</p>
                            <span>Artwork</span>
                            <span>Myself</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>22/07/2018<span>]</span> Bomb Run game<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">
                            <img src="images/HR.png">
                            <img src="images/HR1.png">
                            <img src="images/HR2.png">
                            <img src="images/HR3.png">
                            <img src="images/HR4.gif">
                            <img src="images/HR5.gif">

                            <p>For my second game, I wanted to add some more features. This included the addition of multiple abilities, where a random ability is activated when you collect a mystery box.
                                Also, some basic character customisation and upgrades, that allow a player to increase the length of time that each ability lasts, and change their colour.<br><br>As I haven't kept
                                the game up-to-date with the latest Android Play Store policies, it has been removed due to its outdated usage of Ads (and everything else). For a short period of time I provided an
                                APK version of it, but I feel it is too outdated now (although some site somewhere probably still has an APK of it, but I wouldn't trust it).</p>
                            <span>C#</span>
                            <span>Unity</span>
                            <span>Aseprite</span>
                            <span>Myself</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>22/04/2018<span>]</span> Sweep Driveby game<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">
                            <img src="images/BR.png">
                            <img src="images/BR1.png">
                            <img src="images/BR2.png">

                            <p>My first released game, and my first developed game for Android. The aim of the game is to swipe the junk off the road, that the vehicles continue to dump off. This earns you points, and bonus
                                points for swiping junk into the hoops! The smaller the hoop the more bonus points you will recieve, you loose the game if a car collides with a piece of junk.<br><br>As I haven't kept
                                the game up-to-date with the latest Android Play Store policies, it has been removed due to its outdated usage of Ads (and everything else). For a short period of time I provided an
                                APK version of it, but I feel it is too outdated now (although some site somewhere probably still has an APK of it, but I wouldn't trust it).</p>
                            <span>C#</span>
                            <span>Unity</span>
                            <span>Blender</span>
                            <span>Myself</span>
                        </div>
                    </div>
                    <div class="entry">
                        <button type="button" onClick="ToggleDesc(this)"><span>[</span>07/04/2018<span>]</span> Autocomplete UnityCS<i class="fas fa-caret-down"></i></button>
                        <div class="entry-drop">
                            <img src="images/Autocomplete.gif">

                            <p>I built a little autcomplete package for the Atom editor, that integrates most of the elements from the Unity Scripting API. With reference links to the relevant Unity
                                Scripting Reference page, using the [More] redirect. Again I haven't kept this project up-to-date, so it may or may not still be available, and even so it will
                                not include the latest entries from the Reference pages, as I grabbed the entries using a web scraper I built in Python, at the time of creation</p>
                            <span>Atom</span>
                            <span>Python</span>
                            <span>Myself</span>
                        </div>
                    </div>

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
    </body>
</html>