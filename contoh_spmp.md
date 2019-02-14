
**1. Pendahuluan**
	<br>
	**&nbsp;1.1 Gambaran proyek** 
	<br>
		&nbsp;Aplikasi ini merupakan aplikasi penyewaan jasa travel berbasis website yang mana client dapat melakukan booking secara online tanpa harus datang ke tempat penyewaan jasa travel tersebut. Selain itu, client dapat melakukan proses transaksi melalui aplikasi ini. Terdapat juga form tanya jawab antara admin dengan client apabila ada bagian informasi dalam website yang kurang dipahami oleh client.
		Disini yang menjadi client adalah orang yang akan menyewa travel sedangkan admin adalah pemilik travel. Aplikasi ini dibuat untuk memudahkan client dalam proses penyewaan travel sehingga dapat mengefisienkan waktu penyewaan dan pembayaran.
		Dalam aplikasi ini juga terdapat map yang mana akan menunjukan lokasi tempat client yang akan dijemput oleh travel.
	<br>
	<br>
	**&nbsp;1.2 Dokumen-dokumen dalam proyek** 
	<br>	
		&nbsp;Saat  mengerjakan  projek  ini,  pencatatan  kegiatan  yang  telah  dilakukan  ditulis didalam log book kelompok, anggota yang telah mengerjakan tugas sesuai projek kegiatannya  dicatat  dalam  log  book,  selain  log  book  dokumen  yang  berkaitan dengan  projek  ini  meliputi  requirtments,  penjadwalan,  pembagian  tugas,  dan referensi-referensi yang berkaitan dengan pembuatan projek kami.
	<br>
	<br>	
	**&nbsp;1.3  Evolusi SPMP**
	<br>
		&nbsp;	Dokumen ini bersifat freeware, jadi siapa saja boleh untuk memanfaatkan
		dokumen ini untuk hal yang positif. Tentu ada hal-hal yang tidak boleh dilakukan
		dalam pemanfaatan dokumen ini, seperti menjualbelikan dokumen ini secara ilegal,
		atapun mengubah dokumen tanpa dasar yang jelas.
	<br>
	<br>
	**&nbsp;1.4  Material acuan**
		<br>
		&nbsp;Materi  yang menjadi acuan dalam pembuatan projek ini menggunakan standar IEEE, karena menyediakan kerangka kerja yang menggabungkan seluruh spektrum proses  siklus  hidup  perangkat  lunak.  Dan  juga  standar  IEEE  untuk  membentuk model  yang  diakui  secara  internasional  dari  kehidupan  perangkat  lunak  umum, siklus  proses  yang  dapat  direferensikan  oleh  industri  perangkat  lunak  diseluruh dunia,  untuk  mempromosikan  pemahaman  diantara  pihak  bisnis  dengan  aplikasi umum serta mengakui proses, kegiatan dan tugas.
		<br>
		<br>
		&nbsp;IEEE  adalah  sebuah  organisasi  profesi  nirlaba  yang  terdiri  dari  banyak  ahli dibidang   teknik   yang   mempromosikan   pengembangan   standar-standar   dan bertindak sebagai pihak yang mempercepat teknologi-teknologi baru dalam semua aspek dalam industry dan rekayasa (engineering), yang mencakup telekomunikasi, jaringan komputer, kelistrikan, antariksa, dan elektronika. Tujuan inti IEEE adalah mendorong     inovasi     teknologi     dan     kesempurnaan     untuk     kepentingan kemanusiaan.Visi  IEEE  adalah  akan  menjadi  penting  untuk  masyarakat  teknis global  dan  professional  teknis  dimana-mana  dan  dikenal  secara  universal  untuk kontribusi  teknologi  dan  teknis  yang  professional  dalam  meningkatkan  kondisi perkembangan  global.  Standar  dalam  IEEE  adalah  mengatur  fungsi,  kemampuan dan interoperabilitas dari berbagai macam  produk dan layanan yang mengubah cara orang hidup, bekerja dan berkomunikasi.
	<br>
	<br>
	**&nbsp;1.5  Definisi dan akronim (singkatan)**
	<br>
		&nbsp;Dalam penulisan dokumen pembuatan proyek ini, ada beberapa kata yang mungkin akan sulit dipahami, diantaranya:
		<br>
			•	RFID adalah sebuah metode identifikasi dengan menggunakan sarana yang disebut label RFID atau transponder untuk menyimpan dan mengambil data jarak jauh.
			<br>
			•	IEEE adalah standar yang mendefinisikan lapisan fisik dan sublapisan media akses control dari lapisan data-link dari standar Ethernet berkabel.
