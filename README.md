# Praktikum 3 feby
# 1.) Buat codingan dari flowchart yang menentukan bilangan terbesar dari 3 bilangan yang diinputkan
Berikut adalah flowchart nya
![flowchart 1](https://github.com/user-attachments/assets/58fa9350-bf8a-42dc-b1bd-dfd2531bfa67)
![ss codingan flowchart pertama](https://github.com/user-attachments/assets/3b1fa833-155e-46d9-9bfe-47ed22fc0c0d)

1. Input bilangan

Pengguna diminta untuk memasukkan tiga bilangan satu per satu. Nilai yang dimasukkan akan dikonversi menjadi tipe data float, yang memungkinkan pengguna memasukkan angka desimal.

2. Penggunaan (if-elif-else):

   -if a > b and a > c: Kondisi ini mengecek apakah a lebih besar dari b dan c. Jika benar, maka a adalah bilangan terbesar, dan program mencetak hasilnya.

   -elif b > a and b > c: Jika kondisi pertama salah, maka program akan mengecek apakah b lebih besar dari a dan c. Jika benar, maka b adalah bilangan terbesar.

   -else: Jika kedua kondisi di atas salah, maka c yang dianggap sebagai bilangan terbesar.

3. Output
   
![ss hasil flowchart pertama](https://github.com/user-attachments/assets/ff5154f6-3819-4dfc-ba25-f92684ce732a)

# 2.) Buat codingan dari flowchart yang menentukan bilangan terbesar dari N bilangan yang diinputkan. untuk menentukan jumlah N, berikan masukkan angka 0
Berikut adalah flowchart nya
![flowchart 2](https://github.com/user-attachments/assets/1c718c70-aec9-4f29-a92c-f1e6ed0088d7)
![ss codingan flowchart kedua](https://github.com/user-attachments/assets/e6f523af-5b63-44cf-87e3-a3bbdbf3f74d)

1. Inisialisasi Variabel  terbesar = float('-inf')

   - variabel terbesar diinisialisasi dengan nilai negatif tak terhingga (-inf). Ini dilakukan agar setiap bilangan yang dimasukkan oleh pengguna akan lebih besar dari nilai ini pada awalnya.
     
2. Input Jumlah Bilangan n = int(input("masukkan jumlah bilangan (N) atau 0 untuk mengakhiri: "))

   - Program meminta pengguna untuk memasukkan jumlah bilangan yang ingin dimasukkan. Pengguna dapat memasukkan angka positif untuk menentukan jumlah bilangan atau 0 untuk mengakhiri program.

3. Pengecekan Input Awal  if n == 0: 
    print("Tidak ada bilangan yang dimasukkan.")
    return

   - Jika pengguna memasukkan 0, program akan mencetak pesan bahwa tidak ada bilangan yang dimasukkan dan kemudian keluar dari fungsi dengan menggunakan return.
  
4. Perumusan dan Perbandingan  for i in range(n):
    bilangan = float(input(f"masukkan bilangan ke-{i+1}: "))
    if bilangan > terbesar:
        terbesar = bilangan

   - program akan melakukan iterasi sebanyak n kali. Pada setiap iterasi, pengguna diminta untuk memasukkan bilangan. Program kemudian membandingkan bilangan yang dimasukkan dengan nilai terbesar. Jika bilangan yang dimasukkan lebih besar dari terbesar, maka nilai terbesar akan diperbarui dengan bilangan tersebut.
  
5. Hasil Output  print(f"bilangan terbesar adalah: {terbesar}")

   ![ss hasil flowchart kedua](https://github.com/user-attachments/assets/e6792381-ba40-48c2-89c4-9241e68bfcaa)

   - Setelah semua bilangan dimasukkan dan dibandingkan, program akan mencetak bilangan terbesar yang ditemukan.
  
6. Pemanggilan Fungsi  cari_terbesar_dari_n()

   - Terakhir, fungsi cari_terbesar_dari_n() dipanggil untuk menjalankan program.

   


