

# PRAKTIKUM PEMROGRAMAN WEB 3

## Praktikum

Praktikum pemrograman web membuat list, table dan form. Praktikum dilakukan dengan mengikuti petunjuk pada modul yang sudah disediakan.

## 1. List

List berikut adalah hasil dari praktikum yang dilakukan dengan mengikuti petunjuk dalam modul.

![enter image description here](https://github.com/antonmartinus72/Lab3Web/raw/main/assets/1_ss.jpg)

![enter image description here](https://github.com/antonmartinus72/Lab3Web/raw/main/assets/1_code.jpg)

## 2. Ordered List

Berikut adalah ordered list yang sudah diubah dari urutan angka menjadi huruf :

![enter image description here](https://github.com/antonmartinus72/Lab3Web/raw/main/assets/2_ss.jpg)

Bagian yang diubah terdapat pada tag ordered list `<o>` pada atribut `type="A"` yang digunakan untuk menentukan tipe urutan list dan atribut `start="2"` untuk menentukan urutan dimulai pada urutan ke 2 yaitu "B".

![enter image description here](https://github.com/antonmartinus72/Lab3Web/raw/main/assets/2_code.jpg)


## 3. Unordered List

Bullet pada unordered list diubah dengan menggunakan gambar sebagai bullet.

![enter image description here](https://github.com/antonmartinus72/Lab3Web/raw/main/assets/3_ss.jpg)

Unordered list pada gambar diatas menggunakan css untuk mengubah bullet pada list.

![enter image description here](https://github.com/antonmartinus72/Lab3Web/raw/main/assets/3_code.jpg)

## 4. Description List

Unordered list juga dapat digunakan sebagai nested list seperti berikut :

![enter image description here](https://github.com/antonmartinus72/Lab3Web/raw/main/assets/4_ss.jpg)

Description List diatas dapat dibuat menjadi nested dengan memasukan tag description list `<dl>` kedalam tag `<dd>` di bawahnya.

![enter image description here](https://github.com/antonmartinus72/Lab3Web/raw/main/assets/4_code.jpg)

## 5. Table

Berikut adalah hasil dari table yang ada pada modul praktikum :

![enter image description here](https://github.com/antonmartinus72/Lab3Web/raw/main/assets/5_ss.jpg)

![enter image description here](https://github.com/antonmartinus72/Lab3Web/raw/main/assets/5_code.jpg)

## 7. Table Dengan Rowspan

Tabel berikut menggunakan atribut `rowspan` untuk menggabungkan baris seperti berikut :

![enter image description here](https://github.com/antonmartinus72/Lab3Web/raw/main/assets/6_ss.jpg)

Atribut rowspan `<rowspan="3">` dibawah ini digunakan untuk mengisi kolom sepanjang 3 baris.

![enter image description here](https://github.com/antonmartinus72/Lab3Web/raw/main/assets/6_code.jpg)

## 8. Table Dengan CSS

Tampilan tabel berikut sudah di ubah menggunakan atribut css. 

![enter image description here](https://github.com/antonmartinus72/Lab3Web/raw/main/assets/7_ss.jpg)

Border pada table diubah menjadi tipe `dashed` didalam css internal pada atribut `border-style`.

Untuk backgroud diubah dalam css internal maupun css inline pada atribut `style` html.

![enter image description here](https://github.com/antonmartinus72/Lab3Web/raw/main/assets/7_code.jpg)

## 9. Form

Berikut form hasil dari praktikum yang ada pada modul.

![enter image description here](https://github.com/antonmartinus72/Lab3Web/raw/main/assets/8_ss.jpg)

![enter image description here](https://github.com/antonmartinus72/Lab3Web/raw/main/assets/8_code.jpg)

## 11. Form dengan Dropdown dan Listbox.

Form dibawah ini menggunakan tag `<input>` untuk melakukan input biasa dan tag `<select>` untuk melakukan input yang dipilih dari drowdown dan Listbox.

List box pada gambar dibawah ini dapat dipilih secara multiple atau ganda dengan menggunakan tombol **control** atau **shift** pada keyboard.

![enter image description here](https://github.com/antonmartinus72/Lab3Web/raw/main/assets/9_ss.jpg)

Form pada kode dibawah ini menggunakan atribut `method="get"` untuk sekedar mengetahui apakah hasil input dapat dikirim ke halaman yang dituju.

Tag yang digunakan untuk membuat **dropdown** adalah tag `<select>` dengan tag `<option>` di dalamnya untuk mendefinisikan nama nilai dan diisi atribut `value` yang digunakan untuk mendifinisikan nilai, yang akan dikirim ke halaman yang dimaksud. Dalam kasus ini adalah "submitdatabarang.php" yang ada pada tag `<form>`.

Sedangkan untuk membuat **listbox** bentuk yang digunakan hampir sama dengan **dropdown**. Perbedaannya adalah terdapat atribut `multiple` pada tag `<select>` yang digunakan untuk memilih item secara ganda. Dengan menggunakan atribut `multiple` maka listbox akan dibuat secara otomatis.

![enter image description here](https://github.com/antonmartinus72/Lab3Web/raw/main/assets/9_code.jpg)

Selanjutnya adalah hasil yang dikirim ke halaman "submitdatabarang.php".
Data dikirim dengan menggunakan tombol hijau yang ada pada bagian bawah halaman. Data yang dikirim berikut menggunakan `mothod="get"`.

![enter image description here](https://github.com/antonmartinus72/Lab3Web/raw/main/assets/10_ss.jpg)

Sekian & terimakasih
