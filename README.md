# 1. VMWare - Install Ubuntu Server
**Cara install ubuntu server di vmware/virtualbox**
<br>
1. Buka virtualbox/vmware dan setting resource yang dibutuhkan mulai dari besaran ram dan kapasitas hardisk yang digunakan<br>
2. Setting Network ke Bridge dan masukkan cd untuk menginstall ubuntu server<br>

![Gambar virtualbox](images_ubuntu/gambar1.png)
<br>
![Gambar virtualbox](images_ubuntu/gambar2.png)
<br>
![Gambar virtualbox](images_ubuntu/gambar3.png)
<br>
![Gambar virtualbox](images_ubuntu/gambar4.png)
<br>
![Gambar virtualbox](images_ubuntu/gambar5.png)
<br>
![Gambar virtualbox](images_ubuntu/gambar6.png)
<br>
![Gambar virtualbox](images_ubuntu/gambar7.png)
<br>
![Gambar virtualbox](images_ubuntu/gambar7.1.png)
<br>
![Gambar virtualbox](images_ubuntu/gambar7.2.png)
<br>

3. Pilih language dan setup keyboard <br>

![Gambar virtualbox](images_ubuntu/gambar8.png)
<br>
![Gambar virtualbox](images_ubuntu/gambar9.png)
<br>

4. Setting IP address ke manual dan jadikan ip static dengan memilih IPv4 <br>

![Gambar virtualbox](images_ubuntu/gambar10.png)
<br>
![Gambar virtualbox](images_ubuntu/gambar11.png)
<br>
![Gambar virtualbox](images_ubuntu/gambar12.png)
<br>
![Gambar virtualbox](images_ubuntu/gambar13.png)
<br>
![Gambar virtualbox](images_ubuntu/gambar14.png)
<br>

5. Setting partisi yang akan digunakan, disini saya membagi 1GB untu swap dan alokasikan sisa memory untuk root <br>

![Gambar virtualbox](images_ubuntu/gambar15.png)
<br>

6. Setting nama, server name dan password yang akan digunakan pada saat pertama kali akses atau mencoba untuk login

![Gambar virtualbox](images_ubuntu/gambar16.png)
<br>
![Gambar virtualbox](images_ubuntu/gambar17.png)
<br>
![Gambar virtualbox](images_ubuntu/gambar18.png)
<br>
 
7. Tunggu Hingga Proses intallasi ubuntu server selesai dan reboot system agar bisa digunakan


![Gambar virtualbox](images_ubuntu/gambar19.png)
<br>
![Gambar virtualbox](images_ubuntu/gambar20.png)
<br><br><hr>

# 2. VMWare - Setup Network
**Cara Setup Network/IP Address ke static**
<br>

1. saya login dengan user ridwansaefudin dan membuat user baru dengan perintah adduser untuk user dengan nama ridwan dan juga setting password <br>

![Gambar Setup Network](images_setup_network/gambar1.png)
<br>

2. Saya telah berhasil membuat user baru dan login dengan nama user ridwan <br>

![Gambar Setup Network](images_setup_network/gambar2.png)
<br>

3. dengan perintah sudo nano /etc/sudoers atau perintah sudo -aG sudo ridwan, saya setting agar dapat mengakses hak istimewa root <br>

![Gambar Setup Network](images_setup_network/gambar3.png)
<br>

4. ifconfig untuk melihat alamat ip yang digunakan dan perintah sudo /etc/netplan untuk merubah alamat ip address<br>

![Gambar Setup Network](images_setup_network/gambar4.png)
<br>
![Gambar Setup Network](images_setup_network/gambar5.png)
<br>

5. Perintah netplan apply untuk dapat menggunakan ip address yang telah diubah dan reboot untuk dapat mengubah alamat ip yang sudah di setting sebelumnya

![Gambar Setup Network](images_setup_network/gambar6.png)
<br>
![Gambar Setup Network](images_setup_network/gambar7.png)
<br>
![Gambar Setup Network](images_setup_network/gambar8.png)
<br>

6. coba untuk mengetes alamat ip lokal ke ubuntu server, begitupun sebaliknya dengan perintah ping <br>

![Gambar Setup Network](images_setup_network/gambar9.png)
<br><hr>

# 3. VMWare - Install Application
**Cara mengsetup dan mendeploy aplikasi nodeJS ke server**
<br>
![Gambar Install Application](images_install_application/gambar1.png)
<br><br>
![Gambar Install Application](images_install_application/gambar2.png)
<br><br>
![Gambar Install Application](images_install_application/gambar3.png)
<br><br>
![Gambar Install Application](images_install_application/gambar4.png)
<br><br>
![Gambar Install Application](images_install_application/gambar5.png)
<br><br>
![Gambar Install Application](images_install_application/gambar6.png)
<br><br>
![Gambar Install Application](images_install_application/gambar7.png)
<br><br>
![Gambar Install Application](images_install_application/gambar8.png)
<br><br>
![Gambar Install Application](images_install_application/gambar9.png)
<br><br>
![Gambar Install Application](images_install_application/gambar10.png)
<br><br>
![Gambar Install Application](images_install_application/gambar11.png)
<br><br>
![Gambar Install Application](images_install_application/gambar12.png)
<br><br>
![Gambar Install Application](images_install_application/gambar13.png)
<br><br>
![Gambar Install Application](images_install_application/gambar14.png)
<br><br>
![Gambar Install Application](images_install_application/gambar15.png)
<br><br><hr>

# 4. AWS - Create and Setup Server
<br>

![Gambar Setup Server AWS](images_setup_server_aws/gambar1.png)
<br><br>
![Gambar Setup Server AWS](images_setup_server_aws/gambar2.png)
<br><br>
![Gambar Setup Server AWS](images_setup_server_aws/gambar3.png)
<br><br>
![Gambar Setup Server AWS](images_setup_server_aws/gambar4.png)
<br><br>
![Gambar Setup Server AWS](images_setup_server_aws/gambar5.png)
<br><br>
![Gambar Setup Server AWS](images_setup_server_aws/gambar6.png)
<br><br>
![Gambar Setup Server AWS](images_setup_server_aws/gambar7.png)
<br><br>
![Gambar Setup Server AWS](images_setup_server_aws/gambar8.png)
<br><br>
![Gambar Setup Server AWS](images_setup_server_aws/gambar9.png)
<br><br><hr>

# 5. AWS - Server for Application
<br>

**Saya sudah buat tapi belum dirapihkan folder foto(Saya harap dan tolong untuk beri saya kesempatan memperbaiki)**
