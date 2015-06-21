# Instalasi IGN Arm

## apa itu IGN ARM ?
lihat [IGNwiki](http://igos-nusantara.or.id/wiki/index.php?title=Halaman_Utama#IGOS_Nusantara_ARM)

> **IGN ARM** adalah distro **IGOS** linux yang dikembangkan khusus untuk komputer dengan arsitektur ARM.

## Cara Instalasi
1. unduh [image] (http://repo.informatika.lipi.go.id/arm/image/)   
2. kemudian extract file yang telah di unduh dengan cara ketik di terminal 
~~~bash
$ sudo tar xvfJ filename.tar.xz
~~~
3. siapkan micro sdcard dengan kapasitas minimal **8 GB**
4. masukan micro sdcard kedalam extention sdcard dan pasang di pc / laptop
5. deteksi device melalui terminal dengan perintah **dmesg** misalkan 
**/dev/mmclbk0**
6. apabila sudah dipastikan device berada ketik diterminal
~~~bash
$ sudo dd bs=4MB if=folder/image/ignarm/berada of=/dev/microsd/berada
~~~
7. Proses selesai masukan sdcard yang sudah terinstalasi ign arm kedalam komputer berbasis ARM
8. **Boot**