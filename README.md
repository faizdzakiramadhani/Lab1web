# Lab1web
## Latihan
### Modul Praktikum web
#### Buatlah kerangka pengantar HTML 

![gambar1](https://github.com/faizdzakiramadhani/Lab1web/assets/115913915/e8cf88d7-8c67-411f-ad70-493a00d4552c)

![gambar2](https://github.com/faizdzakiramadhani/Lab1web/assets/115913915/8a8def5d-0ce3-48d8-ba41-74feff55aa38)



### 1. Membuat Paragraf
#### Buatlah 2 buah paragraf menggunakan`<p></p>`
![gambar3](https://github.com/faizdzakiramadhani/Lab1web/assets/115913915/51468997-cc46-4b9a-8a2a-7a7ddec7773c)


#### tampilan browser


### 2. Buat Judul
![gambar4](https://github.com/faizdzakiramadhani/Lab1web/assets/115913915/f54cdf4e-1ca8-47e7-9e47-5e36ad672692)
 Tambahkan judul di masing-masing paragraf pakai`<h1>` dan `<h2>`
![gambar5](https://github.com/faizdzakiramadhani/Lab1web/assets/115913915/22fc290c-aca1-478b-a7db-a0f14e5b8d71)


#### tampilan browser
![gambar6](https://github.com/faizdzakiramadhani/Lab1web/assets/115913915/1815bc44-c9c9-44ce-9762-1d0772445807)


### 3. Memformat Text
#### format text dan tambahkan fariasi seperti kata miring ,tebal ,garis bawah dll
![gambar7](https://github.com/faizdzakiramadhani/Lab1web/assets/115913915/0bfe9a4b-6519-442b-810e-232598604868)


#### tampilan browser
![gambar8](https://github.com/faizdzakiramadhani/Lab1web/assets/115913915/8e79e6cb-1eff-49a1-8e50-40d3b1ec16ad)

### 4. menyispkan gambar
#### letakan gambar di satu folder yang sama dengan file html ,lalu gunakan src
![gambar9](https://github.com/faizdzakiramadhani/Lab1web/assets/115913915/c097d579-4d3a-42cf-ae2c-cda60123f45a)


![gambar10](https://github.com/faizdzakiramadhani/Lab1web/assets/115913915/0ac4151a-bbb7-4c92-a72a-be745f2ce1d3)


#### tampilan browser
![gambar11](https://github.com/faizdzakiramadhani/Lab1web/assets/115913915/e9a8f861-a241-4cb6-ab6a-156069296fe3)

### 5. Tambahkan Hyperlink
#### buatlah navigasi diatas ,lalu buatkan satu file html lagi untuk link kedua dan satunya gunakan google
![gambar12](https://github.com/faizdzakiramadhani/Lab1web/assets/115913915/569518a3-4e0f-43f9-91cf-e4239d9dc32d)


#### tampilan browser
![gambar13](https://github.com/faizdzakiramadhani/Lab1web/assets/115913915/b289e9cf-8e33-4ed5-ae29-e26ab25f3650)


#### Jawab Pertanyaan Berikut
1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulisan tag?
2. Apa perbedaan dari tag `<p>` dengan tag `<br>`, berikan penjelasannya!
3. Apa perbedaan atribut title dan alt pada tag `<img>`, berikan penjelasannya!
4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar
proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top,
_parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?

### Jawaban ----
#### 1. tidak ada eror, karena tag nya telah dibuat dengan nama file pertemuan 1
![gambar14](https://github.com/faizdzakiramadhani/Lab1web/assets/115913915/b4e45596-8265-487d-b922-c169f4f23a56)


#### 2. `<p>` (paragraph) adalah elemen untuk membuat paragraf baru. Ini menambahkan jarak atas dan bawah elemen,
menciptakan batas paragraf. Sebuah paragraf baru dimulai setelah elemen `<p>`.
`<br>` (break) adalah elemen untuk melakukan pemisahan baris (line break). Ini hanya memindahkan teks ke baris 
baru dalam elemen yang sama, tanpa menciptakan paragraf baru.

#### 3. Perbedaan Atribut `title` dan `alt` pada `<img>`:
Atribut `title` digunakan untuk menyediakan informasi tambahan saat pengguna mengarahkan kursor ke gambar. Informasi ini muncul sebagai tooltip.
Atribut `alt` adalah teks alternatif yang akan ditampilkan jika gambar tidak dapat dimuat. Ini juga penting untuk aksesibilitas, membantu
orang dengan keterbatasan penglihatan atau jika gambar gagal dimuat.

#### 4. Atribut `width` dan `height` untuk Ukuran Gambar:
Agar tampilan gambar proporsional, sebaiknya minimal salah satu atribut (width atau height) diisi. Jika hanya satu diisi, browser akan mengukur atribut yang tidak diisi secara proporsional berdasarkan atribut yang diisi. Mengisi keduanya dapat mempertahankan proporsi asli gambar, namun, jika proporsi asli gambar tidak cocok dengan proporsi yang diinginkan, gambar dapat terlihat terdistorsi.

#### 5. Atribut `target` pada Link:
Atribut `target` pada link mengontrol bagaimana tautan dibuka saat diklik:
`_blank`: Membuka tautan di jendela atau tab baru.
`_self`: Membuka tautan di jendela atau tab yang sama (default).
`_top`: Menggantikan seluruh konten dengan tampilan dari tautan tersebut.
`_parent`: Menggantikan tampilan frame parent dengan tampilan dari tautan tersebut.
