<section class="home" style="text-align:center; padding: 2rem;">
    <div class="navbar">
        <a class="active" href="home">Home</a>
        <a href="contact">Contact</a>
        <a href="about">About</a>
    </div>
    <h1>Dylan Berutti</h1>
    <p>Welcome to my projects hub!</p>
    <p>
        I'm a sophomore computer science major at the university of pittsburgh
        with a passion for low level systems and UNIX!
    </p>
    <section class="skills">
        <h1>Skills:</h1>
        <h2>Unix and Deployment Tools:</h2>
        <p>-Linux and docker</p>
    </section>
</section>

<style global>
    body {
        :root {
            --font-mono: ui-monospace;
        }
    }
    .navbar {
        background-color: #333;
        overflow: hidden;
    }
    .navbar a {
        float: left;
        color: #ddd;
        text-align: center;
        padding: 14px 16px;
        text-decoration: none;
        font-size: 17px;
    }
    .navbar a:hover {
        background-color: #ddd;
        color: black;
    }
    .navbar a.active {
        background-color: #04aa6d;
        color: white;
    }
    .home h1 {
        margin-bottom: 0.5rem;
    }
    .skills {
        border: 1px solid blue;
        border-radius: 15px;
        padding: 20px;
        background-color: #f9f9f9;
    }
</style>
