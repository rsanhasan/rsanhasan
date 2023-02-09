---
layout: post
title:  "Belajar Python #01: Mengganti kata dalam sebuah frasa"
author: sal
categories: [ Python, belajar ]
featured: true
hidden: false
image: assets/images/2023-02-08-belajar-python-mengganti-kata-dalam-sebuah-frasa.png
---

Series belajar python yang pertama akan dibahas adalah **String**. *Type* data yang satu ini memuat untuk nilai yang berupa *text*. Kita bisa mengganti sebuah kata dalam frasa tetapi tidak ingin mengubah nilai asli dalam variabel.

Contoh dari penggunaan *string*:

```
nama_kota = 'Surabaya'
``` 

Fungsi *string* yang akan kita gunakan adalah *replace()*.

##### *replace()*
Fungsi *replace()* akan mengubah sebuah kata dengan kata lainnya.
Sintaksis yang tersedia:

> string.replace(oldvalue, newvalue, count)


*oldvalue* merupakan kata yang akan kita cari. *newvalue* merupakan sebuah kata baru yang akan kita gunakan untuk mengganti *oldvalue* yang dicari. Sedangkan *count* merupakan sebuah parameter opsional dari jumlah kata yang akan atau ingin kita ubah di dalam sebuah frasa.

contoh penggunakan dari fungsi *replace()* :

```
variabel = "Belajar Python online di kantor"
variabel.replace('kantor', 'starbuck')
```

hasil *output* yang akan ditampilkan menjadi `Belajar Python online di starbuck`.
Jika kita menambakan nilai untuk parameter `count`, bisa menambahkannya seperti contoh berikut:

```
variabel = "Belajar Python online di kantor. kantor yang terletak di seberang restoran cepat saji sangatlah ramai pengunjung. kantor berjarak 500 meter dari simpang lampu merah"
variabel.replace('kantor', 'starbuck')
variabel.replace('kantor', 'starbuck', 2)
```

hasil *output* dari kode baris 2 akan mengubah semua kata `kantor` menjadi `starbuck`. Sedangkan kode baris 3 hanya mengubah 2 dari total 3 kata `kantor` yang ada dalam variabel tersebut.

selamat belajar ya gaes ya!!