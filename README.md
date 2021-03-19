# Plugin ButterKnife dan Parcelable
ButterKnife adalah library Android yang dikembangkan oleh Jake Wharton. Library ini sangat membantu meringankan tugas developer android karena mampu menyederhanakan penulisan komponen view di Android, atau istilah singkatnya kita bisa menghilangkan ‘findViewById’.

Parcelable adalah suatu interface pada pemrograman Android, yang memungkinkan suatu instansi dari kelas/objek untuk bisa disimpan dan diambil kembali dari sebuah Parcel. Sedangkan Parcel sendiri merupakan suatu kontainer untuk menampung kelas tersebut.

# Intent Result
Intent merupakan suatu objek yang terdapat dalam suatu activity dimana objek tersebut dapat komunikasi dengan activity yang lain, baik activity pada fungsi internal android misal seperti memanggil activity dalam satu package atau beda package yang masih berada dalam satu project.

Ada tiga penggunaan umum intent :

- [x] Memindahkan satu activity ke activity lain dengan atau tidak membawa data.
- [x] Menjalankan background service, misalnya melakukan sinkronisasi ke server dan menjalankan proses berulang (periodic/scheduler task).
- [x] Mengirimkan obyek broadcast ke aplikasi yang membutuhkan. Misal, ketika aplikasi membutuhkan proses menjalankan sebuah background service setiap kali aplikasi selesai melakukan booting. Aplikasi harus bisa menerima obyek broadcast yang dikirimkan oleh sistem Android untuk event booting tersebut.

Pada Intent Result ini dapat mengirim data ke activity lainnya (pindah halaman dengan membawa data) . Ada 2 cara untuk mengirimkan data/nilai antar activity didalam aplikasi Android, yaitu dengan menggunakan Intent dan Bundle, keduanya mempunyai fungsi yang sama, yaitu untuk passing data, tetapi dengan menggunakan Bundle, akan terlihat lebih rapi, karena dikemas terlebuh dahulu didalam bundle sebelum dikirimkan.

# Contoh Penerapan Intent
Tampilan teks yang ingin dimasukkan, yang nantinya akan dikirim dan ditampilkan di activity lainnya. Button "save name" untuk menyimpan data teks yang akan dikirimkan pada halaman activity kedua.

