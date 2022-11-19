# LINUX
Linux adalah keluarga sistem operasi Unix yang open-source dan didasarkan pada Linux Kernel. Di dalam ‘keluarga’ ini juga termasuk sistem berbasis Linux populer seperti Ubuntu, Fedora, Mint, Debian, dan lain-lain. Sistem-sistem ini lebih tepatnya disebut sebagai distribusi atau distros.

Ketika mengoperasikan OS Linux, Kalian harus menggunakan shell, yaitu interface yang menyediakan akses ke layanan sistem operasi. Sebagian besar distribusi Linux menggunakan antarmuka pengguna grafis atau graphic user interface (GUI) sebagai shell-nya, terutama untuk memberikan kemudahan penggunaan bagi para pengguna. 

Jadi, jika hendak menggunakan Linux, Kalian disarankan tahu perintah dasar Linux. Pada kesempatann kali ini, Kami akan memberikan 50 command linux paling mendasar yang akan membantu Kalian sebagai pengguna baru untuk menjelajahi Linux.

-----------------------------------------------------------------------------------------------------------------------------------------------------------

# COMMAND LINUX

- man <perintah> untuk meilhat panduan

Melihat kegunaan dari perintah. Contohnya seperti | $ man apt | akan menampilkan manual penggunaan dari program apt.

- <perintah> –help untuk panduan ringkas

Hampir sama kegunaannya dengan man, akan tetapi hasil yang dimunculkan lebih ringkas daripada menggunakan perintah man.
    
- sudo untuk super user

Menjalankan program sebagai user root atau super user.

- ls untuk melihat direktori

Melihat daftar file & folder yang ada direktori pada saat itu, contohnya | $ ls /var/lib | digunakan untuk melihat apa saja yang ada pada folder lib.
    
- cd untuk masuk ke direktor

Masuk ke direktori yang diinginkan, contohnya seperti | $ cd /home/ | untuk menjadikan folder home sebagai direktori pada saat itu.
    
- mkdir <nama folder> untuk membuat folder

Membuat folder pada direktori kerja pada saat itu.
    
- pwd untuk melihat direktori aktif

Melihat direktori kerja yang pada saat itu aktif. Contoh hasilnya “/home/fasuyaaa
    
- vim untuk membuka text editor

Membuka text editor Vim untuk mengedit teks.
    
- cp <asal> <tujuan> untuk menyalin file

Menyalin file dan folder, bisa ke folder itu juga atau ke folder yang lain. Seperti | $ cp /home/test.php /var/www/html | akan memindahkan file test.php ke folder html. Sedangkan jika menyalin folder harus menggunakan opsi “-r”.
    
- mv <asal> <tujuan> untuk memindahkan folder

Memindahkan file dan folder, bisa ke folder itu juga atau ke folder yang lain. Seperti | $ cp /home/test.php /var/www/html | digunakan untuk memindahkan
file test.php ke folder html.
    
- rm <file> untuk menghapus file

Menghapus file, bisa juga untuk menghapus folder pada direktori tertentu.
    
- find <nama file> untuk mencari file

Mencari file dalam direktori hirarki. Contoh penggunaannya | $ find -name github.txt |.
 
- history untuk melihat riwayat

Perintah dasar linux ini digunakan untuk melihat riwayat perintah yang sudah pernah digunakan sebelumnya. Jika ingin mencari perintah tertentu bisa menggunakan $ history | grep apt untuk mencari nama perintah yang sudah pernah diketikan dan mengandung potongan kata apt.
    
- cat untuk melihat isi file

Melihat isi dari sebuah file, bisa juga untuk menggabungkan isi dari dua buah file. Contohnya | $ cat naskah.txt list.txt|.
    
- echo untuk menampilkan baris teks

Perintah ini digunakan untuk menampilkan satu baris teks. Bisa juga untuk menuliskan sebuah teks kedalam file, contohnya seperti berikut | $ echo “Hai">> sapaan.txt |. Perintah tersebut akan menuliskan “Hai" ke file “sapaan.txt”, jika file tersebut belum ada maka otomatis akan dibuat.

- grep untuk mencari kata

Menampilkan baris yang mengandung kata yang sama sesuai dengan pattern, contohnya seperti | $ grep -i source test.txt | maka akan memunculkan baris yang mengandung kata “source” pada “test.txt”.
    
- wc untuk menampilkan baris baru

Menampilkan baris baru, kata, dan bite pada sebuah file.
    
- sort untuk mengurutkan

Mengurutkan hasil dari pembacaan isi file.
    
- chmod untuk mengganti hak akses

Mengganti hak akses pada sebuah file. Contohnya jika ingin menggani hak akses host.txt menjadi 644 menggunakan baris perintah | $ chmod 644 host.txt |.
    
- chown mengganti hak milik

Mengganti pemilik dan group dari sebuah file. Contohnya jika ingin mengubah kepemilikan host.txt menjadi “fasuyaaa" menggunakan perintah | $ chown fasuyaaa:fasuyaaa host.txt |. Kata “fasuyaaa” di depan merujuk pada user sedangkan “fasuyaaa” di belakang merujuk pada nama group.
    
- su untuk mengganti user id

Mengganti user ID, contohnya | $ su <nama user> | atau menjadikan user pada saat itu menjadi super user.
    
- passwd untuk mengganti password

Perintah ini digunakan untuk mengganti password dari user. Mengetikan | $ sudo passwd | mengganti password user pada saat itu, sedangkan | $ sudo passwd fasuyaaa | digunakan untuk mengganti password user “fasuyaaa”.
    
- who untuk menampilkan user

Perintah dasar linux ini digunakan untuk menampilkan user pada saat ini dipakai.
    
- ps untuk menampilkan snapshot

