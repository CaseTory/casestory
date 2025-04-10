# casestory
Toko casing elegan &amp; custom
<section>
  <h2>Galeri Produk</h2>
  <div class="gallery">
    <img src="gambar1.jpg" alt="Casing Polos Elegan">
    <img src="gambar2.jpg" alt="Casing Custom Anime">
    <img src="gambar3.jpg" alt="Casing Glow in The Dark">
  </div>
</section>

<style>
.gallery {
  display: flex;
  flex-wrap: wrap;
  gap: 15px;
  justify-content: center;
  margin-top: 20px;
}
.gallery img {
  width: 200px;
  border-radius: 12px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.1);
  transition: transform 0.2s;
}
.gallery img:hover {
  transform: scale(1.05);
}
</style>
