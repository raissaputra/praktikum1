# praktikum1
### Tugas Pertemuan ke 05, matakuliah Bahasa Pemrograman

1. **Penjelasan file latihan.py :**
  - Menetapkan nilai pada variabel :
    - ``` nama_lengkap = "Rais Saputra"
          nama_panggilan = "Rais"
          npm = 311810195
          umur = 25
          tempat_lahir = "Kebumen"
          telepon = 6281549454938
          alamat = "Harapan Mulya NO.20B, Medan satria, Kota Bekasi"
      ```
  - Konversi nilai variabel :
  ```
  txt = "Assalamu'alaikum.\n\nLet me introduce my self. My name is {}, but you can call me {}. My NPM is {}. I was born in {} and I am {} years old. I am very glad if you want to invite my house in {}. So, don't forget to call me before with the number {}.\n\nThank you."
  ```
  - Menampilkan output :
  ```
  print(txt.format(nama_lengkap, nama_panggilan,
      npm, tempat_lahir, umur, alamat, telepon))
  ```

2. SCREENSHOT OUTPUT PROGRAM :
  - ![img](https://github.com/raissaputra/praktikum1/blob/main/assets/output.png)
  
  
### **Output program file latihan1.py :**
* ![img](https://github.com/raissaputra/praktikum1/blob/main/assets/output-lat-1.png)
* Penjelasan program :
  * ada eror "TypeError: %d format: a number is required, not str"
  * karena inputan variabel a, b adalah bertipe string
  * sedangkan permintaan program harus nya variabel yang di inputkan adalah number
  * tambah kode seperti dibawah ini, agar program tidak terjadi error.
  * ``` 
        a = int(input("masukan nilai a : "))
        b = int(input("masukan nilai b : "))
    ```
