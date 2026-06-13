# Tooba-Iqbal
<!DOCTYPE html>
<html lang="en">

<head>
    <title>Visit Pakistan</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #222;
            margin: 0;
            padding: 0;
        }
        
        header {
            background-color: #1a5276;
            color: white;
            padding: 20px;
            text-align: center;
        }
        
        header h1 {
            font-size: 32px;
            margin-bottom: 4px;
        }
        
        header p {
            font-size: 14px;
            color: #aac6e0;
        }
        /* NAV */
        
        nav {
            background-color: #154360;
            text-align: center;
            padding: 10px;
        }
        
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 14px;
            font-size: 14px;
        }
        
        nav a:hover {
            text-decoration: underline;
        }
        
        main {
            max-width: 900px;
            margin: 30px auto;
            padding: 0 20px;
        }
        
        section {
            background-color: white;
            padding: 24px;
            margin-bottom: 24px;
            border: 1px solid #ddd;
        }
        
        section h2 {
            color: #1a5276;
            font-size: 20px;
            border-bottom: 2px solid #1a5276;
            padding-bottom: 6px;
            margin-bottom: 16px;
        }
        
        .dest-row {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
        }
        
        figure {
            text-align: center;
            flex: 1 1 200px;
        }
        
        figure img {
            width: 100%;
            height: 140px;
            object-fit: cover;
            border: 2px solid #ccc;
        }
        
        figcaption {
            font-size: 12px;
            color: #555;
            margin-top: 4px;
        }
        
        dl dt {
            font-weight: bold;
            color: #1a5276;
            margin-top: 10px;
        }
        
        dl dd {
            margin-left: 20px;
            color: #444;
        }
        
        table {
            width: 100%;
            border-collapse: collapse;
            font-size: 14px;
        }
        
        table th {
            background-color: #1a5276;
            color: white;
            padding: 9px;
            text-align: center;
        }
        
        table td {
            border: 1px solid #ccc;
            padding: 8px;
            text-align: center;
        }
        
        table tr:nth-child(even) td {
            background-color: #eaf0f6;
        }
        
        .break-row td {
            background-color: #fef9e7;
            font-weight: bold;
            color: #7d6608;
        }
        
        .form-row {
            margin-bottom: 12px;
        }
        
        .form-row label {
            display: inline-block;
            width: 130px;
            font-weight: bold;
            font-size: 14px;
        }
        
        .form-row input[type="text"],
        .form-row input[type="email"],
        .form-row input[type="password"],
        .form-row select {
            padding: 7px 10px;
            border: 1px solid #aaa;
            font-size: 14px;
            width: 240px;
        }
        
        .form-row .radio-group {
            display: inline-flex;
            gap: 14px;
            font-size: 14px;
        }
        
        button {
            background-color: #1a5276;
            color: white;
            border: none;
            padding: 9px 22px;
            font-size: 14px;
            cursor: pointer;
            margin-right: 8px;
            margin-top: 6px;
        }
        
        button:hover {
            background-color: #154360;
        }
        
        .output {
            background-color: #eaf0f6;
            border-left: 4px solid #1a5276;
            padding: 10px 14px;
            margin-top: 14px;
            font-size: 14px;
            min-height: 36px;
        }
        
        dialog {
            border: 2px solid #1a5276;
            padding: 28px;
            max-width: 360px;
            width: 90%;
        }
        
        dialog h3 {
            color: #1a5276;
            margin-bottom: 10px;
        }
        
        dialog p {
            font-size: 14px;
            margin-bottom: 16px;
            color: #333;
            line-height: 1.6;
        }
        
        details {
            border-bottom: 1px solid #ddd;
            padding: 10px 0;
        }
        
        details summary {
            font-weight: bold;
            color: #1a5276;
            cursor: pointer;
            font-size: 14px;
        }
        
        details p {
            margin-top: 8px;
            font-size: 14px;
            color: #444;
            padding-left: 14px;
            line-height: 1.6;
        }
        
        article {
            border: 1px solid #ddd;
            padding: 16px;
            margin-bottom: 14px;
        }
        
        article h3 {
            color: #1a5276;
            margin-bottom: 6px;
        }
        
        article p {
            font-size: 14px;
            color: #444;
            line-height: 1.6;
            margin-bottom: 6px;
        }
        
        article footer {
            background: none;
            padding: 6px 0 0;
            border-top: 1px solid #eee;
            font-size: 12px;
            color: #888;
        }
        
        ul,
        ol {
            margin-left: 22px;
            font-size: 14px;
            line-height: 2;
            color: #444;
        }
        
        footer.site-footer {
            background-color: #1a5276;
            color: #ccc;
            text-align: center;
            padding: 20px;
            font-size: 13px;
        }
        
        footer.site-footer a {
            color: #aac6e0;
        }
    </style>
