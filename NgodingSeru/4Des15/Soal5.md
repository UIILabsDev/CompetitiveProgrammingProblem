<h2 class="text-center">Bebek Ganteng</h2>

<p class="text-center">
    Time limit:

        1 s

</p>
<p class="text-center">
    Memory limit:

        64 MB

</p>

<p>&nbsp;</p>

<div class="content-text">
    <h3>Description</h3>

<p>Pak Dengklek memiliki N ekor bebek. Setiap bebek memiliki nilai kegantengannya masing-masing. Semakin tinggi nilai kegantengan, maka semakin gantenglah bebek tersebut. Pak Dengklek ingin membagi bebek-bebeknya ke dalam 3 buah grup. Setiap grup tidak harus memiliki banyak anggota yang sama dengan grup lainnya.</p>

<p>Tanpa disadari, terdapat suatu kecemburuan di dalam sebuah grup. Kecemburuan tersebut terjadi di antara bebek yang paling tidak ganteng dengan bebek yang paling ganteng pada grup tersebut. Nilai kecemburuan pada grup ini adalah selisih dari nilai kegantengan bebek yang paling ganteng dengan bebek yang paling tidak ganteng.</p>

<p>Setelah Pak Dengklek menyadari adanya kecemburuan ini, Pak Dengklek ingin membagi bebek-bebeknya ke dalam 3 buah grup sedemikian rupa sehingga jumlah nilai kecemburuan dari ketiga grup seminimal mungkin. Bantulah Pak Dengklek menemukan jumlah nilai kecemburuan yang paling minimal!</p>

<h3>Input Format</h3>

<p>Baris pertama berisi sebuah bilangan bulat N yang menyatakan banyaknya bebek yang dimiliki oleh Pak Dengklek. Baris kedua berisi N buah bilangan bulat yang menyatakan nilai kegantengan yang dimiliki oleh masing-masing bebek.</p>

<h3>Output Format</h3>

<p>Keluaran terdiri dari sebuah baris berisi jumlah nilai kecemburuan dari ketiga grup yang paling minimal.</p>

<h3>Sample Input</h3>

<pre>6
6 4 12 3 10 12
</pre>

<h3>Sample Output</h3>

<pre>3
</pre>

<h3>Penjelasan</h3>

<p>Salah satu kemungkinan pembagian grup yang meminimalkan jumlah nilai kecemburuan adalah:</p>

<ul>
	<li>Grup 1 beranggotakan 3 ekor bebek yang memiliki kegantengan 12, 10, dan 12. Nilai kecemburuannya adalah 12 - 10 = 2.</li>
	<li>Grup 2 beranggotakan 2 ekor bebek yang memiliki kegantengan 4 dan 3. Nilai kecemburuannya adalah 4 - 3 = 1.</li>
	<li>Grup 3 beranggotakan 1 ekor bebek yang memiliki kegantengan 6. Nilai kecemburuannya adalah 6 - 6 = 0.</li>
</ul>

<p>Jumlah nilai kecemburuan dari ketiga grup adalah 2 + 1 + 0 = 3. Tidak ada kemungkinan pembagian grup lain yang memiliki jumlah nilai kecemburuan kurang dari 3.</p>

<h3>Batasan</h3>

<ul>
	<li>3 ≤ N ≤ 100.000</li>
	<li>Nilai kegantengan semua bebek berada di antara 1 dan 1.000.000.000 (inklusif).</li>
</ul>
