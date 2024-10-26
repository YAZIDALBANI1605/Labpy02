## NAMA: Naufal Yazid
## NIM: 312410279
## KELAS: TI.24.A.4

## MENENTUKAN NILAI AHKIR
````PYTHON
nama = input("Masukkan nama:")
uts = input("Masukkan nilai UTS:")
uas = input("Masukkan nilai UAS:")
tugas = input("Masukkan nilai Tugas:")
akhir = (int(tugas) * .2) + (int(uts) * .4) + (int(uas) * .4)
keterangan = ("TIDAK LULUS", "LULUS")[akhir > 60.0]

if akhir > 80:
    huruf = "A"
elif akhir > 70:
    huruf = "B"
elif akhir > 50:
    huruf = "C"
elif akhir > 40:
    huruf = "D"
else:
    huruf = "E"

print("\nNama :",nama)
print("Nilai UTS :",uts)
print("Nilai UAS :",uas)
print("Nilai Tugas :",tugas)
print("Nilai Akhir :",akhir)
print("\nNilai Huruf :",huruf)
print("Keterangan :",keterangan)
```
```python
nama = input("Masukkan nama:")
uts = input("Masukkan nilai UTS:")
uas = input("Masukkan nilai UAS:")
tugas = input("Masukkan nilai Tugas:")
````
fungsi `input()` digunakan untuk memasukkan data atau informasi ke dalam sistem atau program komputer, 

```python
akhir = (int(tugas) * .2) + (int(uts) * .4) + (int(uas) * .4)
````
Fungsi dari `integer` dalam pemrograman adalah untuk merepresentasikan nilai bilangan bulat, baik positif maupun negatif, serta nol. Integer biasanya digunakan dalam operasi matematika seperti penjumlahan, pengurangan, perkalian, dan pembagian.

fungsi dari `*` untuk mengkalikan angka,dan fungsi dari ` .2` adalah 0 koma 2

dan nilai tugas yang di masukan 90 ,maka akan dikalikan program di atas  .2 yaitu( 0.2) maka keluar cetakan 18

```python
keterangan = ("TIDAK LULUS", "LULUS")[akhir > 60.0]
````
keterangan ini hanya sebuah variable yang nantinya akan di cetakan,dan hasil ahkir akan memproses 

```python
if akhir > 80:
huruf = "A"
elif akhir > 70:
huruf = "B"
elif akhir > 50:
huruf = "C"
elif akhir > 40:
huruf = "D"
else:
huruf = "E"
````
ini adalah struktur kondisi yang menggunakan `if`, `elif` , dan`else`

```python
if akhir > 80:
huruf = "A"
````
jika hasil dari nilai tersebut lebih besar dari 80 maka output yang keluar (A)

```python
else:
huruf = "E"
````
jika tidak sesuai semuanya pada program di atas output akan keluar(E)

```python
print("\nNama :",nama)
print("Nilai UTS :",uts)
print("Nilai UAS :",uas)
print("Nilai Tugas :",tugas)
print("Nilai Akhir :",akhir)
print("\nNilai Huruf :",huruf)
print("Keterangan :",keterangan)
````
fungsi `print()` adalah mencetak variable-variable pada program tersebut

## menampilkan gaji karyawan

```python
gaji = int(input("Masukkan gaji:"))
berkeluarga = (False, True)[input("Sudah berkeluarga? (Y/T)") == "Y"]
punya_rumah = (False, True)[input("Punya rumah? (Y/T)") == "Y"]

if gaji > 3000000:
    print ("Gaji sudah diatas UMR")

    if berkeluarga:
        print ("Wajib ikutan asuransi dan menabung untuk pensiun")

    else:
         print ("Tidak perlu ikutan asuransi")

    if punya_rumah:
        print ("wajib bayar pajak rumah")

    else:
        print ("tidak wajib bayar pajak rumah")

else:
    print ("Gaji belum UMR")
````

struktur ini menggunakan kondisi `if`, `elif`, dan `else`

```python
gaji = int(input("Masukkan gaji:"))
````
inputan ini akan memasukan angka gaji,karena memiliki fungsi `int`

```python
berkeluarga = (False, True)[input("Sudah berkeluarga? (Y/T)") == "Y"]
punya_rumah = (False, True)[input("Punya rumah? (Y/T)") == "Y"]
````
inputan ini menggunakan fungsi `string` yang di masukan berupa huruf,dan `(false,true)` ini adalah fungsi pemilihan Ya atau Tidak,agar tidak meggunakan `if` di lanjutan program tersebut

```python
if gaji > 3000000:
    print ("Gaji sudah diatas UMR")

    if berkeluarga:
        print ("Wajib ikutan asuransi dan menabung untuk pensiun")
    else:
        print ("Tidak perlu ikutan asuransi")
````
jika angka gaji angka gaji lrbih dari 3 juta maka output yang keluar"gaji sudah diatas UMR" dan jika tidak,output yang keluar"Tidak perlu ikut asuransi"

```python
if punya_rumah:
        print ("wajib bayar pajak rumah")

    else:
        print ("tidak wajib bayar pajak rumah")
````
Jika memiliki rumah maka `output` yang keluar adalah"Wajib bayar pajak", Jika tidak mempunyai rumah maka `output` yang keluar ialah "Tidak wajib bayar pajak"

```python
else:
    print ("Gaji belum UMR")
````

`else` yang berada di paling bawah ini terhubung dengan `if Gaji > 3000000:` apabila gaji tidak melebihi dari 3 juta `output` yang keluar"gaji belum UMR"

## Menggunakan kondisi OR dengan menginputkan 3 bilangan 

```python
a = int(input("Masukkan bilangan A: "))
b = int(input("Masukkan bilangan B: "))
c = int(input("Masukkan bilangan C: "))
if a+b == c or b+c == a or c+a == b:
    print("BENAR")
else:
    print("SALAH")
````
operator OR dalam python merubah beberapa kondisi dan mengembalikan true jika salah satu benar.

```python
a = int(input("Masukkan bilangan A: "))
b = int(input("Masukkan bilangan B: "))
c = int(input("Masukkan bilangan C: "))
````
Program ini menginputkan sesuatu `integer` yang menggunakan variable
a,b,c.

```python
if a+b == c or b+c == a or c+a == b:
    print("BENAR")
else:
    print("SALAH")
````
jika (A) ditambah (B) haslnya (C) atau bahasa pemograman itu `OR` ,dan apabila (B) ditambah (C) hasilnya (A),dan (C) ditambah (A) maka hasilnya (B).
maka output yang keluar adalah "benar"

## Latihan 3
## Pemesanan tiket bioskop

Kasus 1: Program Pemesanan Tiket Bioskop
Buat program yang menghitung harga tiket bioskop. Tiket reguler berharga Rp50.000,
sedangkan tiket VIP berharga Rp100.000. Jika user memiliki kartu member, mereka
mendapatkan diskon 20% dari harga tiket. Program ini harus meminta tipe tiket dan status
member dari user, lalu menghitung total harga yang harus dibayar.

Petunjuk:

    ● Gunakan if else dan operator ternary.
    
```python
harga_reguler = 50000
harga_vip = 100000

tipe_tiket = (input("Masukkan tipe tiket (reguler/VIP): "))
status_member = (input("Apakah Anda memiliki kartu member? (ya/tidak): "))

 Menghitung total harga
if tipe_tiket == "reguler":
    total_harga = harga_reguler
elif tipe_tiket == "vip":
    total_harga = harga_vip
else:
    print("Tipe tiket tidak valid.")
    exit()

 Menghitung diskon jika pengguna memiliki kartu member


if status_member == "ya":
        total_harga *= 0.8  # Diskon 20%
    
        print(f"Total harga yang harus dibayar: Rp{total_harga:.2f}")
elif status_member == "tidak":
            total_harga
            print(f"total harga yang harua dibayar: Rp{total_harga:.2f}")
else:
    print("Harga tidak dapat dihitung.")
 ````
