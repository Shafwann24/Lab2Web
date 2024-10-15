1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
![image](https://github.com/user-attachments/assets/73bfc411-e156-47e8-8055-5a9cf9262bfc)
![image](https://github.com/user-attachments/assets/ebb9c884-bbf0-4d14-935e-030e7f8a0b4a)
2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!
h1 mengatur semua h1, sementara #intro h1 lebih spesifik dan hanya mengatur h1 dalam elemen dengan ID tertentu..
jawab: h1 mengatur semua elemen h1, sementara #intro h1 lebih spesifik dan hanya mengatur h1 yang terdapat dalam elemen dengan ID tertentu.
3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!
![image](https://github.com/user-attachments/assets/e8665807-60b7-4c11-a608-efeb6d7f0de5)
jawab: CSS inline.. inline css memiliki prioritas tertinggi. Jika ada konflik antara aturan-aturan ini, browser akan menampilkan gaya dari inline css terlebih dahulu, diikuti oleh css internal, dan terakhir css eksternal
Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya! (<p id="paragraf-1" class="text-paragraf">)
jawab: Jika ada deklarasi CSS untuk ID dan kelas yang diterapkan pada elemen HTML yang sama, deklarasi ID akan memiliki prioritas lebih tinggi dibandingkan kelas. Jadi, jika ada gaya yang bertentangan, gaya dari ID akan ditampilkan di browser.
