# MyRecyclerView
RecyclerView adalah sebuah komponen tampilan (widget) yang lebih canggih ketimbang pendahulunya listview. Ia bersifat lebih fleksibel. RecyclerView memiliki kemampuan untuk menampilkan data secara efisien dalam jumlah yang besar. Terlebih jika Anda memiliki koleksi data dengan elemen yang mampu berubah-ubah sewaktu dijalankan (runtime).
# Koponen RecyclerView
1. RecyclerView dan LayoutManager: Komponen antarmuka yang bertugas untuk menampilkan data set yang dimiliki di dalamnya. Layoutmanager akan mengatur posisi tampilan data baik itu secara list (vertikal), grid (baris dan kolom) atau staggered grid (grid yang memiliki susunan tak seragam / tak beraturan).
 2. Adapter: Komponen yang akan mengatur bagaimana menampilkan data set ke dalam RecyclerView. Di sinilah terjadi proses pengisian tampilan (ViewInflate) dari file layout xml untuk tiap elemen dari data yang sebelumnya terpasang (bind) ke dalam RecyclerView.
 3. Dataset: Kumpulan data yang dimiliki dan ingin ditampilkan. Bisa berupa array, list maupun obyek map.
 4. Item Animator: Ini yang spesial. Kita bisa pasang animasi untuk tiap item di dalamnya. Contoh animasi yang umum seperti penambahan (add) dan penghapusan (removal) item. Kita akan mempelajari hal ini pada materi terpisah.
 # Tampilan List Mode
 List adalah komponen yang menampilkan kumpulan item dalam bentuk daftar, sedangkan list item adalah komponen yang merepresentasikan tiap-tiap item di dalam suatu daftar.
 
![WhatsApp Image 2020-09-20 at 08 10 59](https://user-images.githubusercontent.com/60589822/93692099-fff11d00-fb18-11ea-8ff5-bd7e0168a6d2.jpeg)

# Tampilan Grid Mode
Tampilan grid mode menampilkan menu dalam bentuk foto/grid.

![WhatsApp Image 2020-09-20 at 08 11 00](https://user-images.githubusercontent.com/60589822/93692100-02ec0d80-fb19-11ea-9f8d-1523748a2bbe.jpeg)

# Tampilan Menu

![WhatsApp Image 2020-09-20 at 08 10 59 (1)](https://user-images.githubusercontent.com/60589822/93692101-041d3a80-fb19-11ea-959f-24261126a9f6.jpeg)
