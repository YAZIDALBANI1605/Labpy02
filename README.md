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
inputan ini menggunakan fungsi `string` yang di masukan berupa huruf,dan `(false,true) ini adalah fungsi pemilihan Ya atau Tidak,agar tidak meggunakan `if` di lanjutan program tersebut

```python
````




