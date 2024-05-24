- 👋 Hi, I’m @Zahraoktavian
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Zahraoktavian/Zahraoktavian is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
Memulai/Menulis di GitHub/Mulai menulis di GitHub/Sintaks pemformatan dasar
Sintaks penulisan dan pemformatan dasar
Buat pemformatan canggih untuk prosa dan kode Anda di GitHub dengan sintaks sederhana.

Dalam artikel ini
Judul
Gaya teks
Mengutip teks
Kode kutipan
Model warna yang didukung
Link
Tautan bagian
Tautan relatif
Gambar
Daftar
Daftar tugas
Menyebutkan orang dan tim
Merujuk masalah dan pull request
Mereferensikan sumber daya eksternal
Mengupload aset
Menggunakan emoji
Paragraf
Catatan kaki
Tanda
Menyembunyikan konten dengan komentar
Mengabaikan pemformatan Markdown
Menonaktifkan rendering Markdown
Bacaan lebih lanjut
Judul
Untuk membuat judul, tambahkan satu hingga enam simbol sebelum teks judul Anda. Jumlah yang Anda gunakan akan menentukan tingkat hierarki dan ukuran jenis huruf judul.##

# A first-level heading
## A second-level heading
### A third-level heading
Cuplikan layar Markdown GitHub yang dirender memperlihatkan contoh header h1, h2, dan h3, yang turun dalam ukuran tipe dan bobot visual untuk menunjukkan tingkat hierarki menurun.

Saat Anda menggunakan dua atau lebih judul, GitHub secara otomatis menghasilkan daftar isi yang dapat Anda akses dengan mengklik di dalam header file. Setiap judul judul tercantum dalam daftar isi dan Anda dapat mengklik judul untuk menavigasi ke bagian yang dipilih.

Cuplikan layar file README di repositori sumber terbuka GitHub Docs dengan menu tarik-turun untuk daftar isi terbuka. Ikon daftar isi diuraikan dalam warna oranye gelap.

Gaya teks
Anda dapat menunjukkan penekanan dengan teks tebal, miring, coret, subskrip, atau superskrip di bidang komentar dan file..md

Gaya	Sintaksis	Pintasan keyboard	Contoh	Hasil
Berani	** ** atau __ __	Command+B (Mac) atau + (Windows/Linux)CtrlB	**This is bold text**	Ini adalah teks tebal
Miring	* * atau _ _	Command+I (Mac) atau + (Windows/Linux)CtrlI	_This text is italicized_	Teks ini dicetak miring
Coret	~~ ~~	Tidak	~~This was mistaken text~~	Ini adalah teks yang keliru
Cetak miring tebal dan bertumpuk	** ** dan _ _	Tidak	**This text is _extremely_ important**	Teks ini sangat penting
Semua tebal dan miring	*** ***	Tidak	***All this text is important***	Semua teks ini penting
Subskrip	<sub> </sub>	Tidak	This is a <sub>subscript</sub> text	Ini adalah Subskrip Teks
Superscript	<sup> </sup>	Tidak	This is a <sup>superscript</sup> text	Ini adalah Superscript Teks
Mengutip teks
Anda dapat mengutip teks dengan file .>

Text that is not a quote

> Text that is a quote
Teks yang dikutip diindentasi, dengan warna tipe yang berbeda.

Cuplikan layar GitHub Markdown yang dirender memperlihatkan contoh teks yang dikutip. Kutipan diindentasi dengan garis vertikal di sebelah kiri, dan teksnya berwarna abu-abu gelap daripada hitam.

Nota: Saat melihat percakapan, Anda dapat mengutip teks dalam komentar secara otomatis dengan menyorot teks, lalu mengetik . Anda dapat mengutip seluruh komentar dengan mengklik , lalu Kutip balasan. Untuk informasi selengkapnya tentang pintasan keyboard, lihat "Pintasan keyboard."R

