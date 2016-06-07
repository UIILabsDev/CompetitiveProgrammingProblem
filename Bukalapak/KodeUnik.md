<div style="text-align:center">
    <p style="font-size:30px">Kode Unik</p>
    <p>Time limit: 1 s</p>
    <p>Memory limit: 64 MB</p>
</div>
<div class="content-text">
<h3>Deskripsi</h3>

<p>Di sebuah kota yang bernama "Lapak City", setiap turis yang berkunjung akan diberikan sebuah kode unik berdasarkan angka favorit turis tersebut. Apabila angka favorit suatu turis sudah digunakan sebagai kode unik, maka turis tersebut akan diberikan kode unik dengan nilai terkecil yang belum digunakan dan lebih besar dari angka favorit turis tersebut. Misalnya turis dengan angka favorit 42 berkunjung ke Lapak City, namun kode unik 42 sudah digunakan. Maka kode unik turis tersebut menjadi 43. Apabila 43 juga sudah digunakan, maka turis tersebut diberi kode unik 44. Begitu seterusnya sampai ada kode unik yang belum digunakan.</p>

<p>Turis yang meninggalkan Lapak City akan dihapus kode uniknya, sehingga kode uniknya dapat digunakan oleh turis lain yang baru masuk. Misalnya turis dengan kode unik 43 keluar dari Lapak City. Maka apabila ada turis yang baru masuk dengan angka favorit 43 akan mendapatkan kode unik 43.</p>

<p>Pada mulanya semua kode unik belum digunakan. Pada suatu hari, ada N peristiwa turis yang berkunjung atau keluar dari Lapak City. Bantulah Lapak City untuk menentukan kode unik turis-turis yang baru masuk.</p>

<h3>Format Masukan</h3>

<p>Baris pertama masukan berisi N, yaitu banyaknya peristiwa (1&lt;=N&lt;=100000). N baris berikutnya berisi jenis peristiwanya. Untuk turis yang berkunjung maka masukannya berupa "1 x", dengan x adalah angka favorit turis yang berkunjung (1&lt;=x&lt;=1.000.000.000). Untuk turis yang keluar maka masukannya berupa "2 x", dengan x adalah kode unik turis yang keluar.</p>

<h3>Format Keluaran</h3>

<p>Untuk setiap turis yang berkunjung, keluarkan kode unik turis tersebut.</p>

<h3>Contoh Masukan</h3>

<pre>5
1 42
1 42
1 43
2 43
1 42</pre>

<h3>Contoh Keluaran</h3>

<pre>42
43
44
43
</pre>

<p>&nbsp;</p>

</div>
