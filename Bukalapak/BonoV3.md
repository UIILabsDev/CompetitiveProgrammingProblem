<div style="text-align:center">
    <p style="font-size:30px;">Bono v3.0</p>
    <p>Time limit: 1 s</p>
    <p>Memory limit: 64 MB</p>
</div>

<div class="content-text">
<h3>Deskripsi</h3>

<p>Kang dan Kung adalah sepasang teman yang senang bermain Board Games (permainan papan). Namun, mereka hanya senang bermain Board Games yang deterministik, yaitu tidak mengandung unsur random(acak), seperti catur. Karena Board Games yang deterministik jumlahnya sedikit, mereka memutuskan untuk membuat permainan baru. Permainan ini mereka namakan "Bono".&nbsp;</p>

<p>Aturan permainan Bono sederhana. Papan permainan Bono adalah sebuah tabel dengan 3 baris dan 3 kolom. Permainan dilakukan secara bergiliran antara 2 pemain. Pada setiap giliran, pemain harus mengisi salah satu sel yang kosong di tabel dengan sebuah sayur kangkung. Kangkung yang telah diletakkan di sel tidak boleh dipindahkan. Tabel akan hancur dengan sendirinya apabila ada baris atau kolom atau diagonal yang berisi 3 sayur kangkung. Pemain dinyatakan kalah apabila tidak dapat meletakkan kangkung di tabel pada gilirannya.</p>

<p>Tentu saja, pemain pertama akan selalu menang apabila dia bermain secara optimal. Oleh karena itu, diciptakanlah Bono v2. Pada Bono v2, jumlah tabel dalam 1 permainan dapat mencapai sebanyak N (N&lt;=1000). Dalam setiap giliran, pemain bebas meletakkan sebuah sayur kangkung pada satu sel yang kosong di tabel yang belum hancur. Pemain dinyatakan kalah apabila tidak dapat meletakkan kangkung di tabel pada gilirannya.</p>

<p>Bono v2 masih terlalu mudah karena apabila kedua pemain bermain secara optimal, pemain pertama akan selalu menang apabila jumlah tabel ganjil, dan pemain kedua akan selalu menang apabila jumlah tabel genap. Untuk menyelesaikan masalah ini, diciptakanlah Bono v3. Pada Bono v3, kondisi awal setiap tabel tidak selalu kosong. Bisa saja sudah ada kangkung yang terletak di berbagai sel di berbagai tabel.</p>

<p>Kang dan Kung memutuskan untuk bermain Bono v3 sebanyak T kali (T&lt;=1000). Kang selalu menjadi pemain pertama dan mereka berdua bermain secara optimal. Untuk setiap permainan, siapakah yang akan menang?</p>

<h3>Format Masukan</h3>

<p>Baris pertama masukan berisikan sebuah bilangan T, banyaknya permainan. (T&lt;=1000).</p>
<p>Untuk setiap permainan, baris pertama berisi sebuah bilangan N, yaitu banyaknya tabel pada permainan tersebut. (N&lt;=1000)<br>
N baris berikutnya masing-masing berisi kondisi awal tabel. Kondisi tabel direpresentasikan dalam sebuah string dengan panjang 9 digit berisi angka 0 atau 1. Sel ke(i,j) pada tabel direpresentasikan oleh karakter ke (i-1)x3+j pada string. Angka 0 berarti tidak ada kangkung dalam sel, angka 1 berarti ada kangkung dalam sel.</p>

<h3>Format Keluaran</h3>

<p>Untuk setiap permainan, keluarkan satu baris yang berisi nama pemenang.</p>

<h3>Contoh Masukan</h3>

<pre>3
1
000000000
2
000000000
000000000
2
100010000
001010000</pre>

<h3>Contoh Keluaran</h3>

<pre>Kang
Kung
Kung</pre>
<h3>&nbsp;</h3>
</div>
