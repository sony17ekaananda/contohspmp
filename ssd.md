**1.** **Pendahuluan** <br>
   &nbsp;Software Requirement Specification (SRS) menjelaskan berbagai macam kebutuhan pembuatan suatu perangkat lunak. Dalam dokumen ini khususnya akan dibahas mengenai spesifikasi kebutuhan software untuk Aplikasi Pendataan Terpusat dan Informasi Produk Usaha Kerupuk Indramayu (PD Sri Tanjung) yaitu kebutuhan spesifik yang terdiri dari kebutuhan fungsionalitas, termasuk didalamnya input, proses, output dan non-fungsionalitas. Kebutuhan antar muka yang terdiri dari kebutuhan antar pengguna, antar hardware yang menjelaskan kebutuhan yang harus ada untuk menjalankan atau mengoprasikan aplikasi sitem, kebutuhan antar software yang menjelaskan bagaimana cara pengguna berinteraksi dengan sistem, dan kebutuhan antar komunikasi. <br>
	&nbsp;&nbsp;**1.1.** **Tujuan** <br>
		 &nbsp;&nbsp;&nbsp;Tujuan dari penulisan dokumen Software Requirement Specification (SRS) ini adalah untuk mempermudah pengembang untuk mengembangkan perangkat lunak untuk Aplikasi Pendataan Terpusat dan Informasi Produk Usaha Kerupuk Indramayu (PD Sri Tanjung) dan memberikan gambaran yang spesifik dari kebutuhan software untuk Aplikasi Pendataan Terpusat dan Informasi Produk Usaha Kerupuk Indramayu (PD Sri Tanjung). Spesfikasi kebutuhan tersebut dari segi perangkat lunak dan perangkat keras, untuk memberikan gambaran dan penjelasan mengenai pembuatan produk, penjelasan hal-hal yan dibutuhkan untuk pembuatan produk termasuk kebutuhan fungsional hingga non-fungsional, dan kebutuhan antar muka mulai dari antar muka pengguna hingga antar muka komunikasi. <br>
	&nbsp;&nbsp;**1.2.** **Lingkup** <br>
		 &nbsp;&nbsp;&nbsp;Aplikasi Pendataan Terpusat dan Informasi Produk Usaha Kerupuk Indramayu (PD Sri Tanjung) berbasis Website ini merupakan salah satu jenis perangkat lunak yang digunakan untuk membantu proses pengelolaan data dan pencatatan informasi yang terkait dengan informasi penjualan kerupuk pada PD Sri Tanjung. Aplikasi ini memungkinkan pengguna dapat mengetahui informasi seputar kerupuk yang tersedia. Data informasi tersebut merupakan data asli yang diberikan oleh pemilik perusahaan kerupuk. <br>
	&nbsp;&nbsp;**1.3.** **Definisi, akronim, singkatan** <br>
		 &nbsp;&nbsp;&nbsp;SRS: Software Requirement Specifications (Spesifikasi kebutuhan perangkat lunak). <br>
		 &nbsp;&nbsp;&nbsp;IEEE: Institute of Electrical and Electronics Engineer. <br>
	&nbsp;&nbsp;**1.4.** **Referensi** <br>
		 &nbsp;&nbsp;&nbsp;Standar IEEE nomor ANSI / IEEE Std 1058.1-1987 (reaffirmed 1993), 18 September 2004. <br>
	&nbsp;&nbsp;**1.5.** **Overview** <br>
		 &nbsp;&nbsp;&nbsp;Penulisan dokumen ini dibagi menjadi beberapa bab sebagai berikut: <br>
		 &nbsp;&nbsp;&nbsp;&nbsp;Bagian pertama berisi penjelasan tentang dokumen SPL yang mencakup tujuan pembuatan dokumen ini, lingkup maslaah yang diselesaikan oleh perangkat lunak yang dikembangkan, definisi, referensi dan deskripsi umum. <br>
		 &nbsp;&nbsp;&nbsp;&nbsp;Bagian kedua berisi tetang gambaran umum mengenai perspektif produk, manfaat produk, karakteristik user, batasan, asumsi dan ketergantungan yang digunakan.<br>
		 &nbsp;&nbsp;&nbsp;&nbsp;Bagian tiga menyediakan spesifikasi kebutuhan antarmuka, kebutuhan fungsional, kebutuhan non fungsional, lingkungan operasi dan batasan perancangan. <br>
		 &nbsp;&nbsp;&nbsp;&nbsp;Bagian empat berisi informasi pendukung yang dibutuhkan dalam dokumen ini.
		 <br>
		 <br>

**2.**	**Gamabaran Umum**<br>
	&emsp;**2.1**	**Perspektif produk**<br>
		&emsp;&emsp;Pendefinisian Aplikasi Produksi Kerupuk ini yaitu untuk mempromosikan dan menjual kerupuk secara onine melalui web. Pembuatan Aplikasi promosi dan penjualan kerupuk bertujuan untuk membantu penjual dan pembeli dalam transaksi agar mudah dan praktis tanpa harus menggunakan kertas secara manual. <br>
		&emsp;&emsp;**2.1.1**	**Antarmuka sistem**<br>
				&emsp;&emsp;&emsp;Dalam penggunaan, pengguna berinteraksi langsung dengan aplikasi melalui PC / Laptop.<br>
		&emsp;&emsp;**2.1.2**	**Antarmuka pengguna**<br>
				&emsp;&emsp;&emsp;Perangkat lunak untuk aplikasi ini dibuat dengan menggunakan aplikasi flash. Dimana tampilan didesain dengan menggunakan template yang ada. Perangkat lunak untuk layanan dalam aplikasi ini dilengkapi dengan menu untuk pengaksesan berbagai fungsi yang disediakan.<br>
		&emsp;&emsp;**2.1.3**	**Antarmuka perangkat keras**<br>
				&emsp;&emsp;&emsp;Perangkat keras yang dapat digunakan dalam perangkat lunak yang dibuat:<br>
				&emsp;&emsp;&emsp;1.	PC<br>
				&emsp;&emsp;&emsp;2.	Monitor VGA mempunyai resolusi minimal 8800 x 1200 pixel.<br>
			&emsp;&emsp;&emsp;3.	Keyboard dan mouse untuk kegiatan user.<br>
				&emsp;&emsp;&emsp;4.	Semua perangkat keras yang digunakan merupakan perangkat sttandar dalam sistem komputer.<br>
		&emsp;&emsp;**2.1.4**	**Antarmuka perangkat lunak**<br>
				&emsp;&emsp;&emsp;Perangkat lunak yang dibutuhkan untuk perpustakaan antara lain:<br>
				&emsp;&emsp;&emsp;1. Sistem Operasi Windows (7, 8,) dll<br>
				&emsp;&emsp;&emsp;2. Untuk pengolahan database : Laragon Server <br>
				&emsp;&emsp;&emsp;3. Untuk koneksi Database digunakan ADOdB<br>
		&emsp;&emsp;**2.1.5**	**Antarmuka komunikasi**<br>
			&emsp;&emsp;&emsp;Proses komunikasi dalam sistem ini menggunakan jaringan lokal, dimana dikontrol oleh komputer server.<br>
		&emsp;&emsp;**2.1.6**	**Batasan – batasan memori**<br>
				&emsp;&emsp;&emsp;Perangkat lunak hanya dijalankan di Windows (7, 8, dll).
				&emsp;&emsp;&emsp;Waktu pengembangan perangkat lunak yang singkat membuat adanya kemungkinan tidak semua fungsi yang ada dapat dilaksanakan. Pengembangan perangkat lunak tidak akan merubah file-file ataupun database yang ada pada saat ini tanpa adanya user.<br>
		&emsp;&emsp;**2.1.7**	**Operasi – operasi**<br>
				&emsp;&emsp;&emsp;Perangkat lunak dapat dijalankan di PC atau Laptop manapun. <br>
		&emsp;&emsp;**2.1.8**	**Kebutuhan – kebutuhan dalam tahapan adaptasi**<br>
	&emsp;**2.2**	**Fungsi – fungsi produk**<br>
		&emsp;&emsp;Fungsi dari Aplikasi Random Grup berdasarkan pengguna sistem ini adalah sebagai berikut :
		&emsp;&emsp;	a.	Membantu admin dan user dalam bertransaksi.
			&emsp;&emsp;b.	Program ini bisa membuat user membeli dan mendapatkan kwetansi secara online.
	&emsp;**2.3**	**Karakteristik pengguna**<br>
		&emsp;&emsp;Karakterisitk pengguna dari perangkat lunak ini adalah pengguna langsung berinteraksi dengan sistem tanpa harus dihubungkan dengan hak akses dan level autentifikasi.<br>
	&emsp;**2.4**	**Batasan – batasan**<br>
	&emsp;&emsp;	1.	Perangkat lunak hanya dijalankan di Windows (7, 8, dll).<br>
		&emsp;&emsp;2.	Waktu pengembangan perangkat lunak yang singkat membuat adanya kemungkinan tidak semua fungsi yang ada dapat dilaksanakan.<br>
		&emsp;&emsp;3.	Pengembangan perangkat lunak tidak akan merubah file-file ataupun database yang ada.<br>
	&emsp;**2.5**	**Asumsi – asumsi dan ketergantungan / keterkaitan**<br>
		&emsp;&emsp;Tidak ada batasan untuk membeli produk kerupuk”.<br>
	&emsp;**2.6**	**Kebutuhan – kebutuhan penyeimbang**
		&emsp;&emsp;(CRequirements dan D-Requirements)
<br>
<br>


**3. Kebutuhan Lain Yang Spesifik**<br>
<br>
	&emsp;**3.1 Performa** 
<br>
		&nbsp;&nbsp; &#183; Di jalankan desktop mana aja bisa
		&nbsp;&nbsp; &#183; Performa system sangat bergantung pada besarnya RAM desktop
<br>
<br>
	&emsp;**3.2 Keamanan Aplikasi**
<br>
		&nbsp;&nbsp; &#183; Keamanan login admin di sertai keamanan yang lumayan mempuni karena menggunakan framework yang lagi Up yaitu Laravel
<br>
		&nbsp;&nbsp; &#183; Di aplikasi terdapat nya fitur forgot password menggunakan email
<br>
<br>
&emsp;**3.3 Keamanan Data**
<br>
		&nbsp;&nbsp; &#183;Data  member  meliputi  nama,  alamat,  nomor  telepon,  alamat  email dan password  harus  disimpan  secara  baik  dan  classified,  terutama  untuk  data password akan dilakukan enkripsi.
<br>
		&nbsp;&nbsp; &#183;Memberikan  pernyataan  informasi  kepada  user,  bahwa  system  ini  berbasis desktop dan menjamin data member akan aman.
<br>
<br>
**4. Informasi Pendukung** 
<br>
<br>
&nbsp; &#183;Kebanyakan informasi pendukung kami dapatkan dari berbagai artikel, makalah, dan tugas akhir yang diperoleh dari internet.
<br>
<br>