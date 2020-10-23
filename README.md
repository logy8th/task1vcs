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
• Download Git, buka website resminya : [Git Link](https://git-scm.com)
<br>
<br>
![Git Link](pictures/gitweb.png)<br>
• Kemudian unduh Git sesuai dengan arsitektur komputer kita. Kalau menggunakan 64bit, unduh yang 64bit. Begitu juga kalau menggunakan 32bit.<br>
• Selamat, Git sudah terinstal di Windows. Untuk mencobanya,
silahkan buka CMD atau PowerShell, kemudian ketik perintah : <br>
***--> git --version*** <br>
![Git Version](pictures/gitversion.png)

# Menambahkan Global Config
• Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi *user.name dan user.email*
<br>
• Konfigurasi ini bisa dilakukan untuk global repostiry atau individual repository.
<br>
• Apabila belum dilakukan konfigurasi, akan mengakibatkan terjadi kegagalan saat menjalankan perintah git commit
<br>
• Config Global Repository<br>
***--> git config --global user.name “nama_user”***<br>
***--> git config --global user.email “nama_user”***<br>
![Git Version](pictures/globalconfig.png)

# Perintah Dasar Git
• **git init**, Perintah untuk membuat repository local<br>
• **git add**, Perintah untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit.<br>
• **git commit**, Perintah untuk menyimpan perubahan kedalam database git. <br>
• **git push -u origin master**, Perintah untuk mengirim perubahan pada repository local menuju server repository.<br>
• **git clone [url]**, Perintah untuk membuat working directory yang diambil dari repositry sever.<br>
• **git remote add origin [url]**, Perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory)<br>
• **git pull**, Perintah untuk mengambil/mendownload perubahan terbaru dari server repository ke local repository

# Membuat Reposiory Local
• Buka direktory aktif, misal: C:\Users\Fall\Desktop\gittask1 (buka menggunakan Windows Explorer)<br><br>
• klik kanan pada direktory aktif tersebut, dan pilih menu Git Bash, sehingga muncul git bash command.<br><br>
• Buat direktory project praktikum pertama dengan nama gittask1.<br><br>
• Sehingga terbentuk satu direktori baru dibawahnya, selanjutnya masuk kedalam direktori tersebut dengan perintah cd (change directory) direktory aktif menjadi: **C:\Users\Fall\Desktop\gittask1**

# Membuat Reposiory Local
• Jalankan perintah git init, untuk membuat repository local.<br>
**$ git init**<br>
![Git Version](pictures/gitinit.png)
<br>
• Repository baru berhasil di inisialisasi, dengan terbentuknya satu direktori hidden dengan nama **.git** <br>
• Pada direktori tersebut, semua perubahan pada working directory akan disimpan.

# Menambahkan File baru pada repository
• Untuk membuat file dapat menggunakan text editor, lalu menyimpan filenya pada direktori aktif (repository)<br>
**$ echo “# Latihan 1” >> CUMATEXT.md**
• Disini kita akan coba buat satu file bernama CUMATEXT.md (text file)
• File CUMATEXT.md berhasil dibuat. <br>
![Git Version](pictures/gitecho.png)