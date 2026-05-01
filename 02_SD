#Nama:*****
#NIM :******
#MKU :Struktur Data 

#Soal No. 1 B
print("-----------------------------------------------------------------------------------")
print("                  Soal 1 B, Gunakan Rumus List, Raw input, Append                  ")
print("-----------------------------------------------------------------------------------")

#List Kosong
bio = []
motor = []

#Judul
print("                            Form Pembelian Motor Honda                             ")
print(" ")

#Input data pembeli
nama = input("masukkan nama pembeli    : ")
alamat = input("masukkan alamat pembeli  : ")
tempat = input("masukkan tempat lahir    : ")
tanggal = input("masukkan tanggal lahir   : ")

#Input data motor
tipe = input("masukkan nama type motor : ")
harga = input("masukkan harga motor     : ")
warna = input("masukkan warna motor     : ")

#Menambahkan data ke list
bio.append(nama)
bio.append(alamat)
bio.append(tempat)
bio.append(tanggal)

motor.append(tipe)
motor.append(harga)
motor.append(warna)

#Hasil
print(f"Biodata Pembeli   : {bio}")
print(f"Motor yang dibeli : {motor}")

print(" ")
print(" ")
#Soal No. 2 B
print("-----------------------------------------------------------------------------------")
print("                Soal 2B, Rumus : List, While, Raw_input, Break, Del                ")
print("-----------------------------------------------------------------------------------")

genap = [2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30]

print(" ")
print(f"Daftar bilangan genap : {genap}")

while True:
    index = input("Masukkan indeks bilangan genap yang akan di hapus atau ketik 's' untuk berhenti : ")
    
    if index.lower() == "s":
        print("selesai")
        break
    try:
     idx = int(index)
     if idx < len(genap):
         del genap[idx]
         print(f"Hasil list bilangan genap setelah di edit : {genap}")
     else:
         print("Indeks di luar jangkauan!")
    except ValueError:
        print("Input tidak valid! Masukkan angka indeks atau 'S/s' untuk berhenti.")

print(" ")
print(" ")
#Soal No. 3 B
print("-----------------------------------------------------------------------------------")
print("                Soal 3B: Program Fungsi Len, Max dan Min pada Tuple                ")
print("-----------------------------------------------------------------------------------")
print(" ")

# Variabel Tuple
A = ("Program", "Studi", "Teknik", "Informatika", "Fakultas", "Saintek", "Unisnu")
B = (10, 20, 30, 40, 50, 60, 70, 80, 90, 100, 200, 300, 400, 500)

print("Tampilkan :")
# Menggunakan len()
print(f"Menentukan nilai len dari elemen A adalah : {len(A)}")
print(f"Menentukan nilai len dari elemen B adalah : {len(B)}")
print(" ")

# Menggunakan max() dan min()
print(f"Menentukan nilai maksimum atau terbesar dari elemen A adalah : {max(A)}")
print(f"Menentukan nilai minimum atau terkecil dari elemen A adalah  : {min(A)}")
print(" ")
print(f"Menentukan nilai maksimum atau terbesar dari elemen B adalah : {max(B)}")
print(f"Menentukan nilai minimum atau terkecil dari elemen B adalah  : {min(B)}")
