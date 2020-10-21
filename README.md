# Apa itu VCS
• VCS atau Version Control System merupakan sebuah sistem yang
merekam perubahan-perubahan dari sebuah berkas atau sekumpulan
berkas dari waktu ke waktu sehingga Anda dapat melihat kembali
setiap perubahannya. <br>
• Salah satu DVCS (Distributed Version Control System) yang sangat
populer saat ini adalah git.<br>

# Apa itu Git?
• Git adalah salah satu sistem pengontrol versi (Version Control
System) pada proyek perangkat lunak yang diciptakan oleh Linus
Torvalds.
• Pengontrol versi bertugas mencatat setiap perubahan pada file
proyek yang dikerjakan oleh banyak orang maupun sendiri.
• Git dikenal juga dengan distributed revision control (VCS terdistribusi),
artinya penyimpanan database Git tidak hanya berada dalam satu
tempat saja.

# Instalasi Git
• Download Git, buka website resminya :
![Git Link](https://git-scm.com)
<br>
<br>
![Git Link](pictures/gitweb.png)<br>
• Kemudian unduh Git sesuai dengan arsitektur komputer kita. Kalau menggunakan 64bit, unduh yang 64bit. Begitu juga kalau menggunakan 32bit.<br>
• Selamat, Git sudah terinstal di Windows. Untuk mencobanya,
silahkan buka CMD atau PowerShell, kemudian ketik perintah : <br>
***git --version*** <br>
![Git Version](pictures/gitversion.png)

# Menambahkan Global Config
• Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi *user.name dan user.email*<br>
• konfigurasi ini bisa dilakukan untuk global repostiry atau individual repository. <br>
• apabila belum dilakukan konfigurasi, akan mengakibatkan terjadi kegagalan saat menjalankan perintah git commit<br>
• Config Global Repository<br>
***$ git config --global user.name “nama_user”***<br>
***$ git config --global user.email “nama_user”***<br>
![Git Version](pictures/globalconfig.png)