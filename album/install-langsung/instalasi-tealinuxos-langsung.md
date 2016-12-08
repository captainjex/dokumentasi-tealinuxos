Tutorial Instalasi TeaLinux
Dapat menggunakan dua media penyimpanan untuk digunakan sebagai bootable.
1.	Flashdisk
2.	DVD / CD
Langkah pertama 	: Download terlebih dahulu Tealinux di http://tealinuxos.org, bagi anda yang sudah memiliki .ISO dari TeaLinux bisa skip langkah ini.
Langkah kedua 		: Persiapkan software untuk burning / membuat bootable, bisa menggunakan Rufus, Universal USB Installer, Rosa Image Writer atau software yang biasa anda gunakan untuk membuat bootable.
Langkah ketiga		: Membuat bootable, disini saya menggunakan Universal USB Installer.
Langkah keempat		: Membuat Partisi bisa menggunakan tools pembuat partisi bawaan windows yang bernama “Create and format hard disk partition”, atau tools lain yang biasa anda gunakan untuk membuat partisi.
Sebagai contoh saya membuat partisi sebesar 50GB / 50000Mb, klik kanan pada disk yang ingin di shrink / dipecah.
Kenapa harus 50GB ?, karena ukuran 50GB itu ukuran yang ideal, ukuran minimalnya untuk linux ialah 20GB.
Langkah kelima 		: Masuk ke BIOS ubah mode BIOS ke Legacy (jika sebelumnya menggunakan mode UEFI/EFI), ubah boot priority USB HDD: ke urutan pertama setelah diubah save pengaturan tersebut dan restart.
Langkah keenam	: Setelah anda masuk ke installer TeaLinux anda akan disuguhkan beberapa pilihan, pilih saja Install TeaLinux.
Langkah ketujuh	: Disini saya menggunakan Bahasa English, anda juga bisa memilih Bahasa lain. 
 
Langkah kedelapan	: pada langkah ini anda dapat menceklis/tidak menceklis Install Third Party Software.
Langkah kesembilan 	: anda akan disuguhkan dengan beberapa pilihan, 
1.	Install TeaLinuxOS Alongside Them
a.	Pilihan ini dapat menyimpan berkas anda seperti document, dll.
2.	Erase disk and Install TeaLinuxOS
a.	Pilihan ini menghapus semua Disk anda pilihan ini dikhususkan bagi anda yang tidak ingin dualboot, karena pilihan ini akan menghapus semua OS dan data yang ada.
3.	Something else
a.	Pilihan ini dikhususkan bagi anda yang ingin dualboot. Karena didalam pilihan ini anda dapat mengatur partisi yang telah kita buat diawal tadi.

Langkah kesepuluh	: pilihan Something else, dalam nya seperti ini. Dan anda cari partisi yang sudah anda buat diawal.
partisi yang saya buat diawal berada di atas /dev/sda6 yang bertuliskan “Free Space”, setelah menemukan partisi yang dibuat diawal klik tombol + 
setelah anda menekan + anda akan disuguhkan tampilan seperti ini, untuk type for the new partition pilih saja logical dan untuk location for the new partition pilih end of this space. Untuk Use as: saya isi dengan SWAP dan Ext4. Dan untuk mount point (Khusus ext4) pilihlah / atau /home
/ = untuk system kalau di windows biasa kita temui sebagai localdisk C
/home = untuk penyimpanan berkas/data kalau di windows biasa kita temui sebagai localdisk D






untuk ukuran swap 2xram, saya mempunyai ram 4GB untuk ukuran swap pada contoh ini adalah 8GB / 8192Mb.

Setelah anda mengatur partisi seperti diatas selanjutnya anda tinggal klik Install Now. Anda akan disuguhkan dengan menu sebagai berikut :

Menu tersebut dimaksudkan untuk lokasi / waktu tempat anda berada. Setelah menu ini anda akan disuruh untuk memilih keyboard layout, langsung klik continue saja.



Dalam menu ini anda diharuskan mengisi data, seperti nama, nama computer, username, password dan ada 3 pilihan dibawah nya pilih saja require my password to log in,

Setelah menu tersebut anda akan memulai proses instalasi TeaLinux, Dan tampilan nya akan seperti di bawah. Anda hanya perlu menunggu proses instalasi sampai selesai.
Setelah proses instalasi selesai anda akan diminta untuk merestart / reboot, jangan lupa cabut/keluarkan bootable yang telah digunakan agar tidak kembali ke menu installer TeaLinux.

Gambar diatas merupakan gambar dari GRUB TeaLinux, setelah sampai ke tahap ini anda tinggal memilih OS mana yang akan anda gunakan disini saya mencoba untuk menggunakan TeaLinux.


