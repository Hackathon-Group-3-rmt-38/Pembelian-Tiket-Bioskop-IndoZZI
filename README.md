# Patch-ver.1.1-release

NOTE :
- Push origin secara terpisah ( Gunakan branch masing-masing. Jangan branch main / master )
- Ketika pull request, compare terhadap branch masing-masing. Kemudian jangan di-merge KECUALI jika hasil eksperimen pengerjaan kita sudah berhasil & ingin diteruskan fiturnya, kita akan merging dengan branch main/master. Kemudian pecah lagi branch-nya dari branch main/master yang versi terbaru.

DIRECTION :
1. Pada saat baru saja git clone, langsung saja git checkout -b "namaBagianTugasManaYangDikerjakan"
2. Pada saat pertamakali sudah selesai mengerjakan, jangan lupa git add . & git commit -m "version 1.0" , kemudian git push origin "namaBagianTugasManaYangDikerjakan"
3. Kemudian pengerjaan yg sudah selesai utk keduakalinya dan seterusnya, gunakan git commit -m "version 1.1" , "version 1.2" , dan seterusnya ~
4. Jika terdapat bug lalu sudah diperbaiki, git commit -m "version 1.x (bug-fixed)"
