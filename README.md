# Prosper Tree Brochure Site

A simple informational brochure site for Prosper Tree, an investment growing company.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Prosper Tree</title>
    <style>
        :root {
            --primary: #9caf88;
            --accent: #ede8d0;
            --dark: #2e3a2e;
            --light: #ffffff;
        }

        body {
            margin: 0;
            font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
            background: var(--accent);
            color: var(--dark);
        }

        .hero {
            padding: 4rem 1.5rem;
            background: linear-gradient(135deg, var(--primary) 0%, var(--accent) 100%);
            text-align: center;
        }

        .hero h1 {
            margin: 0;
            font-size: clamp(2.5rem, 4vw, 4rem);
            color: var(--light);
        }

        .hero p {
            margin: 1rem auto 0;
            max-width: 720px;
            color: rgba(255, 255, 255, 0.9);
            line-height: 1.65;
        }

        .container {
            max-width: 1080px;
            margin: 0 auto;
            padding: 3rem 1.5rem;
        }

        section {
            margin-bottom: 3rem;
            padding: 2rem;
            background: var(--light);
            border-radius: 20px;
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.08);
        }

        h2 {
            margin-top: 0;
            color: var(--primary);
        }

        .metrics {
            display: grid;
            gap: 1rem;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            margin-top: 1.5rem;
        }

        .metric-card {
            background: var(--accent);
            border-radius: 16px;
            padding: 1.5rem;
            text-align: center;
        }

        .metric-card strong {
            display: block;
            font-size: 2rem;
            color: var(--dark);
        }

        .metric-card span {
            color: #556d55;
            display: block;
            margin-top: 0.5rem;
        }

        form {
            display: grid;
            gap: 1rem;
        }

        input,
        textarea {
            width: 100%;
            border: 1px solid #c5c2b8;
            border-radius: 12px;
            padding: 0.95rem 1rem;
            font-size: 1rem;
            background: #f7f2e9;
            color: var(--dark);
        }

        button {
            border: none;
            border-radius: 999px;
            padding: 0.95rem 1.5rem;
            background: var(--primary);
            color: var(--light);
            font-size: 1rem;
            cursor: pointer;
            transition: transform 0.2s ease, box-shadow 0.2s ease;
        }

        button:hover {
            transform: translateY(-2px);
            box-shadow: 0 14px 24px rgba(0, 0, 0, 0.12);
        }

        footer {
            text-align: center;
            color: #5a6d59;
            padding: 1.5rem;
        }
    </style>
</head>
<body>
    <header class="hero">
        <h1>Prosper Tree</h1>
        <p>Growing your future with sustainable investment strategies, trusted financial stewardship, and a clear path to long-term prosperity.</p>
    </header>

    <main class="container">
        <section id="about">
            <h2>About Prosper Tree</h2>
            <p>Prosper Tree is an investment management firm dedicated to helping individuals and businesses grow wealth responsibly. We combine disciplined research, diversified portfolios, and personalized service to support long-term financial success.</p>
            <div class="metrics">
                <div class="metric-card">
                    <strong>$213M</strong>
                    <span>Assets under management</span>
                </div>
                <div class="metric-card">
                    <strong>12+</strong>
                    <span>Years of experience</span>
                </div>
                <div class="metric-card">
                    <strong>98%</strong>
                    <span>Client satisfaction</span>
                </div>
            </div>
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <p>Ready to plant the seeds for your financial future? Reach out and one of our advisors will get back to you shortly.</p>
            <form action="#" method="post">
                <input type="text" name="name" placeholder="Full name" required />
                <input type="email" name="email" placeholder="Email address" required />
                <textarea name="message" rows="5" placeholder="Tell us about your goals" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </section>
    </main>

    <footer>
        <p>Prosper Tree | Investing in growth, stability, and your success.</p>
    </footer>
</body>
</html>
```

Use this HTML as a brochure-style landing page for Prosper Tree.
