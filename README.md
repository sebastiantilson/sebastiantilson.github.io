
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sebastian Tilson</title>
  <meta name="description" content="Personal research website of Sebastian Tilson — research on U.S. mortgage markets, owner-occupancy fraud, and housing finance." />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Crimson+Pro:ital,wght@0,400;0,600;1,400&family=Inter:wght@400;500;600&display=swap" rel="stylesheet">
  <style>
    :root {
      --bg: #fbfaf7;
      --text: #1f1d1a;
      --muted: #5a564e;
      --accent: #7a2c2c;
      --rule: #e6e1d6;
      --serif: "Crimson Pro", Georgia, "Times New Roman", serif;
      --sans: "Inter", -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
    }

    * { box-sizing: border-box; }

    html { scroll-behavior: smooth; }

    body {
      margin: 0;
      background: var(--bg);
      color: var(--text);
      font-family: var(--serif);
      font-size: 19px;
      line-height: 1.65;
      -webkit-font-smoothing: antialiased;
      text-rendering: optimizeLegibility;
    }

    .wrap {
      max-width: 720px;
      margin: 0 auto;
      padding: 64px 28px 96px;
    }

    header.site {
      border-bottom: 1px solid var(--rule);
      padding-bottom: 28px;
      margin-bottom: 40px;
    }

    header.site h1 {
      font-family: var(--serif);
      font-weight: 600;
      font-size: 2.4rem;
      letter-spacing: -0.01em;
      margin: 0 0 6px;
    }

    header.site .tagline {
      font-family: var(--sans);
      font-size: 0.95rem;
      color: var(--muted);
      margin: 0;
    }

    nav.site {
      margin-top: 18px;
      font-family: var(--sans);
      font-size: 0.9rem;
    }

    nav.site a {
      color: var(--muted);
      text-decoration: none;
      margin-right: 18px;
      border-bottom: 1px solid transparent;
      transition: color 0.15s ease, border-color 0.15s ease;
    }

    nav.site a:hover {
      color: var(--accent);
      border-bottom-color: var(--accent);
    }

    section {
      margin-bottom: 56px;
    }

    section h2 {
      font-family: var(--sans);
      font-size: 0.78rem;
      font-weight: 600;
      letter-spacing: 0.14em;
      text-transform: uppercase;
      color: var(--muted);
      margin: 0 0 18px;
    }

    p {
      margin: 0 0 1.1em;
    }

    a {
      color: var(--accent);
      text-decoration: none;
      border-bottom: 1px solid rgba(122, 44, 44, 0.25);
      transition: border-color 0.15s ease;
    }

    a:hover {
      border-bottom-color: var(--accent);
    }

    em, i, cite {
      font-style: italic;
    }

    .paper {
      border-left: 2px solid var(--rule);
      padding: 4px 0 4px 18px;
      margin-top: 22px;
      font-size: 0.98rem;
    }

    .paper .title {
      font-style: italic;
      font-weight: 500;
    }

    .paper .meta {
      font-family: var(--sans);
      font-size: 0.85rem;
      color: var(--muted);
      margin-top: 4px;
      display: block;
    }

    ul.press {
      list-style: none;
      padding: 0;
      margin: 0;
    }

    ul.press li {
      padding: 14px 0;
      border-bottom: 1px solid var(--rule);
      display: flex;
      flex-direction: column;
      gap: 2px;
    }

    ul.press li:last-child {
      border-bottom: none;
    }

    ul.press .outlet {
      font-family: var(--sans);
      font-size: 0.78rem;
      font-weight: 600;
      letter-spacing: 0.08em;
      text-transform: uppercase;
      color: var(--muted);
    }

    ul.press .headline {
      font-style: italic;
      font-size: 1.02rem;
    }

    ul.press .date {
      font-family: var(--sans);
      font-size: 0.82rem;
      color: var(--muted);
    }

    .contact-block {
      font-size: 1rem;
    }

    footer.site {
      margin-top: 72px;
      padding-top: 24px;
      border-top: 1px solid var(--rule);
      font-family: var(--sans);
      font-size: 0.82rem;
      color: var(--muted);
    }

    @media (max-width: 520px) {
      body { font-size: 17px; }
      .wrap { padding: 44px 22px 72px; }
      header.site h1 { font-size: 1.9rem; }
      nav.site a { display: inline-block; margin: 0 14px 8px 0; }
    }

    @media (prefers-color-scheme: dark) {
      :root {
        --bg: #1a1816;
        --text: #ece7dc;
        --muted: #9c9689;
        --accent: #d99a9a;
        --rule: #322e29;
      }
    }
  </style>
