# -- DIV

memungkinkan kita untuk mengelompokkan beberapa elemen sebagai satu kesatuan

fungsi utama: mengelompokkan, menjadi container (kalian punya mie, dimasukkin ke dalam tupperware)

# -- Sizing:

Width - mengatur lebar dari suatu elemen
Height- mengatur tinggi dari suatu elemen

Sizing bisa menggunakan pixel, point, picas, cm, mm, inches

# -- Penjarakan:

Jarak bisa diberikan menggunakan margin dan padding

margin memberikan jarak luar, sehingga dia memiliki jarak antar elemen dengan elemen lainnya

padding memberikan jarak dalam, sehingga dia memiliki jarak antar border dengan elemen di dalamnya

# -- header

jarak cuma h1-h6

# -- img

img src="./image/foto.jpg" style="width: 350px; border-radius: 10px 10px 0px 0px;

src
-> sumber gambar
style
-> border radius
    > urutan searah jam


ref link:

[css units](https://www.w3schools.com/cssref/css_units.php)

[html table border](https://www.w3schools.com/html/html_table_borders.asp)

[md guide](https://www.markdownguide.org/basic-syntax/)

[backup repo](https://github.com/adhxabre/b50s1)

#git push

```bash
git init #inisiasi proyek dipush kedalam repo
git remote add nama_remote link_repo_github #nambah link remote baru
git add . #menambahkan semua file yang ada dalam folder lokal kedalam commit | NOTE: (.) semua file folder dicommit
git commit -m "isi pesan" #ngirim pesan kalo mau ngepush
git branch -M main #merubah direksi branch, dari "master" ke "main"
git push origin main  #push project kedalam repo kita
```
#git update (step by step)

```bash
git add .
git commit -m "isi pesan"
git push origin main
```