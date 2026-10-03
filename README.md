# explore-lagos-html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Semantic HTML Assignment</title>
</head>
<body>

    <!-- HEADER -->
    <header class="header-section">
        <h1>🌍 Explore Nigeria</h1>

        <nav>
            <a href="#contact-form">Contact Us</a> |
            <a href="#data-table">Explore Data</a>
        </nav>
    </header>

    <hr>

    <!-- MAIN -->
    <main class="main-content">

        <!-- SECTION 1 -->
        <section class="intro-section">
            <h2>Welcome</h2>
            <p>
                Discover beautiful places, amazing culture and useful information
                about Nigeria.
            </p>
        </section>

        <hr>

        <!-- SECTION 2 -->
        <section class="video-section">
            <h2>Featured Video</h2>

            <video
                width="600"
                height="350"
                autoplay
                muted
                loop
                controls>
                <source src="video.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>
        </section>

        <hr>

        <!-- SECTION 3 -->
        <section class="image-section">
            <h2>Featured Image</h2>

            <figure>
                <img
                    src="lagos.jpg"
                    alt="Lagos skyline at sunset"
                    width="600"
                    height="350">

                <figcaption>
                    Beautiful evening view of Lagos city.
                </figcaption>
            </figure>
        </section>

        <hr>

        <!-- TABLE -->
        <section class="table-section" id="data-table">

            <table border="1">
                <caption>
                    Population Statistics of Selected Nigerian Cities
                </caption>

                <thead>
                    <tr>
                        <th scope="col">City</th>
                        <th scope="col">State</th>
                        <th scope="col">Population</th>
                    </tr>
                </thead>

                <tbody>
                    <tr>
                        <th scope="row">Lagos</th>
                        <td>Lagos</td>
                        <td>15,000,000+</td>
                    </tr>

                    <tr>
                        <th scope="row">Abuja</th>
                        <td>FCT</td>
                        <td>3,600,000</td>
                    </tr>

                    <tr>
                        <th scope="row">Kano</th>
                        <td>Kano</td>
                        <td>4,100,000</td>
                    </tr>
                </tbody>

            </table>

        </section>

        <hr>

        <!-- FORM -->
        <section class="form-section">

            <h2>Contact Us</h2>

            <form id="contact-form">

                <fieldset>

                    <legend>Personal Information</legend>

                    <label for="fullname">Full Name</label><br>
                    <input
                        type="text"
                        id="fullname"
                        name="fullname"
                        minlength="10"
                        maxlength="20"
                        required>

                    <br><br>

                    <label for="email">Email</label><br>
                    <input
                        type="email"
                        id="email"
                        name="email"
                        required>

                    <br><br>

                    <label for="phone">Phone Number</label><br>
                    <input
                        type="tel"
                        id="phone"
                        name="phone"
                        maxlength="11"
                        required>

                </fieldset>

                <br>

                <fieldset>

                    <legend>Location</legend>

                    <label for="city">City</label><br>

                    <select id="city" required>
                        <option value="">Select City</option>
                        <option>Ikeja</option>
                        <option>Yaba</option>
                        <option>Surulere</option>
                        <option>Lekki</option>
                        <option>Ajah</option>
                        <option>Victoria Island</option>
                        <option>Ikorodu</option>
                        <option>Festac</option>
                        <option>Maryland</option>
                        <option>Epe</option>
                    </select>

                </fieldset>

                <br>

                <fieldset>

                    <legend>Message</legend>

                    <label for="message">Message</label><br>

                    <textarea
                        id="message"
                        rows="5"
                        cols="40"
                        maxlength="100"
                        required></textarea>

                </fieldset>

                <br>

                <input type="submit" value="Submit">

            </form>

        </section>

    </main>

    <hr>

    <!-- FOOTER -->
    <footer class="footer-section">

        <h3>Quick Links</h3>

        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#">Gallery</a></li>
            <li><a href="#">Contact</a></li>
        </ul>

        <p>&copy; 2026 Explore Nigeria</p>

    </footer>

</body>
</html>