Kode kutipan
Anda dapat memanggil kode atau perintah dalam kalimat dengan backticks tunggal. Teks dalam tanda kutip terbalik tidak akan diformat. Anda juga dapat menekan pintasan keyboard + (Mac) atau + (Windows/Linux) untuk memasukkan tanda kutip terbalik untuk blok kode dalam baris Markdown.CommandECtrlE

Use `git status` to list all new or modified files that haven't yet been committed.
Cuplikan layar GitHub Markdown yang dirender menunjukkan tampilan karakter yang dikelilingi oleh backticks. Kata-kata "git status" muncul dalam jenis huruf lebar tetap, disorot dalam warna abu-abu muda.

Untuk memformat kode atau teks ke dalam bloknya sendiri yang berbeda, gunakan triple backticks.

Some basic Git commands are:
```
git status
git add
git commit
```
Cuplikan layar GitHub Markdown yang dirender menunjukkan blok kode. Kata-kata "git status," "git add," dan "git commit" muncul dalam jenis huruf dengan lebar tetap, disorot dalam warna abu-abu muda.

Untuk informasi selengkapnya, lihat "Membuat dan menyoroti blok kode."

Jika Anda sering mengedit cuplikan kode dan tabel, Anda dapat mengambil manfaat dari mengaktifkan font lebar tetap di semua bidang komentar di GitHub. Untuk informasi selengkapnya, lihat "Tentang menulis dan memformat di GitHub."

Model warna yang didukung
Dalam masalah, permintaan tarik, dan diskusi, Anda dapat memanggil warna dalam kalimat dengan menggunakan backticks. Model warna yang didukung dalam backticks akan menampilkan visualisasi warna.

The background color is `#ffffff` for light mode and `#000000` for dark mode.
Cuplikan layar Markdown GitHub yang dirender menunjukkan bagaimana nilai HEX dalam backticks membuat lingkaran warna kecil. #ffffff menunjukkan lingkaran putih, dan #000000 menunjukkan lingkaran hitam.

Berikut adalah model warna yang saat ini didukung.

Warna	Sintaksis	Contoh	Hasil
HEX	`#RRGGBB`	`#0969DA`	Cuplikan layar penurunan harga GitHub yang dirender menunjukkan bagaimana nilai HEX #0969DA muncul dengan lingkaran biru.
RGB	`rgb(R,G,B)`	`rgb(9, 105, 218)`	Cuplikan layar penurunan harga GitHub yang dirender menunjukkan bagaimana nilai RGB 9, 105, 218 muncul dengan lingkaran biru.
HSL	`hsl(H,S,L)`	`hsl(212, 92%, 45%)`	Cuplikan layar penurunan harga GitHub yang dirender menunjukkan bagaimana nilai HSL 212, 92%, 45% muncul dengan lingkaran biru.
Catatan:

Model warna yang didukung tidak boleh memiliki spasi di depan atau di belakang dalam backticks.
Visualisasi warna hanya didukung dalam masalah, permintaan tarik, dan diskusi.
Link
Anda dapat membuat link sebaris dengan membungkus teks link dalam tanda kurung , lalu membungkus URL dalam tanda kurung . Anda juga dapat menggunakan pintasan keyboard + untuk membuat tautan. Saat Anda memilih teks, Anda bisa menempelkan URL dari clipboard Anda untuk membuat tautan secara otomatis dari pilihan.[ ]( )CommandK

Anda juga dapat membuat hyperlink Markdown dengan menyorot teks dan menggunakan pintasan keyboard +. Jika Anda ingin mengganti teks dengan link, gunakan pintasan keyboard ++.CommandVCommandShiftV