Gambar diatas merupakan gambar Halaman Login TeaLinuxOS. Silahkan masukan password yang telah ditentukan sebelumnya. Setelah sampai pada tahap ini anda telah sukses melakukan instalasi TeaLinux.
Tutorial Instalasi TeaLinux
Dapat menggunakan dua media penyimpanan untuk digunakan sebagai bootable.
1.	Flashdisk
2.	DVD / CD
Langkah pertama 	: Download terlebih dahulu Tealinux di http://tealinuxos.org, bagi anda yang sudah memiliki .ISO dari TeaLinux bisa skip langkah ini.
Langkah kedua 		: Persiapkan software untuk burning / membuat bootable, bisa menggunakan Rufus, Universal USB Installer, Rosa Image Writer atau software yang biasa anda gunakan untuk membuat bootable.
Langkah ketiga		: Membuat bootable, disini saya menggunakan Universal USB Installer.
Langkah keempat		: Membuat Partisi bisa menggunakan tools pembuat partisi bawaan windows yang bernama “Create and format hard disk partition”, atau tools lain yang biasa anda gunakan untuk membuat partisi.
Sebagai contoh saya membuat partisi sebesar 50GB / 50000Mb, klik kanan pada disk yang ingin di shrink / dipecah.
Kenapa harus 50GB ?, karena ukuran 50GB itu ukuran yang ideal, ukuran minimalnya untuk linux ialah 20GB.
Langkah kelima 		: Masuk ke BIOS ubah mode BIOS ke Legacy (jika sebelumnya menggunakan mode UEFI/EFI), ubah boot priority USB HDD: ke urutan pertama setelah diubah save pengaturan tersebut dan restart.
Langkah keenam	: Setelah anda masuk ke installer TeaLinux anda akan disuguhkan beberapa pilihan, pilih saja Install TeaLinux.
Langkah ketujuh	: Disini saya menggunakan Bahasa English, anda juga bisa memilih Bahasa lain. 
 
Langkah kedelapan	: pada langkah ini anda dapat menceklis/tidak menceklis Install Third Party Software.
Langkah kesembilan 	: anda akan disuguhkan dengan beberapa pilihan, 
1.	Install TeaLinuxOS Alongside Them
a.	Pilihan ini dapat menyimpan berkas anda seperti document, dll.
2.	Erase disk and Install TeaLinuxOS
a.	Pilihan ini menghapus semua Disk anda pilihan ini dikhususkan bagi anda yang tidak ingin dualboot, karena pilihan ini akan menghapus semua OS dan data yang ada.
3.	Something else
a.	Pilihan ini dikhususkan bagi anda yang ingin dualboot. Karena didalam pilihan ini anda dapat mengatur partisi yang telah kita buat diawal tadi.

Langkah kesepuluh	: pilihan Something else, dalam nya seperti ini. Dan anda cari partisi yang sudah anda buat diawal.
partisi yang saya buat diawal berada di atas /dev/sda6 yang bertuliskan “Free Space”, setelah menemukan partisi yang dibuat diawal klik tombol + 
setelah anda menekan + anda akan disuguhkan tampilan seperti ini, untuk type for the new partition pilih saja logical dan untuk location for the new partition pilih end of this space. Untuk Use as: saya isi dengan SWAP dan Ext4. Dan untuk mount point (Khusus ext4) pilihlah / atau /home
/ = untuk system kalau di windows biasa kita temui sebagai localdisk C
/home = untuk penyimpanan berkas/data kalau di windows biasa kita temui sebagai localdisk D






untuk ukuran swap 2xram, saya mempunyai ram 4GB untuk ukuran swap pada contoh ini adalah 8GB / 8192Mb.

Setelah anda mengatur partisi seperti diatas selanjutnya anda tinggal klik Install Now. Anda akan disuguhkan dengan menu sebagai berikut :

Menu tersebut dimaksudkan untuk lokasi / waktu tempat anda berada. Setelah menu ini anda akan disuruh untuk memilih keyboard layout, langsung klik continue saja.



Dalam menu ini anda diharuskan mengisi data, seperti nama, nama computer, username, password dan ada 3 pilihan dibawah nya pilih saja require my password to log in,

Setelah menu tersebut anda akan memulai proses instalasi TeaLinux, Dan tampilan nya akan seperti di bawah. Anda hanya perlu menunggu proses instalasi sampai selesai.
Setelah proses instalasi selesai anda akan diminta untuk merestart / reboot, jangan lupa cabut/keluarkan bootable yang telah digunakan agar tidak kembali ke menu installer TeaLinux.

Gambar diatas merupakan gambar dari GRUB TeaLinux, setelah sampai ke tahap ini anda tinggal memilih OS mana yang akan anda gunakan disini saya mencoba untuk menggunakan TeaLinux.


Gambar diatas merupakan gambar Halaman Login TeaLinuxOS. Silahkan masukan password yang telah ditentukan sebelumnya. Setelah sampai pada tahap ini anda telah sukses melakukan instalasi TeaLinux.

