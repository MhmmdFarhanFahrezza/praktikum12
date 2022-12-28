# praktikum12

# Latihan string python
txt = 'Hello World'
- hitung jumlah karakternya
- ambil karakter terakhir
- ambil karakter index ke-2 sampai index ke-4(llo)
- hilangkan spasi pada text tersebut(HelloWorld)
- ubah text menjadi huruf besar
- ubah text menjadi huruf kecil
- ganti karakter H menjadi karakter J

# Program
txt = 'Hello World'

# Hitung jumlah karakternya
print(len(txt)) #Output:

# Ambil karakter terakhir
print(txt[-1]) # Output: d

# Ambil karakter index ke-2 sampai index ke-4 (llo)
print(txt[2:5])  # Output: llo

# Hilangkan spasi pada text tersebut (HelloWorld)
txt = txt.replace(' ', '')
print(txt)  # Output: HelloWorld

# Ubah text menjadi huruf besar
print(txt.upper())  # Output: HELLOWORLD

# Ubah text menjadi huruf kecil
print(txt.lower())  # Output: helloworld

# Ganti karakter H dengan karakter J
print(txt.replace('H', 'J'))  # Output:JelloWorld
![2](https://user-images.githubusercontent.com/116137842/209748298-3e1f10d6-cfbd-48e0-9dc7-d87eec9982c8.png)


# Output
![1](https://user-images.githubusercontent.com/116137842/209748314-bd2dd58e-e8ef-4dcd-9bf0-ab66eadd9d2d.png)


# Lengkapi kode berikut :
umur = 24 txt = 'Hello, nama saya john, dan umur saya adalah ... tahun' print(txt.format(umur))

- Untuk menyelesaikan latihan ini, Kita dapat menggunakan method format pada string. Method format akan menggantikan placeholder {} dengan nilai yang diberikan
![3](https://user-images.githubusercontent.com/116137842/209748340-63e58c3d-e7d8-47ca-bd7e-581a1dcd93fa.png)

