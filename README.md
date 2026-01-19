<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>General Affairs Information System (GAIS)</title>
    <style>
        body {
            margin: 0;
            font-family: "Segoe UI", Arial, sans-serif;
            background: linear-gradient(135deg, #1f2933, #111827);
            color: #ffffff;
        }

        header {
            padding: 60px 20px;
            text-align: center;
        }

        header h1 {
            font-size: 36px;
            margin-bottom: 10px;
            letter-spacing: 1px;
        }

        header p {
            font-size: 16px;
            color: #d1d5db;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 40px 20px;
        }

        .menu {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            gap: 20px;
        }

        .card {
            background: #1f2933;
            border-radius: 12px;
            padding: 25px;
            text-align: center;
            transition: transform 0.2s ease, box-shadow 0.2s ease;
            box-shadow: 0 8px 20px rgba(0,0,0,0.3);
        }

        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 12px 28px rgba(0,0,0,0.45);
        }

        .card h3 {
            margin-bottom: 10px;
            font-size: 18px;
        }

        .card p {
            font-size: 14px;
            color: #9ca3af;
            margin-bottom: 15px;
        }

        .card a {
            display: inline-block;
            padding: 10px 18px;
            border-radius: 8px;
            text-decoration: none;
            background-color: #2563eb;
            color: #ffffff;
            font-size: 14px;
            transition: background-color 0.2s ease;
        }

        .card a:hover {
            background-color: #1d4ed8;
        }

        footer {
            text-align: center;
            padding: 20px;
            font-size: 13px;
            color: #9ca3af;
            border-top: 1px solid #374151;
        }
    </style>
</head>
<body>

<header>
    <h1>General Affairs Information System</h1>
    <p>Sistem Pelaporan dan Layanan Operasional General Affairs</p>
</header>

<div class="container">
    <div class="menu">

        <div class="card">
            <h3>Pengecekan Kebersihan</h3>
            <p>Laporan kondisi kebersihan area dan fasilitas kantor.</p>
            <a href="#">Isi Laporan</a>
        </div>

        <div class="card">
            <h3>Kendaraan Dinas</h3>
            <p>Pengecekan kondisi dan permintaan kendaraan operasional.</p>
            <a href="#">Buka Form</a>
        </div>

        <div class="card">
            <h3>Permintaan ATK / RTK</h3>
            <p>Pengajuan kebutuhan alat tulis dan rumah tangga kantor.</p>
            <a href="#">Ajukan Permintaan</a>
        </div>

        <div class="card">
            <h3>Penilaian Catering</h3>
            <p>Evaluasi kualitas makanan dan layanan catering.</p>
            <a href="#">Isi Penilaian</a>
        </div>

        <div class="card">
            <h3>Evaluasi Layanan GA</h3>
            <p>Penilaian kinerja dan pelayanan General Affairs.</p>
            <a href="#">Beri Penilaian</a>
        </div>

    </div>
</div>

<footer>
    © 2026 General Affairs Information System | Internal Use Only
</footer>

</body>
</html>
