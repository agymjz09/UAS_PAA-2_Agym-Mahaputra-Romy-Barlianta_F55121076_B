Analisis Algoritma:

Worst case:
Untuk algoritma TSP, waktu eksekusi terburuk terjadi ketika jumlah node pada graph sangat besar. Dalam kasus ini, jumlah permutasi jalur yang dihasilkan juga sangat besar, sehingga waktu eksekusi akan meningkat secara eksponensial.
Untuk algoritma Dijkstra, waktu eksekusi terburuk terjadi ketika terdapat banyak node dan edge pada graph. Algoritma Dijkstra mengunjungi setiap node dan memperbarui jarak minimum ke node-nodes tetangga, sehingga jumlah operasi yang dilakukan meningkat seiring dengan jumlah node dan edge pada graph.

Best case:
Untuk algoritma TSP, kasus terbaik terjadi ketika jumlah node pada graph sangat sedikit, sehingga jumlah permutasi jalur yang dihasilkan juga sedikit. Waktu eksekusi akan lebih singkat dalam kasus ini.
Untuk algoritma Dijkstra, kasus terbaik terjadi ketika hanya ada satu node pada graph, sehingga tidak ada operasi yang perlu dilakukan. Jarak minimum ke node tersebut adalah 0.

Average case:
Untuk algoritma TSP, kasus rata-rata terjadi ketika jumlah node pada graph sedang. Waktu eksekusi akan meningkat secara eksponensial dengan peningkatan jumlah node.
Untuk algoritma Dijkstra, kasus rata-rata terjadi ketika terdapat beberapa node dan edge pada graph. Waktu eksekusi akan meningkat dengan peningkatan jumlah node dan edge, tetapi tidak secepat algoritma TSP.