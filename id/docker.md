# Tentang Buku Ini

Buku ini berfokus pada dasar-dasar penggunaan Docker dan penggunaannya dalam keseharian anda sebagai *developer* maupun *sysadmin*.


## Lisensi

Anda dapat melihat **lisensi secara lengkap di**:

<http://creativecommons.org/licenses/by-nc/3.0/legalcode>

## Tentang Penulis

Gilang Chandrasa adalah seorang Python/Django programmer yang juga menekuni dunia DevOps.


## Versi Terbaru

Versi terbaru dari sumber buku ini terdapat di:
<http://github.com/gchandrasa/buku-mini-tentang-docker>

# Pengenalan Docker

## Apa itu Docker?

Docker adalah sebuah *platform* terbuka untuk mendistribusikan aplikasi bagi *developer* dan juga *sysadmin*.

Docker mempunyai *tagline* "Build, Ship and Run Any App, Anywhere" yang kira-kira artinya kita bisa membuat, mendistribusikan dan menjalankan aplikasi dimanapun juga.

## Apa manfaat menggunakan Docker?

* Pendistribusian aplikasi yang lebih cepat
* Pendistribusian dan skalabilitas aplikasi menjadi lebih mudah

## Instalasi

Untuk instalasi bisa dilihat dari situs Docker sendiri, berikut proses instalasi beberapa sistem operasi:

* Ubuntu <https://docs.docker.com/installation/ubuntulinux/>
* Mac OS X <https://docs.docker.com/installation/mac/>
* Windows <https://docs.docker.com/installation/windows/>

# Dasar-dasar Docker

## Istilah-istilah yang digunakan dalam docker

## Perintah-perintah docker

### Melihat daftar kontainer

    $ sudo docker ps

### Menghapus kontainer yang ada

    $ sudo rm <container_id>

### Melihat daftar image 

    $ sudo docker images

### Menghapus image dalam docker

    $ sudo rmi <image_id>

### Mengunduh images dari Docker hub

    $ sudo docker pull <nama_image>

# Dockerfile

Dockerfile adalah sebuah text file yang berisikan instruksi untuk membuat sebuah docker image.



# Tips and Trik 

### Menghentikan semua containers
	
	docker stop $(docker ps -a -q)

### Menghentikan semua containers

	docker rm $(docker ps -a -q)