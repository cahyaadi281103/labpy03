# labpy03
cahya adi saputra
352310835
IE.23.C.12
LATIHAN 1 intruksi perintah :

1. Tampilkan nilai n bilangan acak yang lebih kecil dari 0.5
2. Nilai n diisi saat run time
3. Menggunakan while atau for
4. Menggunakan fungsi random

Screenshoot Hasil Program yang dibuat
![Screenshot 2024-11-02 175540](https://github.com/user-attachments/assets/ab43d0fe-4cbd-4f1e-b037-52d194ca694a)
Algoritma dan penjelasan

1. Pertama kita buat program terlebih dahulu menggunakan Idle

2. Saat membuat program, yang pertama kita buat sistem input terlebih dahulu agar kita bisa menginput suatu bilangan saat di runtime dengan rumus n = int(input("Masukkan jumlah bilangan acak yang ingin ditampilkan: "))

3. Selanjutnya kita nisialisasi variabel untuk menghitung jumlah bilangan yang telah ditampilkan dengan rumus count = 0

4. Selanjutnya kita akan Menggunakan while untuk terus menghasilkan bilangan acak sampai mencapai n, dengan rumus while count < n:

5. Selanjutya kita akan menghasilkan bilangan acak dengan a = random()

6. Selanjutnya Memeriksa apakah bilangan acak kurang dari 0.5, rumus: if a < 0.5: count += 1 # Menambah hitungan bilangan yang ditampilkan print(f"Data ke : {count} => {a}")
Menampilkan bilangan acak dengan format yang diinginkan
7. Selesai
LATIHAN 2 Intruksi : Buat program untuk menampilkan bilangan terbesar dari n buah data yang diinputkan. Masukkan angka 0 untuk berhenti.

Screenshot Hasil Dari Program yang dibuat
![Screenshot 2024-11-02 175854](https://github.com/user-attachments/assets/b3767b00-42d6-46a4-a485-9aba4c9d60b8)
Algoritma dan penjelasan

1. Pertama kita buat program terlebih dahulu menggunakan Idle

2. Kita buat Inisialisasi variabel untuk menyimpan bilangan terbesar dengan rumus max_number = None

3. Selanjutnya kita buat while true : Mengambil input dari pengguna,

3. Memeriksa apakah pengguna memasukkan 0, Memperbarui bilangan terbesar jika diperlukan

4. Selanjutnya kita akan menamplkan bilangan terbesarnya dengan rumus, if max_number is not None: print("Bilangan terbesar adalah:", max_number) else: ("Tidak ada angka yang dimasukkan.")

5. Selesai

PROGRAM 1 Intruksi : Seorang pengusaha menginvestasikan uangnya untuk memulai usahanya dengan modal awal 100 juta, pada bulan pertama dan kedua belum mendapatkan laba. pada bulan ketiga baru mulai mendapatkan laba sebesar 1% dan pada bulan ke 5, pendapatan meningkat 5%, selanjutnya pada bulan ke 8 mengalami penurunan keuntungan sebesar 2%, sehingga laba menjadi 3%. Hitung total keuntungan selama 8 bulan berjalan usahanya.

Screenshot Hasil Dari Program yang dibuat
![Screenshot 2024-11-02 180045](https://github.com/user-attachments/assets/abff4cac-1af2-4ec5-9402-61895b08d608)
Algoritma dan penjelasan

1. Pertama kita buat program terlebih dahulu menggunakan Idle
2. Buat print modal awal,rumus :modal_awal = 100_000_000
3. Kita buat nisialisasi list untuk menyimpan laba setiap bulan dengan menggunakan statement for, in, If, elif
4. Menghitung total laba dengan rumus SUM
5. Menampilkan hasil dengan rumus For 1 in
6. Selesai
