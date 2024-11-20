<!DOCTYPE html>
<html lang="en">

    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <meta name="description"
            content="Professional portfolio showcasing creativity, UGC videos, and elegant design.">
        <title>My Portfolio</title>
        <style>
            :root {
                --forest-green: #5E6C5B;
                --fresh-cream: #F4EFE6;
                --cloud-white: #FEFCF6;
                --sky-blue: #D6E0E2;
                --storm-cloud: #686867;
                --midnight: #162A2C;
            }

            body {
                font-family: 'Roboto', sans-serif;
                margin: 0;
                color: var(--forest-green);
                background-color: var(--cloud-white);
                line-height: 1.6;
            }

            header {
                background-color: var(--midnight);
                color: var(--cloud-white);
                padding: 1rem 2rem;
                display: flex;
                justify-content: space-between;
                align-items: center;
            }

            nav a {
                color: var(--cloud-white);
                text-decoration: none;
                margin: 0 1rem;
                font-size: 1rem;
            }

            nav a:hover {
                color: var(--sky-blue);
            }

            .hero {
                background-color: var(--fresh-cream);
                padding: 4rem 2rem;
                text-align: center;
            }

            .hero h1 {
                color: var(--forest-green);
                font-size: 2.5rem;
            }

            .section {
                padding: 4rem 2rem;
            }

            .section:nth-child(even) {
                background-color: var(--fresh-cream);
            }

            .videos {
                display: grid;
                grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
                gap: 2rem;
                margin-top: 2rem;
            }

            .video-card {
                border: 1px solid var(--sky-blue);
                border-radius: 8px;
                overflow: hidden;
                box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            }

            .video-card iframe {
                width: 100%;
                height: 200px;
                border: none;
            }

            .cta {
                background-color: var(--forest-green);
                color: var(--cloud-white);
                padding: 1rem 2rem;
                text-align: center;
                border-radius: 5px;
                text-decoration: none;
                display: inline-block;
                margin: 1rem auto;
            }

            footer {
                background-color: var(--midnight);
                color: var(--cloud-white);
                text-align: center;
                padding: 2rem;
            }

            footer a {
                color: var(--sky-blue);
                text-decoration: none;
            }

            footer a:hover {
                text-decoration: underline;
            }
        </style>
    </head>

    <body>
        <header>
            <h1>My Portfolio</h1>
            <nav>
                <a href="#about">About</a>
                <a href="#portfolio">Portfolio</a>
                <a href="#contact">Contact</a>
            </nav>
        </header>

        <div class="hero">
            <h1>Welcome to My Professional Portfolio</h1>
            <p>Showcasing creativity, UGC expertise, and elegant video content.</p>
        </div>

        <section id="about" class="section">
            <h2>About Me</h2>
            <p>
                Hello! I am passionate about creating high-quality, engaging UGC content. I specialize in
                faceless skincare videos and elegant, aesthetic designs to captivate audiences.
            </p>
        </section>

        <section id="portfolio" class="section">
            <h2>My Work</h2>
            <p>Here are some of my recent UGC videos:</p>
            <div class="videos">
                <div class="video-card">
                    <iframe src="peter j perfumes.mp4" allowfullscreen></iframe>
                </div>
                <div class="video-card">
                    <iframe src="brillare rosemary essential oil.mp4" allowfullscreen></iframe>
                </div>
                <div class="video-card">
                    <iframe src="plum night gel.mp4" allowfullscreen></iframe>
                </div>
                <div class="video-card">
                    <iframe src="aqualogica gel moisturizer (1).mp4" allowfullscreen></iframe>
                </div>
            </div>
        </section>

        <section id="contact" class="section">
            <h2>Contact Me</h2>
            <p>If you'd like to collaborate or inquire about my work, feel free to reach out!</p>
            <a class="cta" href="mailto:your-email@gmail.com">Email Me</a>
            <a class="cta" href="https://www.instagram.com/yourusername" target="_blank">Follow Me on Instagram</a>
        </section>

        <footer>
            <p>© 2024 Your Name. All Rights Reserved.</p>
            <p>
                <a href="mailto:kuchbhi.ugc@gmail.com">Email</a> |
                <a href="https://www.instagram.com/kuchbhi.ugc/?__pwa=1" target="_blank">Instagram</a>
            </p>
        </footer>
    </body>

</html>
