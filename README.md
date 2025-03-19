![Luar Sekolah](https://www.luarsekolah.com/images/svg/logo.svg)

# Tugas 1: HTML

## 📌 Informasi Peserta
- **Nama**: Andhika Septian Prayoga  
- **Okupasi**: Web Development  

---

## 📋 Detail Tugas
Dalam halaman utama website, wajib terdapat beberapa struktur, diantaranya:
1. **Header** dengan navigasi
2. **Hero section** dengan deskripsi utama
3. **Section layanan/produk/konten utama**
4. **Section informasi atau testimoni** (jika ada)
5. **Formulir kontak sederhana**
6. **Footer** dengan informasi tambahan

Selain struktur di atas, peserta bebas menambahkan struktur lain sesuai dengan kebutuhan.

---

## 🖥️ Source Code HTML
```html
        <!DOCTYPE html>
        <html lang="id"></html>
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>Tugas Minggu 1 - Luar Sekolah </title>
        </head>
        <body>

            <header>
                <nav>
                    <ul>
                        <li><a href="https://www.tokopedia.com/">Beranda</a></li>
                        <li><a href="https://www.tokopedia.com/p/handphone-tablet?source=homepage.dynamic_icon.0.680&t_id=1741672569089&t_st=1&t_pp=homepage&t_efo=&t_ef=homepage&t_sm=&t_spt=tnb_homepage">Produk</a></li>
                        <li><a href="https://www.tokopedia.com/help/article/dimana-saya-dapat-menghubungi-tokopedia">Layanan</a></li>
                        <li><a href="#contact">Kontak</a></li>
                    </ul>
                </nav>
            </header>


            <main>
                <section id="hero">
                    <div class="container">
                        <h1>Selamat Datang di Market Luar Sekolah </h1>
                        <p>Toko serba di ada adain </p>

                        <img src="https://seosecret.id/placeholder/600x300/D5D5D5/584959" alt="Gambar Pasar" style="width:100%;height:auto;">    </div>
                </section>


                <section id="products">
                    <div class="container">
                        <h2>Produk Kami</h2>
                        <p>Jelajahi berbagai macam produk kami.</p>

                    </div>
                </section>

                <section id="testimonials">
                    <div class="container">
                        <h2>Testimoni Pelanggan</h2>
                        <table border="1">
                            <thead>
                                <tr>
                                    <th>Nama</th>
                                    <th>Testimoni</th>
                                    <th>Rating</th>
                                </tr>
                            </thead>
                            <tbody>
                                <tr>
                                    <td>Andi</td>
                                    <td>Layanan hebat!</td>
                                    <td>⭐⭐⭐⭐⭐</td>
                                </tr>
                                <tr>
                                    <td>Budi</td>
                                    <td>Produk luar biasa!</td>
                                    <td>⭐⭐⭐⭐</td>
                                </tr>
                                <tr>
                                    <td>Citra</td>
                                    <td>Pengiriman cepat!</td>
                                    <td>⭐⭐⭐⭐⭐</td>
                                </tr>
                            </tbody>
                        </table>
                    </div>
                </section>


                <section id="video">
                    <div class="container">
                        <h2>Video Pasar</h2>

                        <iframe width="560" height="315" src="https://www.youtube.com/embed/XHUURHf7Wb4" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    </div>
                </section>


                <section id="contact">
                    <div class="container">
                        <h2>Hubungi Kami</h2>
                        <form action="/submit" method="post">
                            <fieldset>
                                <legend>Formulir Kontak</legend>
                                <label for="name">Nama:</label>
                                <input type="text" id="name" name="name" placeholder="Nama Anda..." required>
                                <br>
                                <label for="email">Email:</label>
                                <input type="email" id="email" name="email" placeholder="Email Anda..." required>
                                <br>
                                <label for="message">Pesan:</label>
                                <textarea id="message" name="message" placeholder="Pesan Anda..." required></textarea>
                                <br>
                                <input type="submit" value="Kirim">
                            </fieldset>
                        </form>
                    </div>
                </section>
            </main>


            <footer>
                <div class="container">
                    <p>&copy; 2025 Andhika Sptian prayoga.</p>
                    <p>Tugas Weekly Pertama HTML</p>
                </div>
            </footer>
        </body>
        </html>

```

---

## 📸 Screenshot Tampilan HTML
![Screenshot Tampilan HTML](sspic.png)
