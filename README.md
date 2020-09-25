# MyRecyclerView
RecyclerView adalah sebuah komponen tampilan (widget) yang lebih canggih ketimbang pendahulunya listview. Ia bersifat lebih fleksibel. RecyclerView memiliki kemampuan untuk menampilkan data secara efisien dalam jumlah yang besar. Terlebih jika Anda memiliki koleksi data dengan elemen yang mampu berubah-ubah sewaktu dijalankan (runtime).
# Koponen RecyclerView
1. RecyclerView dan LayoutManager: Komponen antarmuka yang bertugas untuk menampilkan data set yang dimiliki di dalamnya. Layoutmanager akan mengatur posisi tampilan data baik itu secara list (vertikal), grid (baris dan kolom) atau staggered grid (grid yang memiliki susunan tak seragam / tak beraturan).
 2. Adapter: Komponen yang akan mengatur bagaimana menampilkan data set ke dalam RecyclerView. Di sinilah terjadi proses pengisian tampilan (ViewInflate) dari file layout xml untuk tiap elemen dari data yang sebelumnya terpasang (bind) ke dalam RecyclerView.
 3. Dataset: Kumpulan data yang dimiliki dan ingin ditampilkan. Bisa berupa array, list maupun obyek map.
 4. Item Animator: Ini yang spesial. Kita bisa pasang animasi untuk tiap item di dalamnya. Contoh animasi yang umum seperti penambahan (add) dan penghapusan (removal) item. Kita akan mempelajari hal ini pada materi terpisah.
 # Langkah Langkah Mengimplementasikan RecyclerView
 1. Tambahkan dependencies komponen recyclerview pada file build.gradle level modul.
 2. Tambahkan obyek RecyclerView di berkas layout xml dari activity / fragment.
 3. Definisikan model kelas (POJO) yang akan digunakan sebagai data source.
 4. Buat berkas layout xml untuk baris item di RecyclerView.
 5. Buat sebuah kelas adapter yang inherit ke RecyclerView.Adapter dan ViewHolder untuk menampilkan tiap elemen data.
 6. Definisikan obyek RecyclerView berikut dengan bentuk yang diinginkan (bisa dalam bentuk list, grid, atau staggered) dan selanjutnya pasang obyek adapter (binding) agar bisa menampilkan koleksi data ke dalam RecyclerView.
 # Tampilan List Mode
 List adalah komponen yang menampilkan kumpulan item dalam bentuk daftar, sedangkan list item adalah komponen yang merepresentasikan tiap-tiap item di dalam suatu daftar. Mode list ini berisi gambar yang menggunakan circle image view dengan menggunakan implementasi (implementation 'de.hdodenhof:circleimageview:3.0.0') pada dependecies di build.grade(Module:app) dan text.

![WhatsApp Image 2020-09-25 at 16 36 39](https://user-images.githubusercontent.com/60589822/94253856-1dc2e580-ff50-11ea-80a0-009488b70448.jpeg)

# Tampilan Grid Mode
Tampilan grid mode menampilkan menu dalam bentuk foto/grid.

![WhatsApp Image 2020-09-20 at 08 11 00](https://user-images.githubusercontent.com/60589822/93692100-02ec0d80-fb19-11ea-9f8d-1523748a2bbe.jpeg)

# Tampilan Menu