</head>
<body>
  <div class="wrap">
    <header class="site">
      <h1>Sebastian Tilson</h1>
      <p class="tagline">AI product manager &middot; mortgage-market researcher</p>
      <nav class="site" aria-label="Section navigation">
        <a href="#bio">Biography</a>
        <a href="#research">Research</a>
        <a href="#press">Selected Press</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <main>
      <section id="bio">
        <h2>Biography</h2>
        <p>
          Sebastian Tilson is an AI product manager whose research on U.S. mortgage markets has been
          cited by <em>The Economist</em>, <em>The Wall Street Journal</em>, and <em>Bloomberg</em>
          among others. His paper <em>Owner-Occupancy Fraud and Mortgage Performance</em>,
          co-authored with Ronel Elul and Aaron Payne, was published in <em>Real Estate Economics</em>
          in 2023 and grew out of his work at the Federal Reserve Bank of Philadelphia.
        </p>
        <p>
          He holds an MS in Applied Statistics from Villanova University and a BA in Mathematics
          from Haverford College. He lives in the Philadelphia area.
        </p>
      </section>

      <section id="research">
        <h2>Research</h2>
        <p>
          When someone takes out a mortgage to buy a home, they have to tell the lender whether they
          plan to live in it. The answer matters: &ldquo;primary residence&rdquo; mortgages come with
          lower interest rates, smaller down payments, and easier credit terms than mortgages for
          investment properties. So there&rsquo;s a real incentive to lie.
        </p>
        <p>
          My co-authors and I set out to measure how often that lie actually happens. Using matched
          credit bureau and mortgage data covering hundreds of thousands of loans, we identified
          borrowers who claimed to be moving into a home but never actually moved. What we found
          surprised us: roughly one in three borrowers in the U.S. mortgage market who behave like
          investors are hiding behind owner-occupant labels. The fraud isn&rsquo;t a relic of the
          2008 housing bubble &mdash; it persists in mortgages originated through 2017, the end of
          our data. It shows up across loans backed by Fannie Mae and Freddie Mac, in bank
          portfolios, and in private securitizations alike.
        </p>
        <p>
          These borrowers default at a 75% higher rate than investors who told the truth. And their
          defaults are more likely to be &ldquo;strategic&rdquo; &mdash; walking away from
          underwater properties they could afford to keep paying &mdash; which means they pose an
          outsized risk to the housing market when prices fall.
        </p>

        <div class="paper">
          <a class="title"
             href="https://onlinelibrary.wiley.com/doi/abs/10.1111/1540-6229.12455"
             target="_blank" rel="noopener">
            Owner-Occupancy Fraud and Mortgage Performance
          </a>
          <span class="meta">Elul, Payne, and Tilson &middot; <em>Real Estate Economics</em>, 2023</span>
        </div>

        <div class="paper">
          <a class="title"
             href="https://www.philadelphiafed.org/consumer-finance/mortgage-markets/from-deceit-to-default-dishonest-borrowers-and-their-effect-on-mortgage-markets">
            From Deceit to Default: Dishonest Borrowers and Their Effect on Mortgage Markets
          </a>
          <span class="meta">Elul, Payne, and Tilson &middot; <em>Federal Reserve Bank of Philadelphia Working Paper Series</em>, 2023</span>
        </div>
        
      </section>

      <section id="press">
        <h2>Selected Press</h2>
        <ul class="press">
          <li>
            <span class="outlet">The Economist</span>
            <a class="headline"
               href="https://www.economist.com/finance-and-economics/2023/08/03/meet-americas-disguised-property-investors"
               target="_blank" rel="noopener">
              Meet America&rsquo;s Disguised Property Investors
            </a>
            <span class="date">August 2023</span>
          </li>
        </ul>

        <ul class="press">
          <li>
            <span class="outlet">The Wall Street Journal</span>
            <a class="headline"
               href="https://wsj.com/economy/housing/mortgage-occupancy-fraud-law-3894c80c"
               target="_blank" rel="noopener">
              Can A Person Ever Legally Have Mortgages For More Than One Primary Residence?
            </a>
            <span class="date">August 2025</span>
          </li>
        </ul>

          <ul class="press">
          <li>
            <span class="outlet">Bloomberg</span>
            <a class="headline"
               href="https://www.bloomberg.com/news/articles/2025-08-20/fed-found-over-22-000-mortgages-like-those-pulte-is-now-flagging">
              Fed Found Over 22,000 Mortgages Like Those Pulte Is Flagging
            </a>
            <span class="date">August 2025</span>
          </li>
        </ul>
        
      </section>

      <section id="contact">
        <h2>Contact</h2>
        <p class="contact-block">
          For media inquiries or research questions, email
          <a href="mailto:Sebastian.Tilson@gmail.com">Sebastian.Tilson@gmail.com</a>.
        </p>
      </section>
    </main>

    <footer class="site">
      &copy; <span id="year"></span> Sebastian Tilson
    </footer>
  </div>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
