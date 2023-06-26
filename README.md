# UAS_PAA-2_Agym-Mahaputra-Romy-Barlianta_F55121076_B
<h3>Nama : Agym Mahaputra Romy Barlianta</h3>
<h3>NIM : F55121076</h3>
<h3>Kelas : B</h3><br>

<h5>Analisis Algoritma TSP dan algoritma Dijkstra:</h5>

Worst case: <br>
Untuk algoritma TSP, waktu eksekusi terburuk terjadi ketika jumlah node pada graph sangat besar. Dalam kasus ini, jumlah permutasi jalur yang dihasilkan juga sangat besar, sehingga waktu eksekusi akan meningkat secara eksponensial.<br>
Untuk algoritma Dijkstra, waktu eksekusi terburuk terjadi ketika terdapat banyak node dan edge pada graph. Algoritma Dijkstra mengunjungi setiap node dan memperbarui jarak minimum ke node-nodes tetangga, sehingga jumlah operasi yang dilakukan meningkat seiring dengan jumlah node dan edge pada graph.

Best case:<br>
Untuk algoritma TSP, kasus terbaik terjadi ketika jumlah node pada graph sangat sedikit, sehingga jumlah permutasi jalur yang dihasilkan juga sedikit. Waktu eksekusi akan lebih singkat dalam kasus ini.<br>
Untuk algoritma Dijkstra, kasus terbaik terjadi ketika hanya ada satu node pada graph, sehingga tidak ada operasi yang perlu dilakukan. Jarak minimum ke node tersebut adalah 0.

Average case:<br>
Untuk algoritma TSP, kasus rata-rata terjadi ketika jumlah node pada graph sedang. Waktu eksekusi akan meningkat secara eksponensial dengan peningkatan jumlah node.<br>
Untuk algoritma Dijkstra, kasus rata-rata terjadi ketika terdapat beberapa node dan edge pada graph. Waktu eksekusi akan meningkat dengan peningkatan jumlah node dan edge, tetapi tidak secepat algoritma TSP.

<h5>Analisis Algoritma Bubble Sort dan Algoritma Insertion Sort:</h5>

Worst Case:<br>
Bubble Sort: O(n^2)<br>
Pada kasus terburuk, jika elemen dalam daftar sudah terurut secara terbalik, maka setiap elemen akan bergeser hingga ke posisi yang benar pada setiap iterasi.<br>
Insertion Sort: O(n^2)<br>
Pada kasus terburuk, jika elemen dalam daftar sudah terurut secara terbalik, maka setiap elemen akan memerlukan pergeseran ke posisi yang benar pada setiap iterasi.<br>

Best Case:<br>
Bubble Sort: O(n)<br>
Pada kasus terbaik, jika daftar sudah terurut, algoritma bubble sort hanya memerlukan satu iterasi untuk memeriksa bahwa daftar sudah terurut dengan benar.<br>
Insertion Sort: O(n)<br>
Pada kasus terbaik, jika daftar sudah terurut, algoritma insertion sort hanya memerlukan satu iterasi untuk memeriksa bahwa daftar sudah terurut dengan benar.<br>

Average Case:<br>
Bubble Sort: O(n^2)<br>
Pada kasus rata-rata, algoritma bubble sort akan memerlukan banyak iterasi dan pertukaran elemen untuk mengurutkan daftar.<br>
Insertion Sort: O(n^2)<br>
Pada kasus rata-rata, algoritma insertion sort akan memerlukan banyak iterasi dan pergeseran elemen untuk mengurutkan daftar.
