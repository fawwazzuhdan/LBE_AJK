# Git

## Penjelasan
Git adalah sebuah perangkat lunak (*software*) yang digunakan untuk mengontrol versi ataupun proyek manajemen kode perangkat lunak yang diciptakan oleh Linus Torvalds. Pada awalnya memang ditujukan untuk pengembangan sebuah kernel linux. Desain GIT juga terinspirasi oleh BitKeeper dan Monotone. Git merupakan sebuah version control system yang dipakai oleh para developer agar bisa mengembangkan sebuah software secara bersamaan. Fungsi utama dari git adalah untuk mengatur versi dari sebuah source code program dengan cara memberikan tanda baris dan code yang akan ditambah atau diganti.

Setelah mengetahui apa itu GIT, selanjutnya anda juga harus mengetahui apa saja fitur fitur yang ada didalam GIT berikut ini :

1. **Version control system yang terdistribusi**, GIT menggunakan pendekatan peer to peer, tidak seperti yang lainnya seperti Subversion (SVN) yang menggunakan model client-server.
2. **GIT memungkinkan developer untuk memiliki branch kode** yang independent dan massive. Membuat, menghapus dan menggabungkan branch tersebut menjadi lebih cepat, lancar dan tidak butuh waktu yang lama.
3. **GIT bersifat atomic**, adalah sebuah tindakan akan benar-benar diselesaikan dengan lengkap atau sama sekali gagal. Ini sangat penting, karena di beberapa version control system seperti CVS, operasinya bersifat non-atomic. Jika ada operasi yang ‘gantung’ dan terkait dengan repository, kondisi repository menjadi tidak stabil.
4. **Media penyimpanan GIT yaitu dalam folder .git**. Berbeda dengan VCS lain seperti SVN atau CVS, dimana metadata file disimpan dalam folder tersembunyi seperti .cvs, .svn, .etc.
5. **GIT memiliki data model** yang dapat membantu memastikan integritas cryptographic yang ada dalam repository. Sehingga setiap kali sebuah file ditambahkan atau di-commit, checksum-nya akan diciptakan; sama hal nya, juga di-retrieve lewat checksum-nya juga.
6. **GIT memiliki staging area atau index**. Dengan stagin area, developer bisa memformat commit dan membuatnya bisa di-review sebelum benar-benar diterapkan.
7. **GIT sangat sederhana dalam penggunannya**. Untuk memulai, Anda bisa membuat repository atau men-checkout yang sudah ada. Setelah instalasi, perintah git-init akan men-setup semuanya.

Contoh dari *software version control system* adalah github, gitlab, bitbucket, dan masih banyak lagi. Jika anda sebagai developer belum mengetahui fitur git ini, maka anda wajib mencoba dan memakainya. Karena banyak manfaat yang akan didapat dengan git ini.

## Keunggulan dari Git
- Design yang mudah dipahami
- Akan sangat memudahkan developer dalam berpartisipasi dalam sebuah pengembangan project yang dilakukan oleh banyak orang
- Akan dapat memudahkan dalam melakukan dokumentasi project, baik dari sisi source code ataupun perubahan fungsi
- Perubahan yang terjadi pada setiap file nantinya akan di commit sehingga dapat terlihat.
- Sistem terdistribusi, peer to peer
- Mendukung dalam proyek besar seperti Kernel Linux
- Akses hanya menggunakan command line tanpa memerlukan client server
- Penyimpanan murni berbasis file (tidak menggunakan database/SQL)
- Open Source alias Gratis

## Kelemahan Git
- Tidak Optimal untuk pengembang tunggal
- Dukungan untuk Windows terbatas dibandingkan Linux

## Manfaat Git
Berikut ini merupakan manfaat lain dari GIT yang bisa Anda rasakan ketika sudah menggunakan Git, diantaranya:
- Sangat mudah dalam penggunannya.
- Ada checkpoint sendiri ketika adanya perubahan yang terjadi pada sebuah kode.
- Dapat menyimpan seluruh versi source code.
- Bisa berkontribusi dalam berbagai proyek yang sifatnya open-source.
- Bisa memahami cara mendeploy sebuah aplikasi modern
- Bisa memahami cara untuk berkolaborasi sebuah atau beberapa proyek.

## Perintah-perintah dasar Git
Untuk mengetahui bagaimana menggunakan git, berikut perintah-perintah dasar git:

- **git init** : untuk membuat repository pada file lokal yang nantinya ada folder .git
- **git status** : untuk mengetahui status dari repository lokal
- **git add** : menambahkan file baru pada repository yang dipilih
- **git commit** : untuk menyimpan perubahan yang dilakukan, tetapi tidak ada perubahan pada remote repository.
- **git push** : untuk mengirimkan perubahan file setelah di commit ke remote repository.
- **git branch** : melihat seluruh branch yang ada pada repository
- **git checkout** : menukar branch yang aktif dengan branchyang dipilih
- **git merge** : untuk menggabungkan branch yang aktif dan branch yang dipilih
- **git clone** : membuat Salinan repository lokal

## Cara install Git
Cara untuk install git di Windows silahkan download file [disini](https://git-scm.com/download/win "Install Git di Windows") kemudian install. Sedangkan untuk Linux bisa dilihat [disini](https://git-scm.com/download/linux "Install Git di Linux").

## Referensi
- https://id.wikipedia.org/wiki/Git
- https://idcloudhost.com/mengenal-apa-itu-git-serta-manfaat-dan-fiturnya-untuk-developer/
- https://idcloudhost.com/pengertian-dan-manfaat-git-bagi-developer/
- https://git-scm.com/docs
- https://www.petanikode.com/tutorial/git/
