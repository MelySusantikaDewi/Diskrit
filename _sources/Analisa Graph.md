---
title: Pengertian Social Network Anal

---

#### Pengertian Social Network Analysis
Social Network Analysis merupakan bidang kajian yang mengekplorasitentang hubungan manusia dengan menggunakan teori graf. Implementasi Social Network Analysis dapat menjelaskan relasi atau hubungan antar aktor melalui visualisasi berbentuk graf.Social network terdapat node yang mewakili orang atau individu atau aktor.Relasi  antar objek  dapat dinyatakan dengan link atau edges yang terjadi antara aktor tersebut Social network terdiri dari banyak aktor yang mempunyai relasi satu sama lain hingga membentuk peta jaringan sosial yang dinyatakan dengan graph.

#### Peta Jaringan Dan Adjacency Matrix
![Screenshot 2024-11-17 204215](https://hackmd.io/_uploads/SJ1V7dDzkx.png)
![Screenshot 2024-11-17 204237](https://hackmd.io/_uploads/Sk9VXODG1l.png)

Centrality adalah penentuan aktor menggunakan ukuran pada Social Network Centrality dalam teori graf dan social network .Dibagi menjadi empat jenis, 
* degree centrality, 
* betweeness centrality, 
* closeness centrality 
* eigenvector centrality

#### Pengertian Degree Centrality
Degree centrality adalah jumlah edge yang terkoneksi pada suatu node yang mewakili interaksi.
* Pentingnya node ditentukan oleh jumlah node yang berdekatan dengan node tersebut
* Lebih besar derajatnya (degree), maka lebih penting node itu dalam suatu jaringan 
* Hanya sebagian kecil node yang memiliki derajat tinggi dalam jaringan 

#### Rumus Degree Centrality
![Screenshot 2024-11-17 205006](https://hackmd.io/_uploads/B1eiEuwG1x.png)

#### Pengertian Closeness Centrality
Closenes centrality adalah nilai kedekatan antara satu node dengan node lain dalam jaringan dengan menghitung rata-rata dari jarak relasi node-node tersebut. Skor closeness centrality mewakili kecepatan dalam penyebaran informasi.

#### Rumus Closeness Centrality
![Screenshot 2024-11-17 205303](https://hackmd.io/_uploads/HJEIB_wf1l.png)

#### Pengertian Betweenness Centrality
Skor betweeness Centrality mewakili seberapa besar informasi yang tersebar dari suatu aktor.Semakin banyak lintasan yang harus melewati persimpangan itu,seberapa besar suatu node diperlukan sebagai penghubung dalam penyebaran informasi di dalam jaringan.

#### Cara Pengerjaan Betweenness Centrality
* Menghitung jumlah lintasan terpendek yang melewati suatu node
* Node dengan  betweenness  tinggi  adalah  penting dalam komunikasi dan penyebaran informasi
* Betweenness Centrality![Screenshot 2024-11-17 205835](https://hackmd.io/_uploads/HyC5UuwMkl.png)
* Jumlah lintasan terpendek antara  s dan t
* Jumlah lintasan terpendek antara s dan t yang melewati vi

#### Tabel Betweenness Centrality
![Screenshot 2024-11-17 210051](https://hackmd.io/_uploads/HkFXw_Pf1e.png)

#### Normalisasi Betweenness Centrality
![Screenshot 2024-11-17 210150](https://hackmd.io/_uploads/SJJDPOvz1l.png)
