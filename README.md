# Aplikasi-Pengelolaan-Data-Menggunakan-DOM-dan-Web-Storage
Submission kelsa dicoding font-end developer.
![asa](https://github.com/sourchib/Aplikasi-Pengelolaan-Data-Menggunakan-DOM-dan-Web-Storage/assets/60887634/f9c9f021-e1ab-4a8e-a32b-461f48fb10bd)
## Kriteria Bookshelf Apps
Buatlah aplikasi web yang dapat memasukan data buku ke dalam rak, memindahkan data buku antar rak, dan menghapus data buku dari rak. 
Untuk lebih jelasnya, terdapat 5 kriteria utama pada Bookshelf Apps yang harus Anda buat.
Kriteria 1: Mampu Menambahkan Data Buku
Bookshelf Apps harus mampu menambahkan data buku baru.
Data buku yang disimpan merupakan objek JavaScript dengan struktur berikut:
{
  id: string | number,
  title: string,
  author: string,
  year: number,
  isComplete: boolean,
}
Berikut contoh data riilnya:

{
  id: 3657848524,
  title: 'Harry Potter and the Philosopher\'s Stone',
  author: 'J.K Rowling',
  year: 1997,
  isComplete: false,
}
Catatan:
Untuk id buku pada tiap buku yang disimpan haruslah unik. Tips dalam menetapkan nilai untuk adalah Anda bisa memanfaatkan nilai timestamp. Untuk mendapatkan nilai timestamp di JavaScript cukup mudah, cukup dengan menuliskan expressions +new Date().

Kriteria 2: Memiliki Dua Rak Buku
Bookshelf Apps harus memiliki 2 Rak buku. Yakni, “Belum selesai dibaca” dan “Selesai dibaca”.
Rak buku "Belum selesai dibaca" hanya menyimpan buku jika properti isComplete bernilai false.
Rak buku "Selesai dibaca" hanya menyimpan buku jika properti isComplete bernilai true.

Kriteria 3: Dapat Memindahkan Buku antar Rak
Buku yang ditampilkan pada rak, baik itu "Belum selesai dibaca" maupun "Selesai dibaca" harus dapat dipindahkan di antara keduanya.

Kriteria 4: Dapat Menghapus Data Buku
Buku yang ditampilkan pada rak, baik itu "Belum selesai dibaca" maupun "Selesai dibaca" harus dapat dihapus.

Kriteria 5: Manfaatkan localStorage dalam Menyimpan Data Buku
Data buku yang ditampilkan pada rak, baik itu "Belum selesai dibaca" maupun "Selesai dibaca" harus dapat bertahan walaupun halaman web ditutup.
Dengan begitu, Anda harus menyimpan data buku pada localStorage.

Thanks !!!
