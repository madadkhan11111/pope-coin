<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pope Coin - The Future of Meme Crypto</title>
    <link rel="stylesheet" href="styles.css">
    <script defer src="script.js"></script>

    <style>
        /*
         * BODY & GENERAL STYLES
         */
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background: linear-gradient(to right, #f7d794, #f3a683);
            color: #333;
            overflow-x: hidden;
        }
        h1, h2, h3 {
            margin: 0.5em 0;
        }
        p {
            margin: 0.5em 0;
            line-height: 1.6;
        }
        a {
            text-decoration: none;
            color: inherit;
        }
        /*
         * HEADER
         */
        header {
            background: rgba(255, 215, 0, 0.9);
            padding: 20px;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.2);
            position: relative;
        }
        .pope-image {
            width: 150px;
            height: auto;
            position: absolute;
            top: 10px;
            left: 50%;
            transform: translateX(-50%);
        }
        .logo {
            width: 200px;
            height: auto;
            margin-top: 60px; /* push down below the pope image */
        }
        /*
         * NAVIGATION
         */
        nav ul {
            list-style: none;
            padding: 0;
            background: #222;
            overflow: hidden;
            color: white;
            text-align: center;
            border-radius: 10px;
            margin: 10px auto;
            display: inline-block;
        }
        nav ul li {
            display: inline-block;
            padding: 15px 20px;
        }
        nav ul li a {
            color: white;
            font-weight: bold;
            transition: color 0.3s ease;
        }
        nav ul li a:hover {
            color: #ffd700;
        }
        /*
         * SECTIONS
         */
        section {
            padding: 40px;
            background: rgba(255, 255, 255, 0.9);
            border-radius: 20px;
            margin: 30px auto;
            width: 80%;
            max-width: 1200px;
            box-shadow: 0px 4px 20px rgba(0, 0, 0, 0.1);
            position: relative;
        }
        /* Additional styling for section headings */
        section h2 {
            font-size: 2em;
            margin-bottom: 1em;
            color: #e74c3c;
            text-transform: uppercase;
        }
        /*
         * FOOTER
         */
        footer {
            background: #222;
            color: white;
            padding: 20px;
            position: relative;
            width: 100%;
        }
        /*
         * BUTTONS & LINKS
         */
        .btn {
            display: inline-block;
            background: #ff4757;
            color: white;
            padding: 15px 30px;
            font-size: 18px;
            border-radius: 10px;
            cursor: pointer;
            text-decoration: none;
            font-weight: bold;
            transition: background 0.3s ease;
        }
        .btn:hover {
            background: #e84118;
        }
        .buy-solana {
            background: #ff4757;
            color: white;
            padding: 15px 30px;
            font-size: 20px;
            border-radius: 10px;
            cursor: pointer;
            text-decoration: none;
            font-weight: bold;
            transition: background 0.3s ease;
            display: inline-block;
            margin-top: 20px;
        }
        .buy-solana:hover {
            background: #e84118;
        }
        /*
         * TEAM SECTION
         */
        .team-cards {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
        .team-card {
            background: #ffffff;
            border-radius: 10px;
            box-shadow: 0px 2px 10px rgba(0,0,0,0.1);
            padding: 20px;
            flex: 1 1 200px;
            max-width: 300px;
        }
        .team-card img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            object-fit: cover;
        }
        .team-card h3 {
            margin: 10px 0 5px;
            font-size: 1.2em;
        }
        /*
         * PRICE/TICKER SECTION
         */
        #live-price {
            position: relative;
        }
        .price-box {
            background: #fff;
            border-radius: 10px;
            box-shadow: 0px 2px 10px rgba(0,0,0,0.1);
            padding: 20px;
            margin-top: 20px;
        }
        .price-box h3 {
            margin-bottom: 10px;
            color: #e74c3c;
        }
        /*
         * FAQ SECTION
         */
        .faq-item {
            text-align: left;
            margin: 10px 0;
        }
        .faq-item h4 {
            cursor: pointer;
            background: #ff4757;
            color: #fff;
            padding: 10px;
            border-radius: 8px;
            margin: 0;
            font-size: 1.1em;
        }
        .faq-item p {
            display: none;
            background: #fff;
            padding: 10px;
            margin: 0;
            border-radius: 0 0 8px 8px;
            color: #333;
        }
        /*
         * COUNTDOWN SECTION
         */
        #countdown {
            margin-top: 30px;
        }
        #countdownTimer {
            font-size: 1.5em;
            margin-top: 20px;
            color: #c0392b;
        }
    </style>
