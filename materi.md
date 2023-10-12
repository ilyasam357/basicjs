=== Membuat Kode JavaScript ===

- Bisa langsung di file HTML
- Atau bisa menggunakan file .js (ekstensi untuk JavaScript), lalu di include di dalam file HTML

==== komentar ====

- kode program yg tidak di eksekusi

====== tipe data number =======

- JavaScript hanya mendukung satu tipe data number, dimana tipe data number di JavaScript bisa berupa bilangan bulat atau bilangan desimal

=========== tipe data boolean =======

- Tipe data boolean adalah tipe data yang berisikan data kebenaran, artinya hanya ada dua data, benar dan salah (yes atau no)
- Benar di representasikan dengan kata kunci true, dan salah direpresentasikan dengan kata kunci false

=========== tipe data string =======

- Tipe data string atau text adalah tipe data yang berisikan kumpulan kosong atau lebih karakter
- Di JavaScript, untuk membuat data dengan tipe string, kita perlu menggunakan “ (petik dua) atau ‘ (petik satu) sebelum dan setelah isi text nya

=== Escape sequence ====

- JavaScript mendukung escape sequence di string. Escape sequence merupakan karakter khusus, seperti ENTER, TAB, " (kutip dua), dan lain-lain. Berikut contoh escape sequence yang didukung oleh JavaScript di data string

=== variable ====

- Variable adalah tempat untuk menyimpan data
- Dengan menyimpan data di variable, kita bisa menggunakannya lagi dengan menyebutkan nama variable nya
- nama variable tidak boleh ada spasi

== kata kunci let dan const ==

- Sebelum tahun 2015, kata kunci untuk membuat variable hanya bisa menggunakan kata kunci var
- Namun tahun 2015 sejak versi ECMAScript 2015, diperkenalkan kata kunci baru untuk membuat variable, let dan const
- JavaScript sekarang tidak direkomendasikan lagi menggunakan kata kunci var untuk membuat variable, namun diganti dengan let, hal ini dikarenakan ada masalah dari desain awal var (akan kita bahas di chapter tersendiri)

== const ==

- Kata kunci let itu seperti kata kunci var, dimana data di variable tersebut bisa diubah-ubah sesuka kita
- Sedangkan kata kunci const berbeda, ketika sebuah variable sudah diisi di variable const, maka variable tersebut tidak bisa diubah lagi value nya
- Variable sejenis ini kadang dibilang juga constant

===== operator matematika =======
-JavaScript mendukung banyak sekali operator Matematika untuk tipe data Number, seperti :
- Operator Aritmatika
- Operator Augmented Assignments
- Operator Unary

=== Operator Aritmatika ===
- "+" ket : pertambahan
- "-" ket : pengurangan 
- "*" ket : Perkalian
- "**" ket : Exponensial
- "/" ket : Pembagian
- "%" ket : Sisa Bagi

=== Operator Augmented Assignments ===
- "+=" 
- "-="  
- "*=" 
- "**=" 
- "/=" 
- "%="

=== Operator Unary ===

- "+" ket : Menandakan nilai positif
- "-" ket : Menandakan nilai negatif 
- "++" ket : Increment, menaikkan 1 angka
- "--" ket : Decrement, menurunkan 1 angka

======== Operator Operasi Perbandingan  =========
- Operasi perbandingan adalah operasi untuk membandingkan dua buah data
- Operasi perbandingan adalah operasi yang menghasilkan nilai boolean (benar atau salah)

== Operator Perbandingan ==
 
- ">" ket : Lebih Dari
- "<" ket : Kurang Dari 
- ">=" ket : Lebih Dari Sama Dengan
- "<=" ket : Kurang Dari Sama Dengan
- "==" ket : Sama Dengan
- "===" ket : Sama Dengan dan Sama Tipe
- "!=" ket : Tidak Sama Dengan
- "!==" ket :Tidak Sama Dengan atau Tidak Sama Tipe

==== Operator Logika ======

- Operator logika adalah operator untuk dua buah data boolean
- Hasil dari operator logika adalah boolean lagi

== Operator Logika ==
 
- "&&" ket : Dan
- "||" ket : Atau 
- "!" ket :  Kebalikan