# Proyek Basis Data Pertemuan ke-05
 Endah sukma kuncari
Model-View-Controller atau MVC adalah sebuah metode untuk membuat sebuah aplikasi 
dengan memisahkan data (Model) dari tampilan (View) dan cara bagaimana 
memprosesnya (Controller). Dalam implementasinya kebanyakan framework dalam
aplikasi website adalah berbasis arsitektur MVC.

versi yang saya gunakan yaitu mongodb-win32-x86_64-2008plus-ssl-3.6.3-signed
untuk dapat mengakses mongoDB saya mengunakan perintah 
C:\mongodb\bin> mongod --dbpath C:\data jika berhasil maka akan menampilkan
 
saat membuat database yaitu dengan masuk kedalam folder mongodb yang terdapat
folder bin klik pada mongo.exe dengan perintah
> db
test
> use databaseEndah
Switched to db databaseEndah
>show dbs
local 0,.078GB
> db.person.insert({"nama":"endahSuk"})
WriteResult({"nInserted" : 1})

