# tugaspemrograman7
## Tugas bahasa program pertemuan 5
## BIODATA
NAMA: Dhani Naufal Habibie

KELAS TI 24.A.4

NIM:312410300

MATKUL:BAHASA PEMOGRAMAN

Dosen : Agung Nugroho, S.Kom., M.Kom.


# Latihan pertemuan 7
![Screenshot 2024-11-02 101312](https://github.com/user-attachments/assets/03984253-516a-48df-a4ce-7e61477e4fc1)


# latihan 1
![Screenshot 2024-11-02 101535](https://github.com/user-attachments/assets/cfc5d4c6-c4fe-4b76-bc03-28759ff09dcc)

kode yang di jalankan

```python
#mengimport angka random
from random import random

n = int(input("MASUKAN BILANGAN :"))
while n==n:
    break
for i in range(n):
    a = random() * 0.5 #data akan menampilkan bilangan kurang dari 0.5
    print(f"data ke-{i+1} => {a}") 
print("selesai")
````


#penjelasan

#Perulangan while


Perulangan while disebut uncounted loop (perulangan yang tak terhitung),

yaitu perulangan yang dilakukan berdasarkan kondisi tertentu selama nilai kondisi bernilai TRUE.

#mengimport angka random

kita diminta untuk memasukan berapa banyak data yang ingin kita masukkan

angka yang di input tidak boleh lebih dari 0,5

![Screenshot 2024-11-02 072417](https://github.com/user-attachments/assets/1b023d2e-4d6b-459d-b386-5cb4994eb398)

Hasil dari code tersebut

![Screenshot 2024-11-02 072017](https://github.com/user-attachments/assets/fa6c6f74-a965-4422-a9d7-4882344b2696)

bisa dilihat bahwa tidak ada angka yang lebih dari 0,5

# latihan 2

![Screenshot 2024-11-02 104829](https://github.com/user-attachments/assets/7575192e-30ca-4e1b-9853-0cfda30d4807)

kode yang dijalankan

```python
#modal awal
modal_awal = 100_000_000

#laba keuntungan per bulan
laba_perbulan = [0, 0, 0.01, 0.01, 0.05, 0.05, 0.05, 0.03]

#total keuntungan
keuntungan = 0

for bulan, presentase in enumerate (laba_perbulan, start=1):
    laba = modal_awal * presentase
    keuntungan += laba
    print(f"laba bulan ke-{bulan}: {laba:,.0f}")
print(f"\nTotal keuntungan selama 8 bulan: {keuntungan:,.0f}")
````


#penjelasan

Variabel modal_awal: Menyimpan modal awal sebesar 100 juta rupiah.

List laba_per_bulan: Menyimpan persentase laba untuk setiap bulan selama 8 bulan.

Loop: Menghitung laba berdasarkan persentase di setiap bulan, lalu menambahkan laba tersebut ke total_keuntungan.

ada 8 bulan, 100 juta rupiah di kalikan dengan

bulan pertama 0%

bulan kedua 0%

belum ada kenaikan di 2 bulan pertama

bulan ketiga 1%

bulan keempat 1%

bulan ke3-4 terjadi kenaikan 1%

bulan kelima 5%

bulan keenam 5%

bulan ketujuh 5%

bulan ke 5,6,7 kenaikan sebesar 5%

bulan kedelapan 3%

bulan ke 8 terjadi penurunan 2%, jadi hanya 3%

Output: Mencetak laba per bulan dan total keuntungan setelah 8 bulan.

![Screenshot 2024-11-02 074932](https://github.com/user-attachments/assets/192ab366-8122-408f-8175-3102e6371a56)

Hasil dari kode tersebut

![Screenshot 2024-11-02 074940](https://github.com/user-attachments/assets/5b347d5b-339a-46ec-a720-d1523d841962)

Total laba yang di dapat dari ke 8 bulan tersebut ada 20 juta

# latihan 3

![Screenshot 2024-11-02 110113](https://github.com/user-attachments/assets/f35678b5-3ebe-4d1c-9e88-14c85097ee63)

kode yang dijalankan

```python
saldo_awal = 1000000

while True:
    print(f"Saldo saat ini: Rp {saldo_awal}")
    print("1. Tarik Uang")
    print("2. Keluar")

    #pilihan menu
    menu = input("Pilih menu (1/2): ")

    if menu == "1":
    # Tarik uang
        jumlah_tarik = int(input("Masukkan jumlah penarikan: "))
        
        
        if jumlah_tarik <= saldo_awal: #cek saldo cukup atau tidak
            saldo_awal -= jumlah_tarik
            print("Penarikan berhasil!")
        else:
            print("Saldo anda tidak mencukupi!")
            
    elif menu == "2": # Keluar dari program
        print("Terima kasih, have a good days:) ")
        break
    else:
        print("Pilihan tidak valid.")

else:
    print("Terima kasih, have a good days:) ")
````

#Penjelasan

Kode ini memulai dengan saldo awal sebesar Rp 1.000.000.

Pengguna dapat memilih untuk menarik uang atau keluar dari program.

Jika pengguna memilih untuk menarik uang, maka program akan meminta jumlah penarikan dan mengurangi saldo jika jumlahnya mencukupi.

Jika pengguna memilih untuk keluar, program akan mengucapkan terima kasih dan berhenti.


![Screenshot 2024-11-02 090439](https://github.com/user-attachments/assets/a1e12bd4-b9a0-4f5f-8dfc-143a401f05fa)

hasil dari kode tersebut

![Screenshot 2024-11-02 090354](https://github.com/user-attachments/assets/ca3820c1-1614-4a16-a9b3-bcf573cb8102)


