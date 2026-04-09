
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portal Kelas 7 Andromeda</title>
    
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&family=Kalam:wght@400;700&family=Playfair+Display:italic,wght@700&display=swap" rel="stylesheet">
    
    <style>
        :root {
            --primary: #0f172a;
            --accent: #f59e0b;
            --bg-gradient: linear-gradient(135deg, #f8fafc 0%, #e2e8f0 100%);
            --white: #ffffff;
        }

        * { margin: 0; padding: 0; box-sizing: border-box; scroll-behavior: smooth; }

        body {
            font-family: 'Poppins', sans-serif;
            background: var(--bg-gradient);
            color: #334155;
            overflow-x: hidden;
        }

        /* NAVBAR */
        nav {
            position: fixed;
            top: 0; width: 100%;
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            padding: 15px 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
            z-index: 1000;
        }

        .logo { font-weight: 700; font-size: 1.4rem; color: var(--primary); }
        .logo span { color: var(--accent); }

        .nav-links { list-style: none; display: flex; gap: 20px; }
        .nav-links a {
            text-decoration: none;
            color: #64748b;
            font-weight: 600;
            font-size: 0.9rem;
        }

        /* HERO */
        .hero {
            height: 45vh;
            background: linear-gradient(rgba(15, 23, 42, 0.7), rgba(15, 23, 42, 0.7)), url('https://images.unsplash.com/photo-1523050854058-8df90110c9f1?q=80&w=1500') center/cover;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            color: white;
            text-align: center;
        }

        .hero h1 { font-size: 3rem; }

        /* SECTIONS */
        section { padding: 80px 5%; }
        .section-title { text-align: center; margin-bottom: 40px; font-size: 2.2rem; }

        .cards-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }

        .card {
            background: var(--white);
            padding: 25px;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
            border-top: 5px solid var(--accent);
        }

        .card h3 { 
            margin-bottom: 15px; 
            color: var(--primary); 
            text-align: center;
            border-bottom: 2px solid #f1f5f9;
            padding-bottom: 10px;
        }

        .card ul { list-style: none; }
        .card li { 
            font-size: 1rem; 
            padding: 8px 0; 
            border-bottom: 1px solid #f8fafc;
            text-align: center;
        }

        /* TEKS TEBAL (BOLD) UNTUK ISI JADWAL */
        .bold-text {
            font-weight: 700; /* Membuat teks nama & mapel lebih tebal */
            color: var(--primary);
        }

        /* GALERI POLAROID */
        .photo-wall { 
            display: flex; 
            justify-content: center; 
            gap: 20px; 
            flex-wrap: wrap; 
        }

        .polaroid {
            background: white;
            padding: 12px 12px 45px 12px;
            box-shadow: 0 10px 20px rgba(0,0,0,0.1);
            width: 220px;
            transition: 0.4s;
        }

        .polaroid img { width: 100%; height: 180px; object-fit: cover; }
        .polaroid p { font-family: 'Kalam', cursive; text-align: center; margin-top: 15px; font-size: 1.2rem; }
        
        .p1 { transform: rotate(-6deg); }
        .p2 { transform: rotate(4deg); }
        .p3 { transform: rotate(-3deg); }
        .p4 { transform: rotate(7deg); }
        .p5 { transform: rotate(-5deg); }

        /* MOTIVASI */
        .motivation {
            text-align: center;
            padding: 80px 10%;
            background: #fff;
            margin: 40px 0;
        }

        .motivation blockquote {
            font-family: 'Playfair Display', serif;
            font-style: italic;
            font-size: 1.8rem;
            margin-bottom: 10px;
        }

        /* FOOTER & TOMBOL SOSMED BIASA */
        footer {
            background: var(--primary);
            color: white;
            padding: 60px 20px;
            text-align: center;
        }

        .social-container {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin-top: 20px;
        }

        .btn-social {
            padding: 10px 25px;
            border: 1px solid white;
            color: white;
            text-decoration: none;
            font-weight: 600;
            border-radius: 5px;
            transition: 0.3s;
        }

        .btn-social:hover {
            background: white;
            color: var(--primary);
        }

    </style>
</head>
<body>

    <nav>
        <div class="logo">8<span>.10</span></div>
        <ul class="nav-links">
            <li><a href="#pelajaran">Pelajaran</a></li>
            <li><a href="#piket">Piket</a></li>
            <li><a href="#galeri">Galeri</a></li>
        </ul>
    </nav>

    <header class="hero">
        <h1>CLASS 8.10</h1>
        <p>Kebersamaan adalah Kekuatan Kami</p>
    </header>

    <section id="pelajaran">
        <h2 class="section-title">Jadwal Pelajaran</h2>
        <div class="cards-grid">
            <div class="card"><h3>Senin</h3><ul><li class="bold-text">PPKN</li><li class="bold-text">PJOK</li><li class="bold-text">IPS</li></ul></div>
            <div class="card"><h3>Selasa</h3><ul><li class="bold-text">Matematika</li><li class="bold-text">B.inggris</li><li class="bold-text">B.indo dan Sbk</li></ul></div>
            <div class="card"><h3>Rabu</h3><ul><li class="bold-text">IPA</li><li class="bold-text">TIK</li><li class="bold-text">PAI/Agama</li></ul></div>
            <div class="card"><h3>Kamis</h3><ul><li class="bold-text">B.inggris</li><li class="bold-text">B.indonesia</li><li class="bold-text">IPS Dan Matematika</li></ul></div>
            <div class="card"><h3>Jumat</h3><ul><li class="bold-text">IPA</li><li class="bold-text">B.indonesia</li><li class="bold-text"></li></ul></div>
        </div>
    </section>

    <section id="piket" style="background: #f1f5f9;">
        <h2 class="section-title">Jadwal Piket</h2>
        <div class="cards-grid">
            <div class="card"><h3>Senin</h3><ul><li class="bold-text">Andi</li><li class="bold-text">Budi</li><li class="bold-text">Citra</li></ul></div>
            <div class="card"><h3>Selasa</h3><ul><li class="bold-text">Dewi</li><li class="bold-text">Eko</li><li class="bold-text">Fani</li></ul></div>
            <div class="card"><h3>Rabu</h3><ul><li class="bold-text">Gilang</li><li class="bold-text">Hana</li><li class="bold-text">Indra</li></ul></div>
            <div class="card"><h3>Kamis</h3><ul><li class="bold-text">Joko</li><li class="bold-text">Kiki</li><li class="bold-text">Lala</li></ul></div>
            <div class="card"><h3>Jumat</h3><ul><li class="bold-text">Mamat</li><li class="bold-text">Nana</li><li class="bold-text">Oki</li></ul></div>
        </div>
    </section>

    <section id="galeri">
        <h2 class="section-title">Galeri </h2>
        <div class="photo-wall">
            <div class="polaroid p1"><img <img src="https://image2url.com/r2/default/images/1775720677325-f15cee5c-5d77-48f2-a791-4093f5547bd1.jpg" alt="Foto"><p>FOTO BERSAMA🤗</p></div>
            <div class="polaroid p2"><img <img src="https://image2url.com/r2/default/images/1775724351317-0228efe9-d112-4b4d-9a86-7981e797aa0f.jpg" alt="Foto"><p>BUKBER😁</p></div>
            <div class="polaroid p3"><img <img src="https://image2url.com/r2/default/images/1775724632475-eb5798aa-9b1f-4fab-aefb-8f9d0f6768ea.jpg" alt="Foto"><p>SOLIDARITAS</p></div>
            <div class="polaroid p4"><img <img src="https://image2url.com/r2/default/images/1775725443537-0b48993b-387a-4e85-8a05-0eb40c5a7373.jpg" alt="Foto"><p>BINGXUE</p></div>
            <div class="polaroid p5"><img <img src="https://image2url.com/r2/default/images/1775725518687-d5ffcab9-0be1-4cfb-b268-873273965ef9.jpg" alt="Foto"><p>HARI GURU</p></div>
        </div>
    </section>

    <section class="motivation">
        <blockquote>"Pendidikan adalah tiket ke masa depan."</blockquote>
        <cite>—Amba </cite>
    </section>

    <footer>
        <p>Hubungi Sosial Media Kelas Kami:</p>
        <div class="social-container">
            <a href="https://www.instagram.com/akun_kelas_kamu" target="_blank" class="btn-social">Instagram</a>
            <a href="https://www.tiktok.com/@akun_kelas_kamu" target="_blank" class="btn-social">TikTok</a>
        </div>
        <br>
        <p style="opacity: 0.5; font-size: 0.8rem;">&copy; 2026 Kelas 7 Andromeda</p>
    </footer>

</body>
</html>
