<div style="text-align:center">
    <p style="font-size:30px">Menyiram Bunga</p>
    <p>Time limit: 2 s</p>
    <p>Memory limit: 64 MB</p>
</div>
<div class="content-text">
    <h3>Deskripsi</h3>

<p>Anda memiliki <strong>N</strong> buah pot bunga berjejer dari kiri ke kanan. Pot paling kiri dinomori 1 hingga pot paling kanan dinomori <strong>N</strong>. Pada awalnya setiap pot kosong dan akan tumbuh bunga apabila disiram. Bunga pada pot nomor <strong>i</strong> akan tumbuh tinggi hingga maksimal <strong>A<sub>i</sub></strong> cm.</p>

<p>Anda akan menyiram pot-pot tersebut dengan sebuah robot yang bekerja dengan algoritma berikut:</p>

<ul>
    <li>Robot pada mulanya ada di depan pot nomor <strong>M</strong>.</li>
    <li>Robot menyiram pot di depannya sebanyak <strong>K</strong> liter.</li>
    <li>Robot bergerak ke pot di sebelah kanan. Apabila sudah mentok (nomor <strong>N</strong>), maka robot akan kembali ke pot 1.</li>
    <li>Ulangi algoritma dari langkah ke-2.</li>
</ul>

<p>Waktu yang diperlukan robot untuk menyiram 1 liter air adalah 1 jam dan tidak diperlukan waktu untuk berpindah pot saking cepatnya. Jika bunga disiram oleh air, maka bunga itu secara ajaib langsung bertambah tingginya dengan 1 liter air sama dengan meninggi 1 cm. Bunga tidak dapat meninggi lagi jika sudah mencapai tinggi maksimalnya.</p>

<p>Diberikan nilai <strong>N</strong>, <strong>M</strong>, <strong>K</strong>, dan masing-masing <strong>A<sub>i</sub></strong>, tentukan urutan bunga-bunga terurut dari bunga yang mencapai tinggi maksimalnya pertama kali!</p>

<h3>Format Masukan</h3>

<p>Baris pertama terdiri dari tiga buah bilangan bulat&nbsp;<strong>N</strong>&nbsp;(1&nbsp;≤ N&nbsp;≤ 10<sup>5</sup>), <strong>M</strong>&nbsp;(1 ≤&nbsp;M ≤ N), dan <strong>K</strong>&nbsp;(1 ≤&nbsp;K ≤ 10<sup>9</sup>).</p>

<p>Baris kedua terdiri dari N buah bilangan bulat <strong>A<sub>1</sub></strong>, <strong>A<sub>2</sub></strong>, ..., <strong>A<sub>N</sub></strong>&nbsp;(1&nbsp;≤ A<sub>i</sub>&nbsp;≤ 10<sup>5</sup>).</p>

<h3>Format Keluaran</h3>

<p>Keluarkan <strong>N</strong> buah bilangan bulat yang menyatakan urutan bunga-bunga terurut dari bunga yang mencapai tinggi maksimalnya pertama kali dipisahkan oleh sebuah spasi.</p>

<h3>Contoh Masukan</h3>

<pre>5 1 4
10 3 7 4 9
</pre>

<h3>Contoh Keluaran</h3>

<pre>2 4 3 1 5
</pre>

<h3>Contoh Masukan</h3>

<pre>10 7 20
1 1 1 1 1 1 1 1 1 1

</pre>

<h3>Contoh Keluaran</h3>

<pre>7 8 9 10 1 2 3 4 5 6
</pre>

</div>