This site was built using [GitHub Pages](https://pages.github.com/).

Cuplikan layar GitHub Markdown yang dirender menunjukkan bagaimana teks dalam tanda kurung, "GitHub Pages," muncul sebagai hyperlink biru.

Nota: GitHub secara otomatis membuat tautan ketika URL yang valid ditulis dalam komentar. Untuk informasi selengkapnya, lihat "Referensi dan URL tertaut otomatis."

Tautan bagian
Anda dapat menautkan langsung ke bagian dalam file yang dirender dengan mengarahkan kursor ke judul bagian untuk mengekspos .

Cuplikan layar README untuk repositori. Di sebelah kiri judul bagian, ikon link digariskan dengan warna oranye gelap.

Tautan relatif
Anda dapat menentukan tautan relatif dan jalur gambar dalam file yang dirender untuk membantu pembaca menavigasi ke file lain di repositori Anda.

Tautan relatif adalah tautan yang relatif terhadap file saat ini. Misalnya, jika Anda memiliki file README di root repositori Anda, dan Anda memiliki file lain di docs/CONTRIBUTING.md, tautan relatif ke CONTRIBUTING.md di README Anda mungkin terlihat seperti ini:

[Contribution guidelines for this project](docs/CONTRIBUTING.md)
GitHub akan secara otomatis mengubah tautan relatif atau jalur gambar Anda berdasarkan cabang apa pun yang Anda gunakan saat ini, sehingga tautan atau jalur selalu berfungsi. Jalur tautan akan relatif terhadap file saat ini. Tautan yang dimulai dengan akan relatif terhadap root repositori. Anda dapat menggunakan semua operan tautan relatif, seperti dan ././../

Teks tautan Anda harus berada pada satu baris. Contoh di bawah ini tidak akan berfungsi.

[Contribution 
guidelines for this project](docs/CONTRIBUTING.md)
Tautan relatif lebih mudah bagi pengguna yang mengkloning repositori Anda. Tautan absolut mungkin tidak berfungsi dalam klon repositori Anda - sebaiknya gunakan tautan relatif untuk merujuk ke file lain di dalam repositori Anda.

Gambar
Anda dapat menampilkan gambar dengan menambahkan dan membungkus teks alt dalam format . Teks alternatif adalah teks pendek yang setara dengan informasi dalam gambar. Kemudian, bungkus tautan untuk gambar dalam tanda kurung .![ ]()

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg)

Tangkapan layar komentar tentang masalah GitHub yang menunjukkan gambar, ditambahkan dalam Markdown, dari Octocat tersenyum dan mengangkat tentakel.

GitHub mendukung penyematan gambar ke dalam masalah Anda, permintaan tarik, diskusi, komentar, dan file. Anda dapat menampilkan gambar dari repositori Anda, menambahkan tautan ke gambar online, atau mengunggah gambar. Untuk informasi selengkapnya, lihat "Mengupload aset"..md

Nota: Saat Anda ingin menampilkan gambar yang ada di repositori Anda, gunakan tautan relatif alih-alih tautan absolut.

Berikut adalah beberapa contoh untuk menggunakan tautan relatif untuk menampilkan gambar.

Konteks	Tautan Relatif
Dalam file di cabang yang sama.md	/assets/images/electrocat.png
Dalam file di cabang lain.md	/../main/assets/images/electrocat.png
Dalam masalah, tarik permintaan dan komentar dari repositori	../blob/main/assets/images/electrocat.png?raw=true
Dalam file di repositori lain.md	/../../../../github/docs/blob/main/assets/images/electrocat.png
Dalam masalah, tarik permintaan dan komentar dari repositori lain	../../../github/docs/blob/main/assets/images/electrocat.png?raw=true
Catatan: Dua tautan relatif terakhir dalam tabel di atas akan berfungsi untuk gambar dalam repositori pribadi hanya jika pemirsa setidaknya memiliki akses baca ke repositori pribadi yang berisi gambar-gambar ini.

Untuk informasi selengkapnya, lihat "Tautan Relatif."

Menentukan tema gambar ditampilkan
Anda dapat menentukan tema gambar ditampilkan untuk Markdown dengan menggunakan elemen HTML dalam kombinasi dengan fitur media. Kami membedakan antara mode warna terang dan gelap, jadi ada dua opsi yang tersedia. Anda dapat menggunakan opsi ini untuk menampilkan gambar yang dioptimalkan untuk latar belakang gelap atau terang. Ini sangat membantu untuk gambar PNG transparan.<picture>prefers-color-scheme

Misalnya, kode berikut menampilkan gambar matahari untuk tema terang dan bulan untuk tema gelap:

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
</picture>
