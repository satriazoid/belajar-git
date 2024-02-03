1. ketika code belum terdaftar di git maka lakukan perintah

//=======================================================================
`git init` => Pesan: Reinitialized existing Git repository in
//=======================================================================

2. Maka lanjut ke perintah git add Folder/file yang di tuju bisa juga
   Menggunakan titik(.) maka beberapa yang yang belum di commit akan masuk
   Lokal

//=================== ===================================================
`git add` => maka akan terjadi save ke repo lokal
//=======================================================================

3. Setelah itu gunakan git commit agar kita menyimpan code yang sudah di
   Kita edit

//=======================================================================
`git commit -m ["Pesan/Komentar"]`
//=======================================================================


4. maka folder repo lokal sudah siap di push ke repository online
seperti github/gitlab


//perintah selanjutnya adalah pemasangan link repo=======================
`git remote add origin [url repo]`
//=======================================================================


maka jika sudah repo sudha terdaftar pada repository online
lanjut ke perintah selanjutnya


//=======================================================================
Perintah => `git push -u origin main` // penanda -u
            `git push origin main` // simple
//=======================================================================
nah main itu branch yang kita sedang kita tempati

