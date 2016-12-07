Instalasi TeaLinux Menggunakan VirtualBox
Bahan yang harus dipersiapkan sebelum instalasi TeaLinuxOS di VirtualBox antara lain sebagai berikut :

1.	VirtualBox
2.	TeaLinuxOS.ISO

Langkah pertama 	: Buka VirtualBox
![Ketika membuka VirtualBox] (album/virtualbox/virtualboxhome.png)

Langkah kedua 		: Klik tombol New, dan akan muncul tampilan seperti dibawah.
Name 	: (Diisi bebas)
Type	: Linux
Version	: Linux 2.6 / 3.x / 4.x (64-bit/32-bit) menyesuaikan dengan .ISO TeaLinuxOS yang anda download dan version Laptop / PC anda 64-bit atau 32-bit.
![Tampilan virtualbox ketika klik New] (album/virtualbox/virtualboxnew.png)

Langkah ketiga		: Setelah klik Next anda akan menemui tampilan seperti dibawah. Langsung klik Next lagi bisa ataupun anda bisa mengisi memory size dengan jumlah ram yang anda punya.
![Setting VirtualMemori] (album/virtualbox/virtualboxmemorysize.png)

Langkah keempat	: Membuat memori virtual di hardisk, langsung klik create.
![Membuat Hard Disk] (album/virtualbox/virtualboxhardisk.png)

setelah klik create anda akan menemukan tampilan seperti dibawah pilih saja VDI (Virtual Disk Image), lalu klik next.
![Type Hard Disk] (album/virtualbox/virtualboxhardiskfiletype.png)

Setelah klik Next anda akan menemui tampilan seperti dibawah, pilih Dynamically Allocated dan klik Next lagi.
![Type Hard Disk] (album/virtualbox/virtualboxstorage.png)

Yang 8.00 GB itu adalah batas dari peyimpanan TeaLinuxOS ubahlah dengan jumlah penyimpanan yang anda inginkan, setelah itu tekan tombol yang berada di samping tulisan TeaLinuxOS, hal tersebut dimaksudkan untuk lokasi dimana ingin anda simpan memori virtual nya lalu klik Create.
![Batas penyimpanan] (album/virtualbox/virtualboxfilelocation.png)

Sebagai contoh disini saya membuat penyimpanannya sebesar 50.00GB dan saya simpan memori virtual tersebut di Disk E:.
![Batas penyimpanan] (album/virtualbox/virtualboxfilelocationsize.png)

Setelah selesai membuat memori virtualnya tampilan VirtualBoxnya akan seperti dibawah, anda hanya perlu mensetting VirtualBox agar dapat menjalankan TeaLinuxOS dengan cara klik setting.
![Selesai mensetting] (album/virtualbox/virtualboxhome2.png)

Setelah anda klik setting tampilannya akan seperti dibawah klik menu System dan ubah urutan Hard Disk menjadi urutan pertama.
![setting system] (album/virtualbox/virtualboxsettingsystem.png)

Hasilnya akan seperti ini.
![setting system] (album/virtualbox/virtualboxsettingsystem2.png)

Setelah selesai mensetting System sekarang anda klik Storage dan klik tulisan Empty akan muncul tampilan seperti dibawah, anda lihat tulisan IDE Secondary Master disampingnya ada sebuah CD klik tombol tersebut.
![setting storage] (album/virtualbox/virtualboxsettingstorage.png)

Sekarang anda hanya perlu mencari dimana anda menyimpan .ISO TeaLinuxOS lalu klik Open.
![mencari file .iso] (album/virtualbox/virtualboxchosefile.png)

Setelah memasukan file .ISO tampilannya akan seperti dibawah, anda bisa ceklis Live CD/DVD ataupun tidak menceklisnya, disini saya tidak menceklis Live CD/DVD.
![tampilan menu storage setelah dimasukan file .iso] (album/virtualbox/virtualboxsettingstorage2.png)

Tampilan setelah selesai mensetting VirtualBox anda sekarang hanya perlu klik Start.
![siap memulai instalasi] (album/virtualbox/virtualboxhome3.png)

Setelah klik start dan menunggu beberapa saat, anda akan disuguhkan dengan tampilan Installer dari TeaLinuxOS disini anda dapat mengatur Bahasa dengan memilih Bahasa yang ada di bagian kiri anda, lalu klik Install TeaLinuxOS.
![Pilih bahasa] (album/virtualbox/homeinstallation.png)

Disini anda dapat menceklis Install Third Party Software ataupun tidak menceklisnya, sebagai contoh saya menceklis Install Third Party Software.  
![persiapan memulai instalasi] (album/virtualbox/preparingtoinstall.png)

Setelah klik Continue/selanjutnya anda akan menemui tampilan seperti di bawah, pada halaman ini anda bisa langsung Install Now ataupun memilih Something Else.

Untuk instalasi langsung dan tidak menggunakan VirtualBox dan ingin Dualboot sebaiknya anda memilih Something Else dan mengatur partisi tempat dimana anda ingin menginstall TeaLinuxOS,

Karena di contoh kali ini menggunakan VirtualBox anda dapat langsung klik Install Now.
![Partition] (album/virtualbox/partition.png)

Anda akan menemui PopUp seperti dibawah klik saja Continue/Selanjutnya.
![Partition] (album/virtualbox/partition2.png)

Setelah klik Continue anda akan menemui tampilan seperti dibawah untuk mengatur waktu agar sesuai dengan tempat anda berada. Ubah Jakarta Time dengan tempat anda berada jika tidak ada tetap Jakarta Time jangan diubah langsung klik Continue.
![Pilih lokasi] (album/virtualbox/choselocation.png)

Setelah klik Continue anda akan menemui tampilan seperti dibawah langsung saja klik Continue jangan ada yang diubah.
![Keyboard Layout] (album/virtualbox/keyboardlayout.png)

Setelah klik Continue anda akan menemui tampilan seperti dibawah isikan data yang dibutuhkan lalu klik continue.
![Data] (album/virtualbox/data.png)

Sebagai contoh pengisian data.
![contoh pengisian data] (album/virtualbox/exampledata.png)

Setelah pengisian data, anda akan menemui tampilan seperti dibawah yang artinya proses instalasi TeaLinuxOS sudah dimulai.
![proses instalasi] (album/virtualbox/prosesinstalasi.png)

Pada saat proses instalasi dimulai anda akan menemui tampilan seperti dibawah, disana terlihat tampilan Desktop dari TeaLinuxOS beserta dengan penjelasannya,
![Homescreen TeaLinuxOS] (album/virtualbox/hometea.png)

Setelah proses instalasi selesai anda akan menemui tampilan seperti dibawah ini, jika anda sudah terlanjur klik restart now.
![Instalasi selesai] (album/virtualbox/instalasiselesai.png)

Tutup virtualbox dan ceklis Power Off The machine dan klik Ok, lalu klik start.
![mematikan virtualbox] (album/virtualbox/virtualboxout.png)

Setelah anda klik start, anda akan mulai proses booting dan menemui tampilan seperti dibawah, sekarang anda hanya tinggal mengisikan password yang telah di setting tadi.
![Login page] (album/virtualbox/loginpage.png)

Setelah anda memasukan password, maka akan muncul Desktop dari TeaLinuxOS dan pada tahap ini anda telah selesai menginstall TeaLinuxOS di virtualbox.
![Home TeaLinuxOS] (album/virtualbox/homescreentea.png)
