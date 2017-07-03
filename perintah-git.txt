# Daftar Perintah GIT #

1. Membuat Repository baru
		git init nama-folder

2. cek status 
		git status

3. untuk mendapatkan tracking (staging) dari git 
		git add nama-file / . (titik untuk mendapatkan seluruh file yang ada pada 1 folder rekursif sampai ke bawah bawahnya)

4. mendapatkan username dan email pada git app
		git config --global user.email "nama-email"
		git config --global user.name "nama-user"

5. untuk melakukan commit terhadap file tersebut
		git commit -m "message-nya"

6. menampilkan apa yang berubah
		git diff

7. melihhat diifference antara versi
		git diff id-versi-1..id-versi-2

8. membatalkan perubahan diseluruh staging, fungsinya agar semua versi bisa di-marge pada kondisi ada yang sudah di-staging area
git reset
coba untuk melihat data yang sudah masuk kedalam staging pilih apa saja yang akan di commit

9. menambahkan ke staging area baris perbaris
git add nama-file -p
* y = yes
  n = no
  s = split
dll


10. cara untuk mengupload project
git push -u nama-project/alias branch-name
"-u berfungsi untuk default remote, karena bisa banyak remote"

11. cara mendownload project
git clone url yang ada pada server

12. menambahkan branch 
git branch brance-name

13. cek status branch
git branch
 
14 --

15 -- 