Menampilkan snapshot  process yang sedang berjalan.
    
- kill untuk menghentikan program

Menghentikan program yang berjalan dengan menggunakan signal. Biasanya perintah ini ditambahkan opsi “-9” pada saat mengeksekusi. Contohnya seperti | $ 
sudo kill -9 373 |, 373 adalah PID dari proses yang sedang berjalan.
    
- tar untuk mengumpulkan file

Ini merupakan program pengarsipan atau untuk mengumpulkan beberapa file menjadi satu file, dengan ekstensi “namafile.tar”. Perintah ini juga menggunakan beberapa opsi, sebagai contoh, opsi “c” untuk membuat arsip, opsi “v” untuk operasi verbose, sedangkan “f” untuk menentukan nama file.
    
- zip untuk mengkompres file

Alat kompresi file menjadi “,zip”, hampir sama penggunaannya dengan tar.

- unzip untuk mengekstrak file

Mengekstrak/membongkar file “.zip”.
    
- ssh untuk akses jarak jauh

Mengakses komputer/server dari jarak jauh. Contoh perintah yang bisa digunakan seperti | $ ssh (namauser)@(ip) |.
    
- scp untuk menyalin file

Menyalin file dari host lain yang terhubung dalam satu jaringan. Contohnya | $ scp (file) (user)@(ip):(folder tujuan) |
    
- fdisk untuk menampilkan partisi

Menampilkan list partisi pada perangkat, biasanya menggunakan opsi “-l”, contohnya | $ sudo fdisk -l |
    
- mount untuk melampirkan file

Melampirkan sebuah filesystem kedalam satu folder besar. Sehingga tidak perlu melakukan akses langsung ke filesystem. Sebagai contoh menggunakan | $ sudo mount /dev/sda2 /mnt |. Perintah ini akan membuat isi partisi /dev/sda2 bisa diakses melalui /mnt.
    
- unmount untuk melakukan unmounth

Mengunlock perintah mount, contohnya | $ umount /mnt | digunakan untuk memutuskan perintah mount pada folder /mnt.
    
- du untuk menampilkan ukuran file

Menampilkan ukuran file secara rekursif.

- df untuk menampilkan disk space

Menampilkan penggunaan ruang disk pada filesystem.
    
- quota menampilkan sisa disk space

Menampilkan ruang disk dan batasannya.
    
- reboot untuk mulai ulang

Menjalankan perintah restart.
    
- poweroff untuk mematikan

Menjalankan perintah shutdown.
    
- gedit untuk membuka editor teks

Membuka Text Editor untuk mengedit teks file.
 
- kate untuk membuka teks editor

Program yang digunakan sebagai file editor pada KDE, beberapa sistem operasi harus melakukan instalasi terlebih dahulu. Fungsinya hampir sama seperti Gedit.
    
- bg membuat proses background

Membuat proses foreground untuk berjalan di background.
    
- fg <id program> membuat proses foreground

Membuat background proses menjadi foreground proses.
    
- jobs <id program> menampilkan identitas proses

Menampilkan nama dan ID dari background jobs.
    
- sed untuk melakukan filter teks

Memfilter teks pada sebuah file dan menggantinya dengan teks yang baru. Contoh penggunaannya sed | ‘s/fasuyaaa/host/g’ admin.txt |
    
- awk untuk memindahkan teks

Perintah ini digunakan untuk memindah teks dan memproses bahasa.
  
- locate untuk mencari file

Digunakan untuk menemukan atau mencari file.
    
- ifconfig untuk melihat ip

Melihat IP yang sedang terkoneksi dan network device apa saja yang tersedia.

- date untuk menampilkan tanggal

Menampilkan tanggal hari ini.
    
- nano merubah teks editor

Perintah digunakan sebagai text editor yang tidak perlu membuka jendela baru. Hampir sama dengan Vi namun lebih praktis.
    
- top melihat proses secara urut

Melihat semua proses yang sedang berjalan, diurutkan dari proses yang paling besar. Fungsinya hampir sama seperti system monitor.
    
- clear membersihkan terminal

Membersihkan jendela terminal. Jadi isi jendela terminal akan kosong, namun jika di scroll keatas maka perintah yang sebelumnya dijalankan masih bisa terlihat.
    
- dpkg -i (namapackage).deb instalasi paket

Berguna untuk melakukan instalasi paket dengan ekstensi “.deb”. Terkadang bisa juga menggunakan program “gdebi”, tetapi harus install.
    
- uname melihat versi kernel

Menampilkan versi kernel yang dipakai, tanggal instalasi, dan jenis arsitektur sistem operasi.
    
- (simbol bintang) untuk mencantumkan deskripsi

Ini adalah sebuah tanda yang digunakan untuk mendeskripsikan satu string yang digunakan untuk memberikan deskripsi singkat dari satu elemen.


-----------------------------------------------------------------------------------------------------------------------------------------------------------
# AKHIR KATA

Hampir semua perintah dasar Linux itu sederhana dan bisa dikembangkan sesuai dengan kebutuhan eksekusi. Jika tidak hafal dengan penulisannya Kalian bisa menekan tombol “Tab” pada keyboard untuk menggunakan fitur auto-complete di terminal.

Itulah kurang lebih 50+ perintah dasar Linux yang paling tidak diketahui saat menggunakan sistem operasi Linux.
Meskipun masih banyak perintah yang lainnya, paling tidak perintah – perintah tersebut menjadi dasar mengenali perintah Linux lain. Supaya Kalian bisa mengoperasikan sistem operasi LINUX dengan mudah.

-----------------------------------------------------------------------------------------------------------------------------------------------------------
# SOURCE: https://www.niagahoster.co.id/blog/perintah-dasar-linux/
