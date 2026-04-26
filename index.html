<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Myzee Catalog Holder</title>

    @vite(['resources/css/app.css'])
</head>

<body>

<div class="background"></div>

<div class="container">
    <h1>📦 Sailor Piece - Pricelist</h1>

    <!-- 🔍 SEARCH -->
    <input type="text" id="search" placeholder="Search item..." class="search-box">

    <!-- 📑 TABS -->
    <div class="tabs">
        <button class="tab active" data-tab="sets">Sets</button>
        <button class="tab" data-tab="items">Items</button>
        <button class="tab" data-tab="crate">Crate</button>
        <button class="tab" data-tab="chest">Chest</button>
        <button class="tab" data-tab="ascend">Ascend</button>
    </div>

    <!-- 🧩 SETS -->
    <div class="tab-content active" id="sets">
        <div class="card">
            <div class="price">2K</div>
            <div class="item">• Limitless Sorcerer (Gojo V1)</div>
            <div class="item">• Curse King (Sukuna V1)</div>
            <div class="item">• Manipulator (Aizen)</div>
        </div>

        <div class="card">
            <div class="price">2K → 3K (+ F Move)</div>
            <div class="item">• Strongest Of Today (Gojo V2)</div>
            <div class="item">• Strongest In History (Sukuna V2)</div>
            <div class="item">• Blessed Maiden</div>
            <div class="item">• Corrupt Knight (Alter)</div>
            <div class="item">• Strongest Shinobi (Madara)</div>
            <div class="item">• True Aizen (Aizen)</div>
            <div class="item">• Gilgamesh (Gilgamesh)</div>
        </div>

        <div class="card">
            <div class="price">3K</div>
            <div class="item">• Shadow (CID V1)</div>
            <div class="item">• Atomic (CID V2)</div>
        </div>

        <div class="card special">
            <div class="price">Special Sets</div>
            <div class="item">• Great Mage (Frieren) — 10K</div>
            <div class="item">• The World (Dio) — 10K</div>
            <div class="item">• Cosmic Being (Garou) — 10K</div>
        </div>
    </div>

    <!-- ITEMS -->
    <div class="tab-content" id="items">
        <div class="card">
            <div class="item">• Bloodline Stone — 1K</div>
            <div class="item">• Race Reroll — 50P</div>
            <div class="item">• Trait Reroll — 50P</div>
            <div class="item">• Clan Reroll — 500P</div>
        </div>
    </div>

    <!-- CRATE -->
    <div class="tab-content" id="crate">
        <div class="card">
            <div class="item">• Cosmetic Crate — 50P</div>
            <div class="item">• Aura Crate — 50P</div>
        </div>
    </div>

    <!-- CHEST -->
    <div class="tab-content" id="chest">
        <div class="card">
            <div class="item">• Mythical Chest — 500P</div>
            <div class="item">• Legendary Chest — 500P</div>
        </div>
    </div>

    <!-- ASCEND -->
    <div class="tab-content" id="ascend">
        <div class="card">
            <div class="item">• II → IV : 5K</div>
            <div class="item">• V → VII : 10K</div>
        </div>
    </div>
</div>

<!-- WA BUTTON -->
<a href="https://wa.me/6281234061011" target="_blank" class="wa-button">
    💬 Contact
</a>

<!-- 🎵 AUDIO -->
<audio id="bg-music" loop>
    <source src="{{ asset('music/Leisure.mp3') }}" type="audio/mpeg">
</audio>

<!-- 🎧 BUTTON -->
<div class="music-control" id="music-btn">🔇</div>

<!-- ⚙️ SCRIPT -->
<script>
// ================= TAB =================
const tabs = document.querySelectorAll(".tab");
const contents = document.querySelectorAll(".tab-content");

tabs.forEach(tab => {
    tab.addEventListener("click", () => {
        tabs.forEach(t => t.classList.remove("active"));
        contents.forEach(c => c.classList.remove("active"));

        tab.classList.add("active");
        document.getElementById(tab.dataset.tab).classList.add("active");
    });
});

// ================= SEARCH =================
document.getElementById("search").addEventListener("keyup", function() {
    let value = this.value.toLowerCase();

    contents.forEach(content => {
        let cards = content.querySelectorAll(".card");
        let hasMatch = false;

        cards.forEach(card => {
            let text = card.innerText.toLowerCase();
            let match = text.includes(value);
            card.style.display = match ? "block" : "none";
            if(match) hasMatch = true;
        });

        if (value && hasMatch) {
            contents.forEach(c => c.classList.remove("active"));
            tabs.forEach(t => t.classList.remove("active"));

            content.classList.add("active");
            document.querySelector(`[data-tab="${content.id}"]`).classList.add("active");
        }
    });
});

// ================= MUSIC =================
const music = document.getElementById("bg-music");
const btn = document.getElementById("music-btn");

let isPlaying = false;

// awal OFF
btn.innerText = "🔇";

music.volume = 0.5;

// Function to start music
const startMusic = () => {
    music.play().then(() => {
        isPlaying = true;
        btn.innerText = "🔊";
    });

    // Remove listeners after first play
    window.removeEventListener("click", startMusic);
    window.removeEventListener("touchstart", startMusic);
    window.removeEventListener("keydown", startMusic);
};

// Set up listeners for user interaction
window.addEventListener("click", startMusic);
window.addEventListener("touchstart", startMusic);
window.addEventListener("keydown", startMusic);

// toggle
btn.addEventListener("click", () => {
    if (isPlaying) {
        music.pause();
        btn.innerText = "🔇";
    } else {
        music.play();
        btn.innerText = "🔊";
    }
    isPlaying = !isPlaying;
});
</script>

</body>
</html>