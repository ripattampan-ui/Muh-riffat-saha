<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Saya - 2026</title>
    <style>
        /* Gaya Umum */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }

        body {
            background-color: #f0f4f8;
            color: #333;
            line-height: 1.6;
        }

        /* Bagian Atas / Header */
        header {
            background-color: #2c5aa0;
            color: white;
            padding: 1.5rem;
            text-align: center;
        }

        /* Menu Navigasi */
        nav {
            background-color: #1a3b69;
            padding: 0.8rem;
        }

        nav ul {
            list-style: none;
            text-align: center;
        }

        nav ul li {
            display: inline;
            margin: 0 1.2rem;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: 500;
        }

        nav ul li a:hover {
            color: #ffd700;
            text-decoration: underline;
        }

        /* Bagian Konten Utama */
        .container {
            max-width: 1100px;
            margin: 2rem auto;
            padding: 0 1.5rem;
        }

        .konten-utama {
            background-color: white;
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
            margin-bottom: 2rem;
        }

        .konten-utama h2 {
            color: #2c5aa0;
            margin-bottom: 1rem;
            border-bottom: 2px solid #e0e7ee;
            padding-bottom: 0.5rem;
        }

        .konten-utama p {
            margin-bottom: 1rem;
            font-size: 1.05rem;
        }

        /* Bagian Bawah / Footer */
        footer {
            background-color: #1a3b69;
            color: white;
            text-align: center;
            padding: 1.2rem;
            margin-top: 2rem;
        }

        /* Tampilan untuk HP (Responsif) */
        @media (max-width: 600px) {
            nav ul li {
                display: block;
                margin: 0.5rem 0;
            }
        }
    </style>
</head>
<body>

    <!-- Bagian Judul -->
    <header>
        <h1>Selamat Datang di Website Saya</h1>
        <p>Dibuat pada 25 Mei 2026</p>
    </header>

    <!-- Menu Navigasi -->
    <nav>
        <ul>
            <li><a href="#">Beranda</a></li>
            <li><a href="#">Tentang Kami</a></li>
            <li><a href="#">Layanan</a></li>
            <li><a href="#">Galeri</a></li>
            <li><a href="#">Kontak</a></li>
        </ul>
    </nav>

    <!-- Isi Konten -->
    <div class="container">
        <div class="konten-utama">
            <h2>Tentang Website Ini</h2>
            <p>Halo! Ini adalah contoh halaman website sederhana yang sudah dilengkapi dengan desain yang rapi, mudah dibaca, dan bisa menyesuaikan tampilan di layar HP maupun komputer.</p>
            <p>Kamu bisa mengubah tulisan, warna, gambar, dan menu di dalam kode ini sesuai dengan keinginanmu. Struktur ini sudah lengkap dan siap dikembangkan lebih lanjut.</p>
        </div>

        <div class="konten-utama">
            <h2>Fitur Utama</h2>
            <p>Beberapa hal yang sudah ada di kode ini:</p>
            <ul style="margin-left: 1.5rem; margin-top: 0.5rem;">
                <li>Desain responsif (cocok untuk semua ukuran layar)</li>
                <li>Warna yang serasi dan enak dilihat</li>
                <li>Menu navigasi yang jelas</li>
                <li>Bagian konten dan footer yang rapi</li>
                <li>Struktur kode yang mudah dipahami dan diubah</li>
            </ul>
        </div>
    </div>

    <!-- Bagian Bawah -->
    <footer>
        <p>&copy; 2026 Website Saya. Semua Hak Dilindungi.</p>
    </footer>

</body>
</html>