</head>
<body>
    <!-- HEADER -->
    <header>
        <img src="pope_image.jpeg" alt="Pope Image" class="pope-image">
        <img src="pope_logo.png" alt="Pope Coin Logo" class="logo">
        <h1>Pope Coin</h1>
        <p>The Holy Grail of Meme Coins</p>
    </header>

    <!-- NAVIGATION -->
    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#tokenomics">Tokenomics</a></li>
            <li><a href="#roadmap">Roadmap</a></li>
            <li><a href="#how-to-buy">How to Buy</a></li>
            <li><a href="#buy-sol">Buy SOL</a></li>
            <li><a href="#live-price">Live Price</a></li>
            <li><a href="#team">Team</a></li>
            <li><a href="#faq">FAQ</a></li>
            <li><a href="#countdown">Countdown</a></li>
            <li><a href="#community">Community</a></li>
        </ul>
    </nav>

    <!-- ABOUT -->
    <section id="about">
        <h2>About Pope Coin</h2>
        <p>Pope Coin is a revolutionary meme token, bringing fun and faith together in the crypto world. Inspired by the unity and positivity of the global community, Pope Coin aims to deliver both value and virtue to its holders.</p>
        <p>Our mission is to spread hope, humor, and humanitarian aid through crypto innovations and charitable initiatives.</p>
    </section>

    <!-- TOKENOMICS -->
    <section id="tokenomics">
        <h2>Tokenomics</h2>
        <ul>
            <li><strong>Supply:</strong> 1,000,000,000 POPE</li>
            <li><strong>Liquidity:</strong> 50% locked</li>
            <li><strong>Community Driven:</strong> 100%</li>
            <li><strong>Transaction Tax:</strong> 2% for charity, 2% reflection, 1% burn</li>
        </ul>
        <p>By holding Pope Coin, you automatically participate in our reflection rewards and contribute to charity through our built-in transaction tax.</p>
    </section>

    <!-- ROADMAP -->
    <section id="roadmap">
        <h2>Roadmap</h2>
        <p><strong>Phase 1:</strong> Launch 🚀 — Smart contract deployment, community building, and social media presence.</p>
        <p><strong>Phase 2:</strong> Marketing Blitz 📢 — Partnerships, influencer campaigns, and charity collaborations.</p>
        <p><strong>Phase 3:</strong> Exchange Listings 🔥 — Listing on major DEX/CEX platforms and reaching a global audience.</p>
        <p><strong>Phase 4:</strong> Metaverse & NFT Integration 🌐 — Pope-themed NFTs and metaverse events to engage the community.</p>
    </section>

    <!-- HOW TO BUY -->
    <section id="how-to-buy">
        <h2>How to Buy</h2>
        <ol>
            <li><strong>Get a Crypto Wallet</strong>: We recommend MetaMask or Trust Wallet.</li>
            <li><strong>Buy BNB</strong>: Purchase Binance Coin (BNB) on your preferred exchange.</li>
            <li><strong>Swap BNB for Pope Coin</strong>: Use PancakeSwap or your favorite DEX to swap BNB for POPE.</li>
            <li><strong>HODL</strong>: Keep your Pope Coins in your wallet and watch your blessings grow!</li>
        </ol>
    </section>

    <!-- BUY SOL -->
    <section id="buy-sol">
        <h2>Buy Solana (SOL)</h2>
        <p>Invest in Solana alongside Pope Coin! Click below to buy SOL now.</p>
        <a href="https://pump.fun/coin/C9ZKmsvrqHBK1aYRe1bxcCLTAtysHgix3Yh2N9m9pump" target="_blank" class="buy-solana">Buy SOL on Pump.fun</a>
    </section>

    <!-- LIVE PRICE SECTION -->
    <section id="live-price">
        <h2>Live Price</h2>
        <div class="price-box">
            <h3>Current POPE Price:</h3>
            <p><em>Coming soon...</em></p>
            <!-- You can embed a price widget or an iframe from a crypto price API -->
        </div>
        <div class="price-box">
            <h3>Current SOL Price:</h3>
            <p><em>Coming soon...</em></p>
        </div>
    </section>

    <!-- TEAM SECTION -->
    <section id="team">
        <h2>Meet the Team</h2>
        <div class="team-cards">
            <div class="team-card">
                <img src="team_member_1.jpg" alt="Team Member 1">
                <h3>Pope Founder</h3>
                <p>Visionary behind Pope Coin. A meme enthusiast, entrepreneur, and crypto missionary.</p>
            </div>
            <div class="team-card">
                <img src="team_member_2.jpg" alt="Team Member 2">
                <h3>Community Manager</h3>
                <p>Handles our vibrant community channels, ensuring everyone stays informed and engaged.</p>
            </div>
            <div class="team-card">
                <img src="team_member_3.jpg" alt="Team Member 3">
                <h3>Lead Developer</h3>
                <p>Responsible for smart contract development, security audits, and future blockchain integrations.</p>
            </div>
        </div>
    </section>

    <!-- FAQ SECTION -->
    <section id="faq">
        <h2>Frequently Asked Questions</h2>
        <div class="faq-item">
            <h4>What is Pope Coin?</h4>
            <p>Pope Coin is a meme token that combines the fun spirit of meme culture with real-world utility and charitable giving.</p>
        </div>
        <div class="faq-item">
            <h4>How do I hold Pope Coin?</h4>
            <p>You can store your Pope Coins in any wallet that supports Binance Smart Chain (BSC), such as MetaMask or Trust Wallet.</p>
        </div>
        <div class="faq-item">
            <h4>Is Pope Coin a safe investment?</h4>
            <p>All investments carry risk. Pope Coin has locked liquidity and a community-driven approach, but we advise DYOR (Do Your Own Research) before investing.</p>
        </div>
        <div class="faq-item">
            <h4>Where can I learn more?</h4>
            <p>Join our community on Telegram, follow us on Twitter, and stay tuned for official updates on our website.</p>
        </div>
        <div class="faq-item">
            <h4>How long do transactions take?</h4>
            <p>Most transactions on Binance Smart Chain or Solana complete within seconds to a minute, depending on network congestion and wallet settings.</p>
        </div>
    </section>

    <!-- COUNTDOWN SECTION -->
    <section id="countdown">
        <h2>Countdown to Next Milestone</h2>
        <p>Stay tuned for our upcoming major exchange listing!</p>
        <div id="countdownTimer">Loading...</div>
    </section>

    <!-- COMMUNITY -->
    <section id="community">
        <h2>Join Our Community</h2>
        <p>Follow us on Twitter and join our Telegram!</p>
        <p>
            <a href="https://twitter.com" target="_blank" class="btn">Follow on Twitter</a>
            <a href="https://t.me/+amebPx7tzuA0MGZk" target="_blank" class="btn">Join Telegram</a>
        </p>
    </section>

    <!-- FOOTER -->
    <footer>
        <p>&copy; 2025 Pope Coin. All Rights Reserved. Powered by Faith and Fun.</p>
    </footer>

    <!-- OPTIONAL SCRIPT FOR FAQ ACCORDION AND COUNTDOWN -->
    <script>
        // FAQ accordion
        const faqItems = document.querySelectorAll('.faq-item');
        faqItems.forEach(item => {
            const question = item.querySelector('h4');
            const answer = item.querySelector('p');

            question.addEventListener('click', () => {
                if (answer.style.display === 'block') {
                    answer.style.display = 'none';
                } else {
                    answer.style.display = 'block';
                }
            });
        });

        // Countdown Script
        // Set a future date for the next milestone
        const targetDate = new Date("December 31, 2025 23:59:59").getTime();

        const countdownTimerEl = document.getElementById('countdownTimer');

        function updateCountdown() {
            const now = new Date().getTime();
            const distance = targetDate - now;

            if (distance < 0) {
                countdownTimerEl.innerHTML = "Milestone reached!";
                return;
            }

            const days = Math.floor(distance / (1000 * 60 * 60 * 24));
            const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
            const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
            const seconds = Math.floor((distance % (1000 * 60)) / 1000);

            countdownTimerEl.innerHTML = `Days: ${days} | Hours: ${hours} | Minutes: ${minutes} | Seconds: ${seconds}`;
        }

        // Update every second
        setInterval(updateCountdown, 1000);
    </script>

</body>
</html>
