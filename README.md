*Project* ini merupakan website portofolio Jonathan Levi (19623013). Website ini menggunakan HTML, CSS dan framework CSS, yaitu Bootstrap, dan dipublikasi pada GitHub Pages (github.io).

# Identitas
> **NAMA:** Jonathan Levi  
> **NIM:** 19623013 / 13523132  
> **JURUSAN:** TEKNIK INFORMATIKA (IF)  

# Cara Kerja
Ketik <a href="https://jonathan-levi.github.io" target=_blank>"jonathan-levi.github.io"</a> pada kolom pencarian di *browser*, atau klik link-nya. Untuk mengunjungi halaman lainnya:
>- ***Mobile***: tekan *hamburger menu* (≡) pada bagian kanan atas website, lalu pilih halaman yang diinginkan.
> - **PC/Laptop/Tablet**: pilih halaman pada bagian kiri website yang diinginkan.

# *Deployment*
Untuk *deployment*, saya menggunakan GitHub Pages (github.io). Saya memilih  GitHub Pages daripada yang lainnya dengan beberapa alasan:
> - **Hanya perlu fokus ke lebih sedikit platform**  
Jika menggunakan platform seperti Vercel atau Netlify, saya harus mengecek Git, GitHub, website yang saya pakai untuk *deployment* dan website portofolio saya. Sedangkan untuk GitHub Pages, saya hanya mengecek Git, GitHub dan website portofolio saja.
> - **Pembuatan akun Netlify bermasalah**  
Saya sebelumnya ingin mencoba memakai Netlify, namun akun saya selalu langsung di-*suspend* karena "*suspicious activity*" (aktivitas yang mencurigakan).
> - ***Link*/URL vercel.app terlalu panjang dan tidak bisa memakai nama yang diinginkan**  
Kecuali jika menggunakan domain *custom* sendiri, namun saya rasa tidak *worth it* membelinya untuk sekarang.
> - **Punya pengalaman dengan GitHub Pages**  
Saya lebih *familiar* dengan GitHub Pages, namun tidak dengan Vercel atau Netlify.

# *Framework*
*Framework* yang saya pakai adalah:
> - **Bootstrap**  
  Framework CSS ini digunakan untuk ***grid system*** pada halaman utama demi mendapat tampilan yang responsif (foto dan teks bersebelahan untuk layar besar; teks di bawah foto untuk layar kecil); **_card_** untuk mempermudah halaman *projects*

# Tampilan Responsif
Untuk mendapat tampilan responsif, saya menggunakan:
> - **CSS biasa untuk *list* halaman**  
*List* langsung tampil di bagian kiri untuk layar besar dan tersembunyi di *hamburger menu* di bagian kanan atas untuk layar kecil.
> - **Bootstrap untuk halaman utama**  
*Grid system*. Info lebih lanjut pada bagian [Framework](#framework) di atas.

# Kendala
> - **Pembuatan *hamburger menu* yang ribet** karena kurangnya pengalaman
> - ***Welcome screen* yang tidak sepenuhnya hilang di Firefox** setelah beberapa detik, namun bekerja di browser lain (konten dapat dilihat namun elemen seperti teks dan *hamburger menu* tidak dapat di-*highlight* atau ditekan). Solusinya adalah dengan menambah `visibility: hidden`