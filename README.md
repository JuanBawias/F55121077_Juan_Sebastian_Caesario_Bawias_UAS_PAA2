# F55121077_Juan_Sebastian_Caesario_Bawias_UAS_PAA2

# ANALISIS ALGORITMA

# Bubble sort & Insertion sort
a. worst case
   Kasus terburuk terjadi ketika elemen-elemen dalam list tidak terurut secara teratur dan perlu dilakukan banyak pertukaran atau 
   pergeseran.   Untuk Bubble Sort, kompleksitas waktu terburuk adalah O(n^2), di mana n adalah jumlah elemen dalam list. Sedangkan untuk 
   Insertion Sort, kompleksitas waktu terburuk juga O(n^2).
  
b. Best Case 
   Kasus terbaik terjadi ketika elemen-elemen dalam list sudah terurut secara teratur. Pada kasus ini, Bubble Sort dapat memiliki              kompleksitas waktu terbaik O(n), karena hanya memerlukan satu iterasi untuk memeriksa bahwa tidak ada pertukaran yang dilakukan. 
   Sedangkan   Insertion Sort memiliki kompleksitas waktu terbaik O(n), karena hanya perlu memeriksa satu elemen sebelumnya untuk 
   memposisikan elemen yang sedang diperiksa. 

c. Average Case 
   Rata-rata kasus terjadi ketika elemen-elemen dalam list diacak secara acak. Baik Bubble Sort maupun Insertion Sort memiliki kompleksitas 
   waktu rata-rata O(n^2).
   

# TSP & Djikstra
a. worst case
   Pada kasus terburuk, algoritma TSP dan algoritma Dijkstra perlu menjelajahi semua kemungkinan jalur atau sisi pada grafik untuk 
   menemukan jalur terpendek. Untuk TSP, ini melibatkan menghasilkan semua permutasi kemungkinan dari simpul-simpul, menghasilkan (n-1)! 
   permutasi yang harus diiterasi. Untuk algoritma Dijkstra, perlu mengunjungi semua simpul dalam grafik. Oleh karena itu, kompleksitas 
   waktu kasus terburuk untuk kedua algoritma dapat dianggap sebagai O(n!), di mana n adalah jumlah simpul dalam grafik. Hal ini 
   dikarenakan dalam kasus terburuk, algoritma-algoritma tersebut perlu menjelajahi semua permutasi kemungkinan atau mengunjungi semua 
   simpul.
  
b. Best Case 
   Skenario terbaik untuk kedua algoritma terjadi ketika simpul awal terhubung langsung dengan simpul tujuan dengan satu sisi, atau 
   ketika grafik sangat kecil hanya dengan sedikit simpul. Pada algoritma TSP, kasus terbaik terjadi ketika simpul awal terhubung 
   langsung dengan semua simpul lainnya, menghasilkan siklus sederhana. Kompleksitas waktu dalam kasus ini adalah O(n), karena tidak 
   perlu menghasilkan permutasi. Pada algoritma Dijkstra, kasus terbaik terjadi ketika simpul awal terhubung langsung dengan simpul 
   tujuan tanpa ada simpul perantara. Kompleksitas waktu dalam kasus ini adalah O(1), karena tidak perlu menjelajahi simpul atau sisi 
   tambahan.

c. Average Case 
   Kompleksitas waktu kasus rata-rata untuk kedua algoritma tergantung pada struktur dan konektivitas grafik. Untuk algoritma TSP, 
   kompleksitas waktu kasus rata-rata umumnya dianggap sebagai O(n!), karena perlu menjelajahi jumlah permutasi yang besar. Namun, 
   heuristik atau optimisasi dapat diterapkan untuk mengurangi ruang pencarian dan meningkatkan kinerja kasus rata-rata, seperti 
   pemrograman dinamis atau teknik branch and bound. Untuk algoritma Dijkstra, kompleksitas waktu kasus rata-rata dapat diperkirakan 
   sebagai O((V + E) log V), di mana V adalah jumlah simpul (vertices) dan E adalah jumlah sisi (edges) dalam grafik. Hal ini dikarenakan 
   algoritma ini melibatkan mengunjungi setiap simpul sekali dan memperbarui jarak pada sisi yang terhubung dengan setiap simpul, yang 
   dapat dilakukan secara efisien menggunakan antrian prioritas (misalnya, min-heap). Perlu diperhatikan bahwa kompleksitas waktu kasus 
   rata-rata sebenarnya dapat bervariasi tergantung pada grafik spesifik dan propertinya, seperti kepadatan sisi, distribusi bobot sisi, 
   dan pola konektivitas. Secara keseluruhan, algoritma TSP memiliki kompleksitas waktu yang lebih tinggi dibandingkan dengan algoritma 
   Dijkstra, menjadikannya lebih mahal secara komputasi, terutama dalam skenario kasus terburuk. 
