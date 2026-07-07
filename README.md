# Crackme Solutions

Selamat datang di repositori **Crackme Solutions**! 

Repositori ini adalah dokumentasi perjalanan belajar *Reverse Engineering* (RE) secara bertahap. Memecahkan *crackme* (program yang sengaja dirancang untuk diretas) adalah cara terbaik untuk melatih insting analisis, dan di sinilah setiap proses akan dicatat.

## Tujuan Repositori
Fokus utama dari penyelesaian *crackme* di sini bukan semata-mata untuk menebak *password* yang benar atau sekadar mendapatkan *flag* keberhasilan. Lebih dari itu, tujuannya adalah untuk memahami alur dari program. 

Mulai dari menavigasi kode *Assembly* tingkat rendah, merapikan *pseudo-code* bahasa C di dalam *decompiler*, memanipulasi *register* di dalam *debugger*, hingga akhirnya mampu membalikkan logika tersebut menjadi *script Keygen* mandiri. 

## Struktur Direktori
Untuk menjaga semuanya tetap rapi dan mudah dibaca, setiap target *crackme* dipisahkan ke dalam foldernya masing-masing (seperti judul crackmesnya). Di dalam setiap folder tersebut, terdapat:
* Laporan `judul.md` yang berisi *writeup* atau langkah-langkah bedah kode yang ditulis secara runtut.
* Bukti tangkapan layar (*screenshot*) dari *decompiler* (seperti Ghidra) atau *debugger* yang sudah diberi anotasi agar alur logikanya mudah dipahami.
* *Script* tambahan (seperti Python) khusus untuk target tingkat lanjut yang membutuhkan perhitungan otomatis seperti *Key Generator*.

---
**Catatan Pembelajaran:** Seluruh analisis dan *writeup* di repositori ini ditulis ulang berdasarkan pemahaman pribadi selama proses belajar. Jika terdapat penggunaan istilah teknis atau penjabaran logika yang sedikit kurang tepat, hal tersebut merupakan bagian murni dari proses pembelajaran dan adaptasi.