<br>
<br>
**2.Organisasi Proyek**
	<br>
	**&nbsp;2.1 Model proses**
	<br>
	&nbsp;Disini kami menggunakan Model Waterfall dalam membangun system ini.
	<br>
	**&nbsp;&nbsp;2.1.1.	Definisi**
	<br>
&nbsp;&nbsp;Model waterfall adalah suatu proses pengembangan perangkat lunak berurutan, dimana kemajuan dipandang sebagai terus mengalir kebawah (seperti air terjun) melewati fase-fase perencanaan, pemodelan, implementasi (kontruksi) dan pengujian.
<br>
**&nbsp;&nbsp;2.1.2.	Tahapan**
<br>
&nbsp;&nbsp;a.	Tahap inisiasi adalah Analisa kebutuhan system yang akan dibuat dan harus dapat dimengerti oleh client dan developer. Pada tahap ini client harus dapat menjelaskan dan mendefinisikan tujuan dari system yang ingin dibangun.
<br>
&nbsp;&nbsp;b.	Tahap desain system, pada tahap ini developer merancang suatu arsitektur system berdasarkan hasil dari tahap sebelumnya yaitu tahap inisiasi.
<br>
&nbsp;&nbsp;c.	Tahap implementasi, dimana keseluruhan desain sistem yang telah disusun sebelumnya akan diubah menjadi kode-kode program dan modul-modul yang nantinya akan diintegrasikan menjadi sebuah sistem yang lengkap sesuai dengan kontrak kerja.
<br>
&nbsp;&nbsp;d.	Tahap berikutnya adalah integrasi dan testing. Pada tahap ini sistem yang sudah dibuat akan diintegrasikan dan di test untuk menguji apakah sistem tersebut telah berfungsi dengan baik dan yang tidak kalah penting adalah sesuai dengan kontrak yang telah disetujui.
<br>
&nbsp;&nbsp;e.	Tahap akhir adalah pemeliharaan yang termasuk diantaranya instalasi dan proses perbaikan sistem apabila ditemukan adanya kesalahan/bug yang tidak ditemukan pada tahap testing.
<br>
**&nbsp;&nbsp;2.1.3.	Keunggulan dan Manfaat**
<br>
&nbsp;&nbsp;Keunggulan model pendekatan pengembangan software dengan metode waterfall adalah pencerminan kepraktisan rekayasa, yang membuat kualitas software tetap terjaga karena pengembangannya yang terstruktur dan terawasi. Disisi lain model ini merupakan jenis model yang bersifat dokumen lengkap, sehingga proses pemeliharaan dapatdilakukan dengan mudah. Akan tetapi dikarenakan dokumentasi yang lengkap dan sangat teknis, membuat pihak klien sulit membaca dokumen yang berujung pada sulitnya komunikasi antar pengembang dan klien. Dokumentasi kode program yang lengkap juga secara tak langsung menghapus ketergantungan pengembang terhadap pemrogram yang keluar dari tim pengembang. Hal ini sangat menguntungkan bagi pihak pengembang dikarenakan proses pengembangan perangkat lunak tetap dapat dilanjutkan tanpa bergantung pada pemrogram tertentu.
<br>
**&nbsp;&nbsp;2.1.4.	Kelemahan**
<br>
&nbsp;&nbsp;Kelemahan pengembangan software dengan metode waterfall yang utama adalah lambatnya proses pengembangan perangkat lunak. Dikarenakan prosesnya yang satu persatu dan tidak bisa diloncat-loncatmenjadikan model klasik ini sangat memakan waktu dalam pengembangannya. Disisi lain pihak klien tidak dapatmencoba sistem sebelum sistem benar-benar selesai pembuatannya. Kelemahan yang lain adalah kinerja personil yang tidak optimal dan efisien karena terdapat proses menunggu suatu tahapan selesai terlebih dahulu. Secara keseluruhan model pendekatan pengembangan software dengan metode waterfall cocok untuk pengembangan software / perangkat lunak dengan tingkat resiko yang kecil, dan memiliki ukuran yang kecil serta waktu pengembangan yang cukup panjang. Model ini tidak disarankan untuk ukuran perangkat lunak yang besar dantingkat resiko yang besar.
<br>
	<br>
	**&nbsp;2.2 Struktur Organisasi**
	<br>
	&nbsp;&nbsp;a.	Project Manager
	<br>
	&nbsp;&nbsp;b.	Programmer
	<br>
	&nbsp;&nbsp;c.	System Analis
	<br>
	&nbsp;&nbsp;d.	Database Administrator
	<br>
	**&nbsp;2.3 Batasan dan antarmuka organisasi**
	<br>
	&nbsp;&nbsp;a.	Project Manager harus menjadi pengawas dari anggota-anggotanya bilamana saat anggota lalai dengan tugas-tugasnya, project manager berhak menegur dan bagi anggota tidak berhak melawan jika ditegur dan untuk project manager sendiri tidak berhak semena-mena dengan jabatannya.
	<br>
	&nbsp;&nbsp;b.	Programmer dimana dia bertanggung jawab untuk membuat dan menyempurnakan suatu program.
	<br>
	&nbsp;&nbsp;c.	System Analis bertugas memberikan gambaran project dan alur pengkoding pada programmer.
	<br>
	&nbsp;&nbsp;d.	Database Administrator bertugas menyusun database yang akan digunakan dalam project.
	<br>
	**&nbsp;2.4 Lingkup tanggung jawab**
	<br>
	&nbsp;&nbsp;a.	Project Manager adalah seseorang mempunyai tanggung jawab dan tugas yang besar dalam sebuah tim, tidak hanya terfokus pada hal-hal yang teknis sifatnya. Manager juga harus mampu memajemen tim dengan baik, agar target projek dapat tercapai. Selain itu memberi pengarahan, memonitoring kinerja tim, serta serta membagi tugas juga bagian tanggung jawab dari seorang manager.
	<br>
	&nbsp;&nbsp;b.	Programmer, seorang programer bertugas untuk mengimplementasikan dari sistem yang sudah dirancang didesain. Programmer dituntut dapat menuliskan code program dengan baik, dan efesien. Hal ini dimaksudakan untuk menghindari terjadinya banyak error dalam proses implementasinya.
	<br>
	&nbsp;&nbsp;c.	System Analis, banyak hal yang harus dilakukan oleh seorang sistem analis, terutama yang berkaitan dengan pemecahan masalah. Seorang sistem analis harus mampu menganalisa segala kemungkinan dari pemasalahan yang ada, dan dapat mengasilkan solusi yang tepat dari permasalahan tersebut. Menentukan sistem yang tepat merupakan bagian dari tugas seorang sistem analis, sehingga kinerja tim dapat berjalasan secara efesien.
	<br>
	&nbsp;&nbsp;d.	Database Administrator orang yanga berfungsi mengatur dan mengawasi sumber daya pada database yaitu data itu sendiri dan DBMS software, DBA bertanggung jawab untuk mangizinkan akses, memonitor dan mengkoordinasi database dan membeli software dan hardware yang dibutuhkan. Dan menyelesaikan masalah seperti kebobolan kemananan dan system respion yang lambat
	<br>

**3.Proses Manajerial**
	<br>
	**&nbsp;3.1 Tujuan dan prioritas manajemen**
	<br>
	**&nbsp;3.2 Asumsi-asumsi, ketergantungan/keterkaitan, dan batasan-batasan**
	<br>
	**&nbsp;3.3 Manajemen resiko**
	<br>
	**&nbsp;3.4 Mekanisme monitoring dan kontroling**
	<br>
	**&nbsp;3.5 Perencanaan staf**
	<br>

**4. Proses Teknis**
	<br>
	**&nbsp;4.1 Metoda, tool, dan tekn**
	<br>
	**&nbsp;4.2 Dokumentasi perangkat lunak**
	<br>
	**&nbsp;4.3 Fungsi-fungsi petunjuk proyek**
	<br>

**5. Paket pekerjaan, jadwal, dan budget**
	<br>
	**&nbsp;5.1 Paket pekerjaann**
	<br>
	**&nbsp;5.2 Ketergantungan/keterkaitan**
	<br>
	**&nbsp;5.3 Kebutuhan-kebutuhan sumber daya**
	<br>
	**&nbsp;5.4 Alokasi budget dan sumber daya**
	<br>
	**&nbsp;5.5 Jadwal**
	<br>

	