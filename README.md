<!doctype html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>My Portofolio | Ahmad</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-4bw+/aepP/YC94hEpVNVgiZdgIC5+VKNBQNGCHeKRQN+PtmoHDEXuppvnDJzQIu9" crossorigin="anonymous">
</head>

<style>
    .about {
        padding-bottom: 50px;
        background-color: lightgrey;
    }

    .contact {
        width: 100%;
        height: 200px;
        background: rgb(39, 158, 255);
        background: linear-gradient(90deg, rgba(39, 158, 255, 1) 0%, rgba(39, 158, 255, 1) 100%);
        background-position: center;
        background-size: cover;
        color: white;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
    }
</style>

<body>
    <!-- Navbar Start -->
    <nav class="navbar navbar-expand navbar-primary bg-primary" aria-label="Second navbar example">
        <div class="container-fluid">
            <a class="navbar-brand text-light" href="#">Ahmad Neo Rizky</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarsExample02"
                aria-controls="navbarsExample02" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>

            <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                <div class="navbar-nav ms-auto">
                    <a class="nav-link text-light" aria-current="page" href="#home">Home</a>
                    <a class="nav-link text-light" href="#about">About Me</a>
                    <a class="nav-link text-light" href="#project">Project</a>
                    <a class="nav-link text-light" href="#contact">Contact</a>
                </div>
            </div>
        </div>
    </nav>
    <!-- Navbar End -->

    <!-- Home Start -->
    <section class="text-center" id="home">
        <div class="p-5 mb-4 bg-body-tertiary rounded-3">
            <div class="container-fluid py-5">
                <img src="myphoto.jpg" width="250px" height="250px" alt="" class="rounded-circle ">
                <h1>Ahmad Neo Rizky</h1>
                <p class="fs-4">Student | Web Developer</p>
            </div>
        </div>
    </section>
    <!-- Home End -->

    <!-- About Strat -->
    <section class="about" id="about">
        <div class="container text-center">
            <div class="row">
                <div class="col">
                    <h2>About Me</h2>
                </div>
            </div>

            <div class="row justify-content-center text-center">
                <div class="row row-cols-1 row-cols-md-1 g-2">
                    <div class="col">
                        <p style="text-align: justify">Hello, my name is Ahmad Neo Rizky. I'm from Jombang. My hobby is
                            playing music and also exploring things, including information technology. Apart from my
                            hobbies, I also have other things that I like, namely entrepreneurship and also
                            participating in esports tournaments. Besides that, I also like to design and edit both
                            photos and videos. I am an undergraduate student at Surabaya State University. My
                            organizational experiences include IPNU IPPNU, OSIS MA Al-Asy'ari Keras, and also HMP MP
                            UNESA. Apart from being a student, I also have work besides my busy life as a student.
                            Namely, I work at a tutoring institution called ESC (Excellent Study Club) as an admin and
                            branch coordinator in the village of Lidah Wetan (Surabaya). Apart from working at a
                            tutoring agency, I also have a side job or what is commonly called a freelance, namely
                            Cryptocurrency.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- About End -->

    <!-- Project Start -->
    <section class="project" id="project">
        <div class="container text-center">
            <div class="row">
                <div class="col">
                    <h2>Project</h2>
                </div>
            </div>

            <div class="row row-cols-1 row-cols-md-2 g-4">
                <div class="col">
                    <div class="card h-100">
                        <img src="pmw.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Entrepreneurial Student Program</h5>
                            <p class="card-text">Passed funding in the Entrepreneurial Student Program at Surabaya
                                State
                                University</p>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card h-100">
                        <img src="edunesa.png" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">EduNesa</h5>
                            <p class="card-text">EduNesa is a learning platform that provides online and offline
                                learning services with professional tutors from Surabaya State University</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        </div>
    </section>
    <!-- Project End -->

    <div id="wave-container" class="css-0 eepbx3x0">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
            <path fill="#279EFF" fill-opacity="1"
                d="M0,288L48,272C96,256,192,224,288,197.3C384,171,480,149,576,165.3C672,181,768,235,864,250.7C960,267,1056,245,1152,250.7C1248,256,1344,288,1392,304L1440,320L1440,320L1392,320C1344,320,1248,320,1152,320C1056,320,960,320,864,320C768,320,672,320,576,320C480,320,384,320,288,320C192,320,96,320,48,320L0,320Z">
            </path>
        </svg>
    </div>

    <!-- Contact Start -->
    <section class="contact" id="contact">
        <div class="container text-center">
            <div class="row">
                <div class="col">
                    <h2>Contact</h2>
                </div>
            </div>

            <div class="row justify-content-center text-center">
                <div class="col-md-4">
                    <p>Phone Number: +6281216800840.</p>
                </div>
                <div class="col-md-4">
                    <p>Email: ahmadneor1@gmail.com</p>
                </div>
                <div class="col-md-4">
                    <p>Instagram: @neorizky_</p>
                </div>
                <div class="col-md-4">
                    <p>Twitter: @ahmad68033</p>
                </div>
                <div class="col-md-4">
                    <p>LinkedIn: https://www.linkedin.com/in/ahmad-neo-r-4303b7281</p>
                </div>
                <div class="col-md-4">
                    <p>GitHup: https://github.com/ahmadneor1</p>
                </div>
            </div>
        </div>
    </section>
    <!-- Contact End -->

</body>
<footer>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-HwwvtgBNo3bZJJLYd8oVXjrBZt8cqVSpeBNS5n7C8IVInixGAoxmnlMuBnhbgrkm" crossorigin="anonymous">
        </script>
</footer>

</html>
