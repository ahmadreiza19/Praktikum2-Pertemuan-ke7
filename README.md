# Praktikum2-Pertemuan-ke7
Dibuat untuk memenuhi tugas Bahasa Pemrograman <br>

Nama    : Ahmad Reiza<br>
NIM     : 312010037<br>
Kelas   : TI.20.B.1<br>
<hr>

### Menentukan bilangan terbesar dari 3 nilai yang diinputkan
<br>
Pada Pertemuan ke-7 ini saya mendapat tugas membuat aplikasi yang menentukan bilangan terbesar dari tiga nilai yang client/user inputkan menggunakan Bahasa Pemrograman Pyython. <br>

Pada repository ini saya akan menjelaskan alur dalam *flowchart* yang telah saya buat, file *flowchart* bisa dilihat pada link berikut ini : [Praktikum2-Pertemuan-ke7](flowchart.pdf)
<br><br>
Berikut ini source code yang saya tulis untuk menjadikan aplikasi tersebut.

``` python
print("Masukan pilihan angka ke-1 : ")
xangka1 = int(input())
print("Masukan pilihan angka ke-2 : ")
xangka2 = int(input())
print("Masukan pilihan angka ke-3 : ")
xangka3 = int(input())

print("\n")

if (xangka1 > xangka2) and (xangka1 > xangka3):
    print(f"Bilangan pertama ({xangka1}) lebih besar dari Bilangan kedua dan ketiga")
elif (xangka2 > xangka1) and (xangka2 > xangka3):
    print(f"Bilangan kedua ({xangka2}) lebih besar dari Bilangan pertama dan ketiga")
elif (xangka1 == xangka2) and (xangka1 == xangka3) and (xangka2 == xangka3):
    print("Bilangan yang dimasukan sama besar")
else:
    print(f"Bilangan ketiga ({xangka3}) lebih besar dari Bilangan pertama dan kedua")
```

Saya akan menjelaskan langkah-langkah nya :<br>

* Langkah pertama yaitu saya akan membuat sebuah inputan tersebut untuk menentukan angka terbesar, yaitu dengan mengetikan perintah/syntax berikut ini :<br>

'''python
print("Masukan pilihan angka ke-1 : ")
xangka1 = int(input())
print("Masukan pilihan angka ke-2 : ")
xangka2 = int(input())
print("Masukan pilihan angka ke-3 : ")
xangka3 = int(input())
'''
<br>

* Sesuai *flowchart* yang saya , client/user diminta untuk memasukan nilai inputan berupa angka dan akan disimpan kedalam variable xangka1,xangka2, dan xangka3. <br>
Setalah proses input nilai selesai buat, client/user diminta untuk memasukan nilai inputan berupa angka dan akan disimpan kedalam variable xangka1,xangka2, dan xangka3. <br>
Setelah proses input nilai selesai maka saya akan membuat pemilihan angka terbesar berdasarkan kondisi. <br>
<br> Paa 