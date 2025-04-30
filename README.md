### Laporan task 1

### Subtask A

![task1_a_code](images/task1_a_code.png)

- Menggunakan wget untuk mendownload file zip dari gdrive pada proses child
- Menggunakan unzip pada parent untuk mengekstrak file zip yang sudah didownload

**Hasil output**

![task1_a_out](images/task1_a_out.png)

### Subtask B

![task1_b_code](images/task1_b_code.png)

- Menggunakan sracnd(time(NULL) untuk mendapatkan angka acak 
- Menggunakan while untuk menghitung jmlh film
- Menggunakan MOD untuk mencari film acak

**Hasil output**

![task1_b_out](images/task1_b_out.png)

### Subtask C

![task1_c_code1](images/task1_c_code1.png)
![task1_c_code2](images/task1_a_code2.png)
![task1_c_code3](images/task1_a_code3.png)

- Membuat fungsi untuk menghitung jumlah film
- Pada fungsi log menggunakan time(NULL) dan localtime(&now) untuk mendapatkan waktu saat ini
- Pada fungsi extract Menggunakan strchr untuk mendapatkan genre dari nama film
- Pada fungsi film menggunakan strcmp untuk membandingkan nama genre film agar dipindahkan ke folder sesuai genre film
- Pada main menggunakan mkdir untuk membuat folder 
- Menggunakan strncpy untuk menyalin nama film ke struck film
- Menggunakan fork dan if agar move film Peddy dan Trabowo dilakukan secara bergantian
- Membandingkan jmlh genre untuk mendapatkan genre yang paling banyak
- Menggunakan fprint untuk menampilakan jumlah genre serta genre yang paling banyak di folder total.txt

![task1_c_out1](images/task1_c_out1.png)
![task1_c_out2](images/task1_c_out2.png)
![task1_c_out3](images/task1_c_out3.png)

### Subtask D

![task1_d_code](images/task1_d_code.png)

- Pada fungsi zip menggunakan fork untuk membuat zip dan menghapus folder yang sudah dizip
- Membuat zip pada child dan menghapus folder pada parent
- Pada main chdir untuk menuju folder film

![task1_d_out](images/task1_d_out.png)
