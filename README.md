<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tuulva Guardian | Voice of Tulunadu</title>
    <style>
        :root {
            --primary-red: #8b0000; /* Heritage Deep Red */
            --text-dark: #1a1a1a;
            --bg-light: #fdfcf8; /* Paper-like background */
        }

        body {
            font-family: 'Georgia', serif;
            margin: 0;
            background-color: var(--bg-light);
            color: var(--text-dark);
            line-height: 1.6;
        }

        header {
            text-align: center;
            padding: 40px 20px;
            border-bottom: 3px double var(--text-dark);
        }

        .logo {
            font-size: 3.5rem;
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: -1px;
            margin: 0;
        }

        nav {<div class="hero-image" style="width: 100%; height: 300px; overflow: hidden; margin-bottom: 20px;">
    <img src="https://source.unsplash.com/featured/?coast,india,temple" 
         alt="Tulunadu Heritage" 
         style="width: 100%; height: 100%; object-fit: cover;">
</div>
;
        }

        .container {
            max-width: 1100px;
            margin: 20px auto;
            display: grid;
            grid-template-columns: 2fr 1fr;
            gap: 40px;
            padding: 0 20px;
        }

        .main-story {
            border-bottom: 1px solid #ddd;
            padding-bottom: 20px;
        }

        .main-story h2 {
            font-size: 2.2rem;
            margin-top: 10px;
            color: var(--primary-red);
        }

        .sidebar h3 {
            border-top: 2px solid var(--text-dark);
            padding-top: 10px;
            text-transform: uppercase;
            font-size: 1rem;
        }

        .btn {
            background: var(--text-dark);
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            display: inline-block;
            margin-top: 10px;
            font-family: sans-serif;
            font-size: 0.9rem;
        }

        footer {
            text-align: center;
            padding: 40px;
            margin-top: 40px;
            background: #eee;
            font-size: 0.8rem;
        }
    </style>
</head>
<body>

    <header>
        <p style="font-style: italic; margin-bottom: 10px;">The Independent Voice of the Tulu People</p>
        <h1 class="logo">TUULVA GUARDIAN</h1>
    </header>

    <nav>
        <span>News</span> | <span>Heritage</span> | <span>Advocacy</span> | <span>Maritime</span> | <span>About</span>
    </nav>

    <div class="container">
        <main>
            <article class="main-story">
                <p style="color: var(--primary-red); font-weight: bold; margin: 0;">ADVOCACY</p>
                <h2>The Case for Classical Status: Why Tulu’s Recognition is Overdue</h2>
                <p>An in-depth look at the linguistic depth of Tulu and the ongoing campaign to include it in the 8th Schedule of the Constitution...</p>
                <a href="#" class="btn">Read Full Report</a>
            </article>

            <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin-top: 30px;">
                <article>
                    <h3>The Alupa Legacy</h3>
                    <p>New insights into the 7th-century Pelattur inscriptions and the dynasty that shaped our coast.</p>
                </article>
                <article>
                    <h3>Maritime Routes</h3>
                    <p>Exploring the "T-Signal" hypothesis and ancient Tulu-Kadal trade networks.</p>
                </article>
            </div>
        </main>

        <aside class="sidebar">
            <h3>Latest Updates</h3>
            <p><strong>• SSLC Results:</strong> Tulu language sees 100% pass rate in 2025.</p>
            <p><strong>• Railway Representation:</strong> New demands for Tuluva staff in regional coastal zones.</p>
            
            <div style="background: #f0f0f0; padding: 15px; margin-top: 30px;">
                <h3>Our Mission</h3>
                <p>To document, preserve, and advocate for the cultural and linguistic sovereignty of Tulunadu.</p>
            </div>
        </aside>
    </div>

    <footer>
        &copy; 2026 Tuulva Guardian. Dedicated to the Tulu Heritage.
    </footer>

</body>
</html>

