- Traditionally in computation and processing data we would bring the data to the computer.
-  You'd wanna program and you'd bring the data into the program

## BIG DATA CLUSTER
- Biig data cluster :
  1. took the data -->
  2. disdtributed and replicated each piece / triplicated each piece -->
  3. send the pieces of these files to thousands of computers first it was hundreds but then now it's thousands now it's tens of thousands -->
  4. would send the same program to all these computers in the cluster -->
  5. each computer would run the program on its little piece of the file and send the results back. -->
  6. The results would then be sorted & redistributed back to another process -->
  7. The first process is called a map or a mapper process and the second one was called a reduce process.
- you could do lots and lots of different kinds of handle lots and lots of different kinds of problems and very, very, very large data sets.
- big data cluster scale linearly.
- Yahoo then got on board. Yahoo hired someone named Doug Cutting who had been working on a clone or a copy of the Google big data architecture and now that's called Hadoop.
- Hadoop = big data ecology

## BIG DATA
- computational capabilities to apply some new techniques - machine learning
- we can take really large data sets and instead of taking a sample and trying to test some hypothesis we can take large dataset and look for patterns


## NOTE
K- Means clustering —> 
- melakukan perform object into cluster
    - objek similiar satu dengan yang lain
- mencari kelompok yang homogen —> bikin cluster
- Dalam cluster ini terdapat 2 centroid yang di assign secara random
- Centroid = titik tengah sebuah cluster
- Euclidean distance —> mencari centroid terdekat dengan setiap data point
- proses berlangsung secara iterativ sampai centroid stabil
- membagi cluster —> dimana masing2 objek ditempatkan di clusternya masing2
    - dimana objek2nya sama 1 sama lain


ASSIGN DATA POINT 

TIPE CLUSTERING
- HIERARCHICAL CLUSTERRING
    - Agglomerative
    - divisive
- PARTITIONAL CLUSTERING
    - K-means
    - Fuzzy C-Means

DISTANCE MEASURE —> MENGUKUR JARAK CLUSTERING
- Euclidean distance
- manhattan
- squared
- cosine distance

Distance —> menentukan similarity antara 2 elemen

EUCLIDIAN DISTANCE
- Merupakan ordinary straight line
- megukur jarak antara 2 point
- Vexp.(Qi-Pi)^2


K MEANS CLUSTERING BEKERJA
- cari titik centroid —> bersatu

  HADOOP ECOSYSTEM
- Hadoop banyak komponen yang terlibat
    - kafka
    - casandra
    - graphx
- Hadoop menggunakan map reduce 

HADOOP ARCHITECTURE


BIG DATA —> banyak data
- menggunakan mapReduce dari hadoop 
- HIVE —> Bahasa SQL dalam big dta, bisa pake SQL/ PHYTON
- HDFS —> buat simpan data
- CASANDRA —> dipake facebook
