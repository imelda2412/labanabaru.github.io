<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kirim Review | Labana Baru</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<!-- NAVBAR -->
<nav class="navbar">
    <a href="beranda.php">Beranda</a>
    <a href="best-menu.php">Best Menu</a>
    <a href="tentang.php">Tentang</a>
    <a href="kontak.php">Kontak</a>
</nav>

<!-- FORM SECTION -->
<section class="form-section">
    <div class="form-card">
        <h2>Kirim Review & Keluhan</h2>
        <p>Masukan Anda sangat berarti untuk membantu kami meningkatkan kualitas pelayanan.</p>

        <form id="reviewForm">

            <div class="form-group">
                <input type="text" id="name" name="name" placeholder="Nama Anda" required>
            </div>

            <div class="form-group">
                <input type="email" id="email" name="email" placeholder="Email Anda" required>
            </div>

            <div class="form-group">
                <select id="type" name="type" required>
                    <option value="">Pilih Jenis Pesan</option>
                    <option value="Review">Review</option>
                    <option value="Keluhan">Keluhan</option>
                </select>
            </div>

            <div class="form-group">
                <textarea id="message" name="message" rows="5" placeholder="Tulis pesan Anda..." required></textarea>
            </div>

            <button type="submit" class="btn-submit">Kirim Review</button>

            <!-- BUTTON LIHAT REVIEW -->
            <div style="text-align:center; margin-top:15px;">
                <a href="review.php" class="btn secondary">Lihat Review</a>
            </div>

        </form>
    </div>
</section>

<script>
const form = document.getElementById('reviewForm');
const scriptURL = 'https://script.google.com/macros/s/AKfycbyZ4tnzvkLCt7luo1LhWFUYTjwj3Qz0JeKQp_qOEHWNNRk5VrtHIeSh3_Xe0BoM4BZ6/exec';

form.addEventListener('submit', async (e) => {
    e.preventDefault();

    const name = document.getElementById('name').value;
    const email = document.getElementById('email').value;
    const type = document.getElementById('type').value;
    const message = document.getElementById('message').value;
    const date = new Date().toLocaleString();

    const reviews = JSON.parse(localStorage.getItem('reviews')) || [];
    reviews.push({ name, email, type, message, date });
    localStorage.setItem('reviews', JSON.stringify(reviews));

    const formData = new FormData();
    formData.append('name', name);
    formData.append('email', email);
    formData.append('type', type);
    formData.append('message', message);
    formData.append('date', date);

    try {
        await fetch(scriptURL, {
            method: 'POST',
            body: formData
        });

        alert('Review berhasil dikirim 🙌');
        form.reset();
    } catch (error) {
        alert('Gagal kirim ke spreadsheet ❌');
    }
});
</script>

</body>
</html>