</head>

<body>


    <header>
        <hgroup>
            <h1>Visit Pakistan</h1>
            <p>Explore the mountains, history, and culture of Pakistan</p>
        </hgroup>
    </header>


    <nav>
        <a href="#destinations">Destinations</a>
        <a href="#facts">Facts</a>
        <a href="#blog">Blog</a>
        <a href="#schedule">Schedule</a>
        <a href="#book">Book</a>
        <a href="#faq">FAQ</a>
        <a href="#js-demo">Demo</a>
    </nav>

    <main>


        <section id="destinations">
            <h2>Top Destinations</h2>

            <div class="dest-row">

                <figure>
                    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/54/Fairy_Meadows%2C_Pakistan_%282%29.jpg/640px-Fairy_Meadows%2C_Pakistan_%282%29.jpg" alt="Fairy Meadows">
                    <figcaption>Fig. 1 – Fairy Meadows</figcaption>
                </figure>

                <figure>
                    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b3/Lahore_Fort.jpg/640px-Lahore_Fort.jpg" alt="Lahore Fort">
                    <figcaption>Fig. 2 – Lahore Fort</figcaption>
                </figure>

                <figure>
                    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d4/K2_2006b.jpg/480px-K2_2006b.jpg" alt="K2">
                    <figcaption>Fig. 3 – K2, 8,611 m</figcaption>
                </figure>

            </div>

            <p style="margin-top:16px; font-size:14px; color:#444;">
                Click a destination to see travel details:
            </p>

            <button type="button" onclick="openDialog('Fairy Meadows', 'Best visited June to September. Altitude: 3,300 m. Trek from Raikot Bridge takes 3 hours.')">Fairy Meadows</button>
            <button type="button" onclick="openDialog('Lahore Fort', 'Open daily 8 AM to 6 PM. UNESCO World Heritage Site. Built by Emperor Akbar in the 16th century.')">Lahore Fort</button>
            <button type="button" onclick="openDialog('K2', 'World\'s 2nd highest peak at 8,611 m. Located in Gilgit-Baltistan. Only for expert mountaineers.')">K2</button>


            <dialog id="destDialog">
                <h3 id="dialog-title">Destination</h3>
                <p id="dialog-info">Info here.</p>
                <button type="button" onclick="document.getElementById('destDialog').close()">Close</button>
            </dialog>
        </section>


        <section id="facts">
            <h2>Pakistan – Key Facts</h2>

            <dl>
                <dt>Total Area</dt>
                <dd>881,913 km<sup>2</sup> — the 33<sup>rd</sup> largest country in the world.</dd>

                <dt>K2 Height</dt>
                <dd>8,611 m — the 2<sup>nd</sup> highest mountain on Earth.</dd>

                <dt>River Indus</dt>
                <dd>Length: 3,180 km. Freshwater source: H<sub>2</sub>O essential for farming.</dd>

                <dt>Carbon Dioxide</dt>
                <dd>Pakistan emits 0.9 tonnes of CO<sub>2</sub> per person per year. Eco-tourism helps.</dd>

                <dt>Population Density</dt>
                <dd>About 287 people per km<sup>2</sup>. Cities can reach 10<sup>4</sup> per km<sup>2</sup>.</dd>
            </dl>
        </section>


        <section id="blog">
            <h2>Travel Blog</h2>

            <article>
                <header>
                    <h3>Five Days on the Karakoram Highway</h3>
                    <p>Posted: April 2026</p>
                </header>
                <p>
                    The Karakoram Highway is 1,300 km of stunning mountain road from Hasan Abdal to the Chinese border. Temperature drops 6.5°C for every 1,000 m you climb — bring warm clothes even in summer.
                </p>
                <footer>
                    <p>Tags: Road Trip · Mountains · KKH</p>
                </footer>
            </article>

            <article>
                <header>
                    <h3>A Weekend in the Walled City of Lahore</h3>
                    <p>Posted: March 2026</p>
                </header>
                <p>
                    Walk through the Delhi Gate early in the morning before the bazaars open. Visit Badshahi Mosque, the Lahore Museum, and end the day at Food Street.
                </p>
                <footer>
                    <p>Tags: History · Culture · Lahore</p>
                </footer>
            </article>

        </section>


        <section id="schedule">
            <h2>Weekly Tour Schedule</h2>

            <table>
                <tr>
                    <th>Time</th>
                    <th>Monday</th>
                    <th>Tuesday</th>
                    <th>Wednesday</th>
                    <th>Thursday</th>
                    <th>Friday</th>
                </tr>
                <tr>
                    <td><strong>8:00 – 10:00</strong></td>
                    <td>Lahore City Tour</td>
                    <td>Taxila Day Trip</td>
                    <td>Lahore City Tour</td>
                    <td>Taxila Day Trip</td>
                    <td>Walled City Walk</td>
                </tr>
                <tr>
                    <td><strong>10:00 – 12:00</strong></td>
                    <td>Badshahi Mosque</td>
                    <td>Rohtas Fort</td>
                    <td>Lahore Museum</td>
                    <td>Katas Raj Temples</td>
                    <td>Shalimar Gardens</td>
                </tr>
                <tr class="break-row">
                    <td colspan="6">Lunch Break — 12:00 to 13:00</td>
                </tr>
                <tr>
                    <td><strong>13:00 – 16:00</strong></td>
                    <td>Lahore Fort</td>
                    <td>Free Explore</td>
                    <td>Food Street Tour</td>
                    <td>Free Explore</td>
                    <td>Sunset at Fort</td>
                </tr>
            </table>
        </section>


        <section id="book">
            <h2>Book a Tour</h2>

            <div class="form-row">
                <label>First Name</label>
                <input type="text" id="fname" placeholder="Your first name">
            </div>
            <div class="form-row">
                <label>Last Name</label>
                <input type="text" id="lname" placeholder="Your last name">
            </div>
            <div class="form-row">
                <label>Email</label>
                <input type="email" id="email" placeholder="you@email.com">
            </div>
            <div class="form-row">
                <label>Password</label>
                <input type="password" id="pwd" placeholder="Create a password">
            </div>
            <div class="form-row">
                <label>Trip Type</label>
                <span class="radio-group">
        <input type="radio" name="trip" value="solo"> Solo
        <input type="radio" name="trip" value="group" checked> Group
        <input type="radio" name="trip" value="family"> Family
      </span>
            </div>
            <div class="form-row">
                <label>Destination</label>
                <select id="dest">
        <option>Fairy Meadows</option>
        <option>Lahore Heritage</option>
        <option>Hunza Valley</option>
        <option>Skardu</option>
        <option>Naran &amp; Kaghan</option>
      </select>
            </div>
            <div class="form-row">
                <label>I agree:</label>
                <input type="checkbox" id="terms"> Terms &amp; Conditions
            </div>

            <button type="button" onclick="handleBooking()">Accept</button>
            <button type="button" onclick="resetForm()">Reset</button>

            <div class="output" id="book-output"></div>


            <dialog id="bookDialog">
                <h3>Booking Confirmed!</h3>
                <p id="book-dialog-msg"></p>
                <button type="button" onclick="document.getElementById('bookDialog').close()">Close</button>
            </dialog>
        </section>


        <section id="tips">
            <h2>Travel Tips</h2>

            <p style="font-size:14px; margin-bottom:10px;"><strong>What to Pack:</strong></p>
            <ul>
                <li>Warm jacket (even in summer for mountains)</li>
                <li>Sunscreen SPF 50+</li>
                <li>Water bottle — stay hydrated with clean H<sub>2</sub>O</li>
                <li>Power bank for remote areas</li>
            </ul>

            <p style="font-size:14px; margin:14px 0 10px;"><strong>How to Plan Your Trip:</strong></p>
            <ol>
                <li>Choose your region and travel season</li>
                <li>Apply for permits (NOC) if visiting restricted areas</li>
                <li>Check road conditions before departing</li>
                <li>Carry local currency — ATMs are scarce in mountains</li>
                <li>Buy a local SIM card for best coverage</li>
            </ol>
        </section>


        <section id="faq">
            <h2>FAQ</h2>

            <details>
                <summary>Is Pakistan safe for tourists?</summary>
                <p>Yes. Tourist areas like Hunza, Lahore, and Gilgit-Baltistan are safe and welcoming. Always check your government's travel advisory before departing.</p>
            </details>

            <details>
                <summary>What is the best time to visit?</summary>
                <p>May to September for northern mountains. October to February for Lahore and Sindh. Avoid monsoon season (July–August) for mountain roads.</p>
            </details>

            <details>
                <summary>Do I need a visa?</summary>
                <p>Citizens of 175+ countries can get a visa on arrival or apply online. E-visa processing takes 24–72 hours.</p>
            </details>

            <details>
                <summary>What currency is used?</summary>
                <p>Pakistani Rupee (PKR). USD, EUR, and GBP can be exchanged in major cities. Carry cash before entering remote mountain areas.</p>
            </details>
        </section>


        <section id="js-demo">
            <h2> Demo</h2>


            <button type="button" onclick="showDate()">Show Date</button>
            <button type="button" onclick="showVars()">Show Variables</button>
            <button type="button" onclick="confirmLeave()">Confirm &amp; Leave</button>
            <button type="button" onclick="alert('Welcome to Visit Pakistan!')">Alert</button>

            <div class="output" id="js-output">Click a button to see output.</div>
        </section>

    </main>

    <footer class="site-footer">
        <p>&copy; 2026 Visit Pakistan</p>
        <p>Contact: <a href="mailto:info@visitpakistan.pk">info@visitpakistan.pk</a></p>
    </footer>



    <script type="text/javascript">
        const SITE_NAME = "Visit Pakistan";
        const COUNTRY = "Pakistan";


        let currentUser = "Guest";

        function showDate() {

            document.getElementById("js-output").innerHTML =
                "<strong>Today:</strong> " + Date();
        }


        function showVars() {

            let _altitude = 3300;
            let $extraMetres = 5311;

            let total = _altitude + $extraMetres;

            document.getElementById("js-output").innerHTML =
                "const SITE_NAME = \"" + SITE_NAME + "\"<br>" +
                "let _altitude = " + _altitude + " m (Fairy Meadows)<br>" +
                "let $extraMetres = " + $extraMetres + " m<br>" +
                "Total = " + total + " m (K2 Summit)";
        }


        function confirmLeave() {
            var answer = confirm("Leave " + SITE_NAME + " and visit Pakistan Tourism site?");
            if (answer) {
                window.open("https://www.tourism.gov.pk");
            } else {
                document.getElementById("js-output").innerHTML =
                    "Good choice! Keep exploring " + COUNTRY + ".";
            }
        }


        function openDialog(title, info) {
            document.getElementById("dialog-title").innerHTML = title;
            document.getElementById("dialog-info").innerHTML = info;
            document.getElementById("destDialog").showModal();
        }


        function handleBooking() {
            let fname = document.getElementById("fname").value;
            let lname = document.getElementById("lname").value;
            let email = document.getElementById("email").value;
            let dest = document.getElementById("dest").value;

            if (fname === "" || lname === "" || email === "") {
                document.getElementById("book-output").innerHTML =
                    "Please fill in First Name, Last Name, and Email.";
                return;
            }

            currentUser = fname + " " + lname; // let changes here

            document.getElementById("book-dialog-msg").innerHTML =
                "Name: <strong>" + currentUser + "</strong><br>" +
                "Email: " + email + "<br>" +
                "Destination: <strong>" + dest + "</strong><br><br>" +
                "We will contact you within 24 hours!";

            document.getElementById("bookDialog").showModal();
            document.getElementById("book-output").innerHTML =
                "Booking received for <strong>" + currentUser + "</strong> — " + dest;
        }


        function resetForm() {
            document.getElementById("fname").value = "";
            document.getElementById("lname").value = "";
            document.getElementById("email").value = "";
            document.getElementById("pwd").value = "";
            document.getElementById("book-output").innerHTML = "";
        }
    </script>

</body>

</html>
