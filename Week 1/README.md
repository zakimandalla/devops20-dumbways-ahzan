# Week 1
Task for week 1 stage 1 

## Task for day 2
### 1. Perbedaan antara IP Private & Public, serta IP Dynamic & Static!
Jawaban

### 2. Buat penjelasan singkat tentang Virtualization!
Jawaban

### 3. Buat rancangan sebuah jaringan dengan spesifikasi sebagai berikut!
      - CIDR Block : 192.168.1.xxx/24
      - Subnet : 255.255.255.0
      - Gateway : 192.168.1.1
#### (Gunakan app.diagrams.net untuk membuat diagramnya)
Jawaban

### 4. Step-by-Step Menginstall Virtual Machine Ubuntu 20.04 via VirtualBox di Windows 10
Langkah 1: Unduh dan Install VirtualBox di https://www.virtualbox.org/wiki/Downloads

Langkah 2: Unduh File ISO Ubuntu Server 20.04 di https://ubuntu.com/download/server

Langkah 3: Buka VirtualBox, kemudian klik New
![alt text](https://github.com/zakimandalla/devops20-dumbways-ahzan/blob/main/Week%201/D-2/1.PNG?raw=true)

Langkah 4: Masukkan Nama dan file ISO yangsudah diunduh, kemudian klik Next
![alt text](https://github.com/zakimandalla/devops20-dumbways-ahzan/blob/main/Week%201/D-2/2.png?raw=true)

Langkah 5: Setup Username dan Password, lalu klik Next
![alt text](https://github.com/zakimandalla/devops20-dumbways-ahzan/blob/main/Week%201/D-2/3.PNG?raw=true)

Langkah 6: Atur jumlah RAM dan Processor yang ingin dipakai, lalu klik Next
![alt text](https://github.com/zakimandalla/devops20-dumbways-ahzan/blob/main/Week%201/D-2/4.PNG?raw=true)

Langkah 7: Atur jumlah memori yang ingin dipakai, lalu klik Next dan klik Finish
![alt text](https://github.com/zakimandalla/devops20-dumbways-ahzan/blob/main/Week%201/D-2/5.PNG?raw=true)

Langkah 8: Tunggu sampai muncul jendela dibawah, lalu pilih bahasa
![alt text](https://github.com/zakimandalla/devops20-dumbways-ahzan/blob/main/Week%201/D-2/9.PNG?raw=true)

Langkah 9: Jika tidak ingin mengupdate ke versi terbaru, bisa pilih Continue without Updating
![alt text](https://github.com/zakimandalla/devops20-dumbways-ahzan/blob/main/Week%201/D-2/10.PNG?raw=true)

Langkah 10: Jika layout keyboard normal, bisa pilih Done
![alt text](https://github.com/zakimandalla/devops20-dumbways-ahzan/blob/main/Week%201/D-2/11.PNG?raw=true)

Langkah 11: Pilih ethernet yang digunakan -> Edit IPv4
![alt text](https://github.com/zakimandalla/devops20-dumbways-ahzan/blob/main/Week%201/D-2/12.PNG?raw=true)

Langkah 12: Atur IPv4 Method ke Manual, lalu isi sesuai IP masing-masing (cek di terminal) lalu Save dan pilih Done
![alt text](https://github.com/zakimandalla/devops20-dumbways-ahzan/blob/main/Week%201/D-2/13.png?raw=true)

Langkah 13: Pada jendela Configure proxy dan Configure Ubuntu archive mirror, pilih Done

Langkah 14: Selanjutnya silang pada Custom storage layout, lalu pilih Done
![alt text](https://github.com/zakimandalla/devops20-dumbways-ahzan/blob/main/Week%201/D-2/16.PNG?raw=true)

Langkah 15: Pilih free space -> Add GPT Partition
![alt text](https://github.com/zakimandalla/devops20-dumbways-ahzan/blob/main/Week%201/D-2/17.PNG?raw=true)
    
Yang pertama, Isi +-80% free space sebagai penyimpanan utama dengan Format:[ext4], Mount:[/], lalu pilih Create
![alt text](https://github.com/zakimandalla/devops20-dumbways-ahzan/blob/main/Week%201/D-2/18.PNG?raw=true)
    
Yang kedua, Isi sisa free space sebagai penyimpanan cadangan dengan Format:[swap], lalu pilih Create
![alt text](https://github.com/zakimandalla/devops20-dumbways-ahzan/blob/main/Week%201/D-2/19.PNG?raw=true)

Langkah 16: pilih Done, lalu pilih Continue
![alt text](https://github.com/zakimandalla/devops20-dumbways-ahzan/blob/main/Week%201/D-2/21.PNG?raw=true)

Langkah 17: Isi profile setup, lalu pilih Done
![alt text](https://github.com/zakimandalla/devops20-dumbways-ahzan/blob/main/Week%201/D-2/22.PNG?raw=true)

Langkah 18: Silang pada Install SSH Server, lalu pilih Done
![alt text](https://github.com/zakimandalla/devops20-dumbways-ahzan/blob/main/Week%201/D-2/23.PNG?raw=true)

Langkah 19: lalu pilih Continue pada jendela Third-Party drivers dan Done pada jendela Featured server snaps.

Langkah 20: Tunggu proses instalasi selesai, lalu pilih Rebot Now
![alt text](https://github.com/zakimandalla/devops20-dumbways-ahzan/blob/main/Week%201/D-2/26.PNG?raw=true)

Langkah 21: Buka kembali VirtualBox, pada VM yang telah dibuat pilih setting
![alt text](https://github.com/zakimandalla/devops20-dumbways-ahzan/blob/main/Week%201/D-2/8.PNG?raw=true)

Langkah 22: Pilih Network, Ubah Attached to: ke Bridged Adapter, lalu klik OK
![alt text](https://github.com/zakimandalla/devops20-dumbways-ahzan/blob/main/Week%201/D-2/7.PNG?raw=true)

Sekarang VM telah siap digunakan
