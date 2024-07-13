### Project Based Internship as a Data Engineer - ID/X Partner x Rakamin Academy 

## Case Study

Salah satu client dari ID/X Partners yang bergerak di bidang e-commerce memiliki kebutuhan untuk membuat sebuah Data Warehouse yang berasal dari beberapa tabel dari database sumber.
Data Warehouse terdiri dari satu tabel Fact dan beberapa tabel Dimension. Sebagai Data Engineer, terdapat beberapa langkah yang dilakukan pada project ini :
1. Melakukan Import/Restore Database Staging.
2. Membuat sebuah Database bernama DWH_Project, serta membuat Tabel Fact dan Dimension dari tabel yang ada di database Staging.
3. Membuat Job ETL di aplikasi talend untuk memindahkan data dari Staging ke Data Warehouse. Khusus untuk Tabel DimCustomer, lakukan transformasi data dengan merubah data
dari kolom FirstName dan LastName menjadi huruf kapital semua, lalu gabungkan kedua kolom tersebut menjadi satu kolom yang bernama CustomerName.
4. Membuat Store Procedure (SP) untuk menampilkan summary sales order berdasarkan status pengiriman.

<h2 align="center">Steps in Projects</h2>
1. Melakukan Import/Restore Database Staging : Restore database menggunakan file backup Staging.bak
2. Membuat sebuah Database bernama DWH_Project, serta membuat Tabel Fact dan Dimension dari tabel yang ada di database Staging 
3. Membuat Job ETL di aplikasi talend untuk memindahkan data dari Staging ke Data Warehouse
4. Membuat Store Procedure untuk menampilkan summary sales order berdasarkan status pengiriman.
