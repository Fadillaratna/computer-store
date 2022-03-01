# Sequelize Computer Store


## Membuat Tabel & Relasi dengan SEQUELIZE dengan ketik command sebagai berikut 
### Tabel `product`
sequelize model:create --name product --attributes name:string,price:double,stock:double,image:string

### Tabel `admin`
sequelize model:create --name admin --attributes name:string,username:string,password:string

### Tabel `customer` 
sequelize model:create --name customer --attributes name:string,phone:string,address:string,image:string,username:string,password:string

### Tabel `transaksi`
sequelize model:create --name transaksi --attributes customer_id:integer,waktu:date

### Tabel `detail_transaksi`
equelize model:create --name detail_transaksi --attributes transaksi_id:integer,product_id:integer,price:double,qty:double


## Hasilnya adalah database dengan relasi seperti berikut

![image](https://user-images.githubusercontent.com/87308406/156081931-56acf1c6-d29b-4f9d-98a2-928c3ebeb162.png)
