# casestory
Toko casing elegan &amp; custom
<section>
  <h2>Galeri Produk</h2>
  <div class="gallery">
    <img src="GAMBAR1.JPG" alt="Casing Polos Elegan">
    <img src="GAMBAR2.JPG" alt="Casing Custom Anime">
    <img src="GAMBAR3.JPG" alt="Casing Glow in The Dark">
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
