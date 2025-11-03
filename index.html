<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile Talent</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
    <style>
        :root {
            --card-bg: rgba(28, 28, 28, 0.9);
            --text-color: #fff;
            --muted-text: #bbb;
            --accent-color: #ff4500;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }

        body {
            background: linear-gradient(-45deg, #0f0f0f, #1b1b1b, #111, #1a1a1a);
            background-size: 400% 400%;
            animation: gradientBG 12s ease infinite;
            color: var(--text-color);
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            overflow-y: auto;
            position: relative;
            padding: 3rem 0 3rem 0;
            overflow-x: hidden;
            background-attachment: fixed;
        }

        @keyframes gradientBG {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        .particles {
            position: absolute;
            width: 100%;
            height: 100%;
            top: 0;
            left: 0;
            overflow: hidden;
            z-index: 0;
        }

        .particle {
            position: absolute;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 50%;
            animation: floatParticle linear infinite;
        }

        @keyframes floatParticle {
            from { transform: translateY(100vh) scale(0.5); opacity: 0; }
            25% { opacity: 1; }
            to { transform: translateY(-10vh) scale(1); opacity: 0; }
        }

        .container {
            width: 90%;
            max-width: 850px;
            background: var(--card-bg);
            padding: 2rem;
            border-radius: 20px;
            box-shadow: 0 0 30px rgba(0, 0, 0, 0.6);
            position: relative;
            z-index: 1;
            animation: popIn 0.6s ease;
        }

        @keyframes popIn {
            from { transform: scale(0.9); opacity: 0; }
            to { transform: scale(1); opacity: 1; }
        }

        nav {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 0.5rem;
            margin: 1.5rem 0 1.5rem 0;
        }

        nav button {
            background: #333;
            color: var(--text-color);
            border: none;
            padding: 0.5rem 1rem;
            border-radius: 10px;
            cursor: pointer;
            transition: background 0.3s, transform 0.3s;
        }

        nav button:hover {
            background: #555;
            transform: translateY(-3px);
        }

        .profile-header {
            display: flex;
            align-items: center;
            gap: 1rem;
            margin-bottom: 2rem;
            animation: fadeInUp 0.7s ease;
        }

        .profile-header img {
            width: 100px;
            height: 100px;
            object-fit: cover;
            border-radius: 50%;
            border: 3px solid #555;
            animation: float 3s ease-in-out infinite;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-5px); }
        }

        .profile-info h2 {
            font-size: 1.5rem;
            font-weight: 600;
        }

        .profile-info p {
            font-size: 0.9rem;
            color: var(--muted-text);
        }

        .page {
            display: none;
            animation: fadeIn 0.5s ease;
            opacity: 0;
            transform: translateY(10px);
            transition: opacity 0.4s ease, transform 0.4s ease;
        }

        .page p {
            margin-bottom: 1rem;
            line-height: 1.8;
            color: #d4d4d4;
            animation: fadeInUp 0.6s ease both;
            line-height: 1.8;
            text-align: justify;
        }

        .page.active {
            display: block;
            opacity: 1;
            transform: translateY(0);
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(10px); }
            to { opacity: 1; transform: translateY(0); }
        }

        h1 {
            margin-bottom: 1rem;
        }

        /* proof grid similar to simpen.php */
        .proof-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
            gap: 14px;
            margin-top: 18px;
        }

        .thumb {
            background: linear-gradient(180deg, rgba(255, 255, 255, 0.01), rgba(255, 255, 255, 0.015));
            border-radius: 10px;
            overflow: hidden;
            cursor: pointer;
            border: 1px solid rgba(255, 255, 255, 0.03);
            transition: transform .35s cubic-bezier(.2, .9, .2, 1), box-shadow .35s;
            box-shadow: 0 8px 22px rgba(0, 0, 0, 0.6);
            display: flex;
            flex-direction: column;
            align-items: stretch;
        }

        .thumb img {
            width: 100%;
            height: 110px;
            object-fit: cover;
            display: block;
            transition: transform .35s ease;
        }

        .thumb .meta {
            padding: 8px 10px;
            font-size: 0.85rem;
            color: var(--muted-text);
            opacity: 1;
            transform: translateY(0);
            background: rgba(0,0,0,0.3);
        }

        .thumb:hover {
            transform: translateY(-8px);
        }

        .thumb:hover img {
            transform: scale(1.04);
        }

        .thumb:hover .meta {
            transform: translateY(0);
            opacity: 1;
            color: #d6d6d6;
        }

        .filter-btn {
            background: #222;
            color: #fff;
            border: 1px solid #444;
            padding: 0.4rem 0.9rem;
            border-radius: 8px;
            cursor: pointer;
            font-size: 0.85rem;
            transition: all 0.25s ease;
        }

        .filter-btn:hover {
            background: #555;
            border-color: #555;
            transform: translateY(-2px);
        }

        .filter-btn.active {
            background: #555;
            border-color: #555;
            color: #fff;
        }

        #no-result {
            margin-top: 1rem;
            color: #bbb;
            font-style: italic;
            display: none;
        }

        /* Modal & overlay arrows */
        .modal {
          display: none;
          position: fixed;
          z-index: 999;
          top: 0;
          left: 0;
          width: 100%;
          height: 100%;
          background: rgba(0,0,0,0.95);
          justify-content: center;
          align-items: center;
          overflow-y: auto;
          animation: fadeIn 0.3s ease;
          padding: 40px 20px;
          box-sizing: border-box;
        }

        .modal-content {
          max-width: 90%;
          display: flex;
          flex-direction: column;
          align-items: center;
          gap: 20px;
        }

        .modal-images {
          display: grid;
          grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
          gap: 12px;
          width: 100%;
          max-width: 300px;
          margin: 0 auto;
        }

        .modal-images img {
          width: 100%;
          height: auto;
          border-radius: 10px;
          object-fit: cover;
          display: block;
        }

        .modal-caption {
          background: rgba(0,0,0,0.4);
          backdrop-filter: blur(6px);
          color: #fff;
          font-size: 1rem;
          padding: 10px 16px;
          border-radius: 8px;
          text-align: center;
          max-width: 90%;
        }

        .fancy-link {
          position: relative;
          color: #fff;
          text-decoration: none;
          font-weight: 500;
          padding-right: 24px;
          transition: color 0.3s ease;
        }

        .f-link::after {
          content: url('img/tele.png');
          width: 10px;
          height: 10px;
          position: absolute;
          right: 0;
          opacity: 0;
          transform: translateX(-6px);
          transition: all 0.4s ease;
        }

        .f-link:hover,
        .f-link:focus {
          color: #a5b4ff;
        }

        .f-link:hover::after,
        .f-link:focus::after {
          opacity: 1;
          transform: translateX(0);
        }


        /* Arrows (overlay on images) */
        .arrow {
          position: fixed;
          top: 50%;
          transform: translateY(-50%);
          font-size: 42px;
          color: white;
          cursor: pointer;
          background: rgba(0, 0, 0, 0.45);
          border-radius: 50%;
          padding: 10px 16px;
          transition: all 0.3s ease;
          user-select: none;
          z-index: 2000;
        }
        .arrow:hover {
          background: rgba(255, 255, 255, 0.25);
          transform: translateY(-50%) scale(1.1);
        }
        #prevPost { left: 15px; }
        #nextPost { right: 15px; }

        .smuse {
          display: grid;
          gap: 25px;
          grid-template-columns: repeat(auto-fit, minmax(140px, 1fr));
        }

        .smuse-item {
          text-align: center;
        }

        .smuse-item .smuse-wrapper {
          width: 100%;
          aspect-ratio: 1 / 1;
          overflow: hidden;
          border-radius: 12px;
          transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .smuse-item .smuse-wrapper img {
          width: 100%;
          height: 100%;
          object-fit: cover;
          border-radius: 12px;
          transition: transform 0.3s ease, box-shadow 0.3s ease;
          display: block;
        }

        .smuse-item:hover img {
          transform: scale(1.05);
          box-shadow: 0 10px 25px rgba(0,0,0,0.2);
        }

        .smuse-item p {
          margin: 0;
          font-size: 14px;
          font-weight: 300;
          color: rgb(255, 255, 255);
          text-align: center;
          }

        /* Responsive adjustments */
        @media (max-width: 768px) {
          .smuse-item img {
            height: 120px;
          }
        }

        @media (max-width: 480px) {
          .smuse {
            grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
            gap: 15px;
          }

          .smuse-item img {
            height: 100px;
          }

          .smuse-item p {
            font-size: 12px;
          }
        }

        @media (max-width: 600px) {
          .arrow {
            font-size: 32px;
            padding: 8px 12px;
          }
          #prevPost { left: 8px; }
          #nextPost { right: 8px; }
        }

    </style>
</head>
<body>
    <div class="particles" id="particles"></div>

    <div class="container">
        <div class="profile-header">
            <img src="img/icon.jpg" alt="Foto Profil">
            <div class="profile-info">
                <h2 class="kmh">Khamran Hagifar</h2>
                <p class="par"><a href="https://t.me/kooenig" class="f-link" style="text-decoration: none; color: #bbb;">@Kooenig</a> on Telegram</p>
            </div>
        </div>
        <nav>
            <button onclick="showPage('profile')">Profile</button>
            <button onclick="showPage('available')">Available</button>
            <button onclick="showPage('introduction')">Introduction</button>
            <button onclick="showPage('proof')">Testimonial</button>
        </nav>

        <div id="profile" class="page active">
            <h1>Profile</h1>
            <p>Name: Khamran Hagifar</p>
            <p>Age: Major, 22+</p>
            <p>Main ava: Lee Jeno</p>
            <p>Side ava: Jay Park, Theo James, Lee Juyeon, Kim Mingyu, Choi San, Scoups, Simon Ghost Riley, Leon S. Kennedy, Joong Archen, Pond Naravit</p>
            <p>MBTI: ENFJ</p>
            <p>Relationship: BxG, BxB, BxNB, Family and Friends Rent</p>
            <p>Position: Dominant</p>
            <p>Love Language: Act of Service, Physical Touch, Quality Time, Receiving Gift</p>
            <p>Language: Indonesia, broken Eng, Sundanese</p>
            <p>Platform: Whatsapp & Line</p>
            </p>

            <h1> Side Muse </h1>
            <div class="smuse">
              <div class="smuse-item">
                <div class="smuse-wrapper">
                  <img src="img/jay.jpg" alt="Jay Park">
                </div>
                <p>Jay Park</p>
              </div>
              <div class="smuse-item">
                <div class="smuse-wrapper">
                  <img src="img/Juyeon.jpg" alt="Lee Juyeon">
                </div>
                <p>Lee Juyeon</p>
              </div>
              <div class="smuse-item">
                <div class="smuse-wrapper">
                  <img src="img/mingyu.jpg" alt="Kim Mingyu">
                </div>
                <p>Kim Mingyu</p>
              </div>
              <div class="smuse-item">
                <div class="smuse-wrapper">
                  <img src="img/scoups.jpg" alt="Scoups">
                </div>
                <p>Scoups</p>
              </div>
              <div class="smuse-item">
                <div class="smuse-wrapper">
                  <img src="img/SAN.jpg" alt="Choi San">
                </div>
                <p>Choi San</p>
              </div>
              <div class="smuse-item">
                <div class="smuse-wrapper">
                  <img src="img/theo.jpg" alt="Theo James">
                </div>
                <p>Theo James</p>
              </div>
              <div class="smuse-item">
                <div class="smuse-wrapper">
                  <img src="img/scoups.jpg" alt="Scoups">
                </div>
                <p>Scoups</p>
              </div>
              <div class="smuse-item">
                <div class="smuse-wrapper">
                  <img src="img/ghost.jpg" alt="Simon Ghost Riley">
                </div>
                <p>Simon "Ghost" Riley</p>
              </div>
              <div class="smuse-item">
                <div class="smuse-wrapper">
                  <img src="img/leon.jpg" alt="Leon S. Kennedy">
                </div>
                <p>Leon S. Kennedy</p>
              </div>
            </div>
        </div>

        <div id="available" class="page">
            <h1>Available</h1>

            <h2 style="margin-top:1rem; margin-bottom:.5rem; font-size:1.1rem;">Basic Request</h2>
            <ul style="list-style:none; padding-left:1rem; margin-bottom:1rem;">
                <li>- Profile Pictures, Personality, Typing, Change Name, Biography, etc</li>
                <li>- Matching Ava/Bio</li>
            </ul>

            <!-- <h2 style="margin-top:1rem; margin-bottom:.5rem; font-size:1.1rem;">Real Life Things</h2>
            <ul style="list-style:none; padding-left:1rem; margin-bottom:1rem;">
                
                <li>- Otp / Sleepcall Mute</li>
                <li>- Voice Note</li>
            </ul> -->

            <h2 style="margin-top:1rem; margin-bottom:.5rem; font-size:1.1rem">Any Date (Bills on Cust)</h2>
            <ul style="list-style:none; padding-left:1rem; margin-bottom:1rem;">
                <li>- Reading Date (Book, Wattpad, Alternative Universe, etc)</li>
                <li>- Movie Date (Rave)</li>
                <li>- Cigarette Date</li>
                <li>- Food Date</li>
                <li>- Game Date (Plato, Roblox, Telegram bot)</li>
            </ul>

            <h2 style="margin-top:1rem; margin-bottom:.5rem; font-size:1.1rem;">Extra</h2>
            <ul style="list-style:none; padding-left:1rem; margin-bottom:1rem;">
                <li>- Pap Daily Activity (Faceless & Muse)</li>
                <li>- PDA only V/VIP</li>
                <li>- Fotbar, Vidbar, Manips, etc</li>
                <li>- Make a Content</li>
                <li>- Imagine SFW</li>
                <li>- In Character (Ask First)</li>
                <li>- Lovey-Dovey and Love-Hate Relationship</li>
                <li>- Stay Up Late Until 00.00 (Depends)</li>
            </ul>
        </div>

        <div id="introduction" class="page">
            <h1>Introduction</h1>
            <p>Hi, sweetheart! Sebelum ngenalin saya lebih jauh, alangkah baiknya kalau saya memperkenalkan diri terlebih dahulu. I'm Ozero Flint, usually called Oze or Ozi for short. But for my future prince(ss), you may call me by another name.</p>

            <p>Saya orangnya cemburuan, kalau misalkan kamu nyebut nama orang lain di roomchat kita, saya bakalan ngambek seharian. Posesif juga, ngga mau pasangannya deket sama orang lain. I'm also a good listener, kamu ga perlu malu buat share tmi atau misuh-misuh sama saya. Saya orangnya terbuka, mudah berbaur sama orang-orang. Jadi ga perlu takut bakalan canggung ataupun mati topik kalau sama saya. Saya bisa jadi temen curhat, temen ghibah, atau apapun itu. Kadang saya manja, tapi lebih sering ngemanjain. I also have a low sense of humor, akibatnya jadi sering ngetawain hal-hal yang kata orang mah biasa aja.</p>

            <p>Tipe orang yang gampang kangen, kalau kamu ilang tanpa kabar, bakalan saya cariin terus spam roomchat kamu sampai beribu-ribu pesan. Saya kalau lagi salting suka pake harshword sama capslock, ditambah stiker-stiker alay. Tapi kalau kamu keganggu, langsung bilang aja ya, sayang? Biar kita sama-sama nyaman.</p>

            <p>Selain itu, saya juga sering pamerin pacar ke orang-orang, soalnya mubazir kalau punya pacar tapi ga dipamerin ke orang-orang, kan? Saya suka bales bbc satu persatu, saya jamin ga bakalan ada bbc yang kelewat.</p>

            <p>Saya suka musik dan nonton film, semua genre saya suka. We can exchange playlist if you want and talk about movies, or we can also exchange our hearts. If you're interested, please just tap my roomchat, sweetheart. I'm waiting for you, see you.</p>
        </div>

        <!-- Di dalam #proof -->
        <div id="proof" class="page">
          <h1>What They Say</h1>

          <!-- Filter button -->
          <div style="margin-bottom: 1rem; display: flex; gap: 0.5rem; flex-wrap: wrap;">
            <button class="filter-btn" data-filter="all">All</button>
            <button class="filter-btn" data-filter="BxG">BxG</button>
            <button class="filter-btn" data-filter="BxB">BxB</button>
            <button class="filter-btn" data-filter="BxNB">BxNB</button>
          </div>

          <div class="proof-grid" id="proof-grid">
            <div class="thumb" data-category="BxG" data-caption="BxG as Lover.">
              <img src="img/proof.jpg" alt="BxG as Lover">
              <div class="meta">BxG as Lover.</div>
              <div class="images" style="display:none;">
                <img src="img/proof.jpg">
              </div>
            </div>

            <div class="thumb" data-category="BxG" data-caption="BxG as Lover.">
              <img src="img/proof1.jpg" alt="BxG as Lover">
              <div class="meta">BxG as Lover.</div>
              <div class="images" style="display:none;">
                <img src="img/proof1.jpg">
              </div>
            </div>

            <div class="thumb" data-category="BxG" data-caption="BxG as Lover.">
              <img src="img/proof2.jpg" alt="BxG as Lover">
              <div class="meta">BxG as Lover.</div>
              <div class="images" style="display:none;">
                <img src="img/proof2.jpg">
              </div>
            </div>

            <div class="thumb" data-category="BxG" data-caption="BxG as Father.">
              <img src="img/proof3.jpg" alt="BxG as Father">
              <div class="meta">BxG as Father.</div>
              <div class="images" style="display:none;">
                <img src="img/proof3.jpg">
              </div>
            </div>

            <div class="thumb" data-category="BxB" data-caption="BxB as Lover.">
              <img src="img/proof4.jpg" alt="BxB as Lover">
              <div class="meta">BxB as Lover.</div>
              <div class="images" style="display:none;">
                <img src="img/proof4.jpg">
              </div>
            </div>

            <div class="thumb" data-category="BxG" data-caption="BxG as Lover.">
              <img src="img/proof5.jpg" alt="BxG as Lover">
              <div class="meta">BxG as Lover.</div>
              <div class="images" style="display:none;">
                <img src="img/proof5.jpg">
              </div>
            </div>

            <div class="thumb" data-category="BxG" data-caption="BxG as Lover.">
              <img src="img/proof6.jpg" alt="BxG as Lover">
              <div class="meta">BxG as Lover.</div>
              <div class="images" style="display:none;">
                <img src="img/proof6.jpg">
              </div>
            </div>

            <div class="thumb" data-category="BxG" data-caption="BxG as Lover.">
              <img src="img/proof7.jpg" alt="BxG as Lover">
              <div class="meta">BxG as Lover.</div>
              <div class="images" style="display:none;">
                <img src="img/proof7.jpg">
              </div>
            </div>

            <div class="thumb" data-category="BxG" data-caption="BxG as Lover.">
              <img src="img/proof8.jpg" alt="BxG as Lover">
              <div class="meta">BxG as Lover.</div>
              <div class="images" style="display:none;">
                <img src="img/proof8.jpg">
              </div>
            </div>

            <div class="thumb" data-category="BxG" data-caption="BxG as Lover.">
              <img src="img/proof9.jpg" alt="BxG as Lover">
              <div class="meta">BxG as Lover.</div>
              <div class="images" style="display:none;">
                <img src="img/proof9.jpg">
              </div>
            </div>

          </div>

          <div id="no-result">Belum ada testimonial untuk kategori ini.</div>
        </div>

        <!-- Modal viewer -->
        <div id="modal" class="modal">
          <span id="prevPost" class="arrow">&#10094;</span>
          <div class="modal-content">
            <div id="modalImages" class="modal-images"></div>
            <div id="modalCaption" class="modal-caption"></div>
          </div>
          <span id="nextPost" class="arrow">&#10095;</span>
        </div>

<script>
function showPage(pageId) {
  document.querySelectorAll(".page").forEach(page => page.classList.remove("active"));
  document.getElementById(pageId).classList.add("active");
}

// === MODAL GALERI ===
const modal = document.getElementById("modal");
const modalImages = document.getElementById("modalImages");
const modalCaption = document.getElementById("modalCaption");
const thumbs = document.querySelectorAll(".thumb");
const nextArrow = document.getElementById("nextPost");
const prevArrow = document.getElementById("prevPost");

let visiblePosts = Array.from(thumbs);
let currentPost = 0;

// Filter
document.querySelectorAll(".filter-btn").forEach(btn => {
  btn.addEventListener("click", () => {
    const filter = btn.dataset.filter;
    visiblePosts = Array.from(thumbs).filter(t =>
      filter === "all" || t.dataset.category === filter
    );
  });
});

// Klik thumbnail → buka modal
thumbs.forEach((t, i) => {
  t.addEventListener("click", () => {
    const activeFilter = document.querySelector(".filter-btn.active");
    const filter = activeFilter ? activeFilter.dataset.filter : "all";
    visiblePosts = Array.from(thumbs).filter(tt =>
      filter === "all" || tt.dataset.category === filter
    );
    currentPost = visiblePosts.indexOf(t);
    openModal();
  });
});

function openModal() {
  modal.style.display = "flex";
  document.body.style.overflow = "hidden";
  updateModal();
}

function closeModal() {
  modal.style.display = "none";
  document.body.style.overflow = "";
}

function updateModal() {
  const post = visiblePosts[currentPost];
  const images = post.querySelectorAll(".images img");
  modalImages.innerHTML = "";
  images.forEach(img => {
    const clone = document.createElement("img");
    clone.src = img.src;
    modalImages.appendChild(clone);
  });
  modalCaption.textContent = post.dataset.caption || "";
  modal.scrollTop = 0;
}

// Panah navigasi antar postingan
nextArrow.addEventListener("click", () => {
  currentPost = (currentPost + 1) % visiblePosts.length;
  updateModal();
});
prevArrow.addEventListener("click", () => {
  currentPost = (currentPost - 1 + visiblePosts.length) % visiblePosts.length;
  updateModal();
});

// Klik di luar modal → tutup
modal.addEventListener("click", (e) => {
  if (e.target === modal) closeModal();
});

// Keyboard shortcut
document.addEventListener("keydown", (e) => {
  if (modal.style.display === "flex") {
    if (e.key === "ArrowLeft") prevArrow.click();
    if (e.key === "ArrowRight") nextArrow.click();
    if (e.key === "Escape") closeModal();
  }
});

// Particles
const particlesContainer = document.getElementById('particles');
for (let i = 0; i < 20; i++) {
    const particle = document.createElement('div');
    particle.classList.add('particle');
    const size = Math.random() * 10 + 5;
    particle.style.width = `${size}px`;
    particle.style.height = `${size}px`;
    particle.style.left = `${Math.random() * 100}%`;
    particle.style.animationDuration = `${5 + Math.random() * 10}s`;
    particlesContainer.appendChild(particle);
}

window.addEventListener("scroll", () => {
const scrolled = window.scrollY;
document.querySelectorAll(".profile-header, .kmh, .par").forEach(el => {
    el.style.transform = `translateY(${scrolled * 0.1}px)`;
});
});


// Filter testimonial
const buttons = document.querySelectorAll(".filter-btn");
const cards = document.querySelectorAll("#proof-grid .thumb");
const noResultMsg = document.getElementById("no-result");

buttons.forEach(btn => {
  btn.addEventListener("click", () => {
    buttons.forEach(b => b.classList.remove("active"));
    btn.classList.add("active");

    const filter = btn.getAttribute("data-filter");
    let visibleCount = 0;

    cards.forEach(card => {
      if (filter === "all" || card.getAttribute("data-category") === filter) {
        card.style.display = "";
        visibleCount++;
      } else {
        card.style.display = "none";
      }
    });

    noResultMsg.style.display = visibleCount === 0 ? "block" : "none";
  });
});

</script>


</body>
</html>

