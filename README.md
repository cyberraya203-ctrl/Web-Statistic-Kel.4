<!DOCTYPE html><html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Materi Statistika Keren</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
<style>
* { margin:0; padding:0; box-sizing:border-box; }
body {
    font-family:'Poppins', sans-serif;
    background: linear-gradient(135deg,#74ebd5,#acb6e5);
    scroll-behavior:smooth;
}/* Navbar */ nav { position:fixed; top:0; width:100%; background:rgba(0,0,0,0.7); padding:10px; display:flex; justify-content:center; gap:20px; z-index:1000; } nav a { color:white; text-decoration:none; font-weight:500; } nav a:hover { color:#74ebd5; }

header { margin-top:60px; text-align:center; color:white; padding:40px 20px; } header h1 { font-size:2.5em; }

.container { max-width:1000px; margin:20px auto; padding:20px; }

.card { background:white; border-radius:15px; padding:20px; margin-bottom:25px; box-shadow:0 8px 20px rgba(0,0,0,0.2); transform:translateY(50px); opacity:0; transition:all 0.6s ease; }

.card.show { transform:translateY(0); opacity:1; }

.card:hover { transform:scale(1.03); }

h2 { color:#2c3e50; margin-bottom:10px; } ul { padding-left:20px; line-height:1.8; }

img { width:100%; border-radius:10px; margin-bottom:15px; }

footer { text-align:center; padding:15px; background:rgba(0,0,0,0.7); color:white; } </style>

</head>
<body><nav>
<a href="#pengertian">Pengertian</a>
<a href="#data">Pengumpulan</a>
<a href="#penyajian">Penyajian</a>
<a href="#pemusatan">Pemusatan</a>
<a href="#penyebaran">Penyebaran</a>
</nav><header>
<h1>📊 Materi Statistika</h1>
<p>Website Interaktif & Modern</p>
</header><div class="container"><div id="pengertian" class="card">
<img src="https://images.unsplash.com/photo-1551288049-bebda4e38f71">
<h2>1. Pengertian</h2>
<ul>
<li>Statistika: Ilmu pengolahan data</li>
<li>Statistik: Data berupa angka</li>
<li>Populasi: Seluruh objek</li>
<li>Sampel: Sebagian objek</li>
</ul>
</div><div id="data" class="card">
<img src="https://images.unsplash.com/photo-1581090700227-1e8a5b6b6c7d">
<h2>2. Pengumpulan Data</h2>
<ul>
<li>Observasi</li>
<li>Kuesioner</li>
<li>Wawancara</li>
<li>Internet</li>
</ul>
</div><div id="penyajian" class="card">
<img src="https://images.unsplash.com/photo-1554224155-6726b3ff858f">
<h2>3. Penyajian Data</h2>
<ul>
<li>Tabel</li>
<li>Diagram</li>
</ul>
</div><div id="pemusatan" class="card">
<img src="https://images.unsplash.com/photo-1591696205602-2f950c417cb9">
<h2>4. Ukuran Pemusatan</h2>
<ul>
<li>Mean</li>
<li>Median</li>
<li>Modus</li>
</ul>
</div><div id="penyebaran" class="card">
<img src="https://images.unsplash.com/photo-1509228468518-180dd4864904">
<h2>5. Ukuran Penyebaran</h2>
<ul>
<li>Kuartil</li>
<li>Desil</li>
<li>Persentil</li>
<li>Jangkauan</li>
<li>Simpangan</li>
</ul>
</div></div><footer>
<p>© 2026 Statistika Keren 🚀</p>
</footer><script>
// Animasi scroll
const cards = document.querySelectorAll('.card');
window.addEventListener('scroll', () => {
    cards.forEach(card => {
        const top = card.getBoundingClientRect().top;
        if(top < window.innerHeight - 50){
            card.classList.add('show');
        }
    });
});
</script></body>
</html>
