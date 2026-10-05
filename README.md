# spookypetsstore
A curated digital boutique and affiliate storefront for spooky pets and witchy aesthetics.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Familiar's Coven | Spooky Pet & Witchy Boutique</title>
    <style>
        :root {
            --bg-color: #0b090a;
            --card-bg: #161a1d;
            --accent-purple: #9d4edd;
            --accent-pink: #f72585;
            --text-main: #f8f9fa;
            --text-muted: #adb5bd;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-main);
            font-family: 'Courier New', Courier, monospace;
            margin: 0;
            padding: 0;
        }

        header {
            text-align: center;
            padding: 3rem 1rem;
            background: linear-gradient(to bottom, #10002b, var(--bg-color));
            border-bottom: 1px solid #240046;
        }

        header h1 {
            font-size: 2.5rem;
            margin: 0;
            color: var(--accent-purple);
            letter-spacing: 2px;
            text-shadow: 0 0 10px rgba(157, 78, 221, 0.4);
        }

        header p {
            color: var(--text-muted);
            font-size: 1.1rem;
            margin-top: 0.5rem;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }

        .category-title {
            border-bottom: 2px dashed var(--accent-purple);
            padding-bottom: 0.5rem;
            margin-bottom: 1.5rem;
            font-size: 1.5rem;
            color: var(--accent-pink);
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 2rem;
            margin-bottom: 3rem;
        }

        .card {
            background-color: var(--card-bg);
            border: 1px solid #3c096c;
            border-radius: 8px;
            overflow: hidden;
            display: flex;
            flex-direction: column;
            transition: transform 0.2s, box-shadow 0.2s;
        }

        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 0 15px rgba(157, 78, 221, 0.3);
        }

        .card-img-placeholder {
            background-color: #240046;
            height: 200px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--text-muted);
            font-size: 0.9rem;
        }

        .card-content {
            padding: 1.5rem;
            display: flex;
            flex-direction: column;
            flex-grow: 1;
        }

        .card-title {
            font-size: 1.2rem;
            margin: 0 0 0.5rem 0;
            color: var(--text-main);
        }

        .card-desc {
            font-size: 0.9rem;
            color: var(--text-muted);
            margin-bottom: 1.5rem;
            flex-grow: 1;
        }

        .btn {
            background-color: var(--accent-purple);
            color: white;
            text-align: center;
            padding: 0.75rem;
            border-radius: 4px;
            text-decoration: none;
            font-weight: bold;
            transition: background-color 0.2s;
        }

        .btn:hover {
            background-color: #7b2cbf;
        }

        footer {
            text-align: center;
            padding: 2rem;
            background-color: #050305;
            color: var(--text-muted);
            font-size: 0.8rem;
            border-top: 1px solid #161a1d;
        }
    </style>
</head>
<body>

    <header>
        <h1>🌙 The Familiar's Coven 🔮</h1>
        <p>Curated Spooky Goods & Occult Comforts for You & Your Familiars</p>
    </header>

    <div class="container">
        
        <!-- SECTION 1: SPOOKY PETS -->
        <h2 class="category-title">🐾 Familiar Essentials (Spooky Pets)</h2>
        <div class="grid">
            
            <div class="card">
                <div class="card-img-placeholder">[ Product Image ]</div>
                <div class="card-content">
                    <h3 class="card-title">Celestial Velvet Bat Cat Harness</h3>
                    <p class="card-desc">Keep your little black cat or spooky pup secure on midnight walks with gothic winged harness design.</p>
                    <a href="YOUR_AMAZON_AFFILIATE_LINK_HERE" class="btn" target="_blank">Summon on Amazon</a>
                </div>
            </div>

            <div class="card">
                <div class="card-img-placeholder">[ Product Image ]</div>
                <div class="card-content">
                    <h3 class="card-title">Gothic Coffin Pet Bed</h3>
                    <p class="card-desc">Plush, pitch-black velvet coffin-shaped lounger fit for royalty (or heavy sleepers like Jinxy).</p>
                    <a href="YOUR_AMAZON_AFFILIATE_LINK_HERE" class="btn" target="_blank">Summon on Amazon</a>
                </div>
            </div>

        </div>

        <!-- SECTION 2: WITCHY & SPOOKY GIRL -->
        <h2 class="category-title">🕯️ Witchy & Spooky Aesthetic</h2>
        <div class="grid">
            
            <div class="card">
                <div class="card-img-placeholder">[ Product Image ]</div>
                <div class="card-content">
                    <h3 class="card-title">Moon Phase Glass Teapot & Warmer</h3>
                    <p class="card-desc">Brew your favorite dark roast or loose-leaf herbal potions under the watchful phases of the moon.</p>
                    <a href="YOUR_AMAZON_AFFILIATE_LINK_HERE" class="btn" target="_blank">Summon on Amazon</a>
                </div>
            </div>

            <div class="card">
                <div class="card-img-placeholder">[ Product Image ]</div>
                <div class="card-content">
                    <h3 class="card-title">Holographic Tarot Card Deck & Guide</h3>
                    <p class="card-desc">Stunning iridescent card stock with sleek minimalist gold foil detailing for daily guidance.</p>
                    <a href="YOUR_AMAZON_AFFILIATE_LINK_HERE" class="btn" target="_blank">Summon on Amazon</a>
                </div>
            </div>

        </div>

    </div>

    <footer>
        <p>Disclaimer: As an Amazon Associate, I earn from qualifying purchases. (Paid Link / #ad)</p>
    </footer>

</body>
</html>
<!-- refreshed -->
