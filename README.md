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
Fungsi dari integer dalam pemrograman adalah untuk merepresentasikan nilai bilangan bulat, baik positif maupun negatif, serta nol. Integer biasanya digunakan dalam operasi matematika seperti penjumlahan, pengurangan, perkalian, dan pembagian.





