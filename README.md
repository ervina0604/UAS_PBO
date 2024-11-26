
# 📚 **Aplikasi dengan Java Persistence API (JPA)**  


Langkah-langkah berikut mencakup pembuatan database hingga penerapan fitur aplikasi.

---

## **1. Buat Database dan Tabel Mahasiswa dan Login di PostgreSQL**  

![Screenshot 2024-11-26 140818](https://github.com/user-attachments/assets/27f1e9a6-75ac-4256-b888-728a6c8ed541)

---

## **2. Buat Frame Gui dan button**
![Screenshot 2024-11-26 140847](https://github.com/user-attachments/assets/5575066a-e70e-44dc-b499-c69a5b5dbea9)


![Screenshot 2024-11-26 141039](https://github.com/user-attachments/assets/33e2ba3b-185d-4ed3-804e-254f691160fb)


![Screenshot 2024-11-26 141028](https://github.com/user-attachments/assets/c4f07b99-caf2-4d49-882b-e81877b921b5)


--- 


## **3. Buat Button CRUD **
    
- **Create**
	source code:
 ![Screenshot 2024-11-26 141143](https://github.com/user-attachments/assets/e12820f9-bc04-42f3-a42b-9c2d905f21e3)


tampilan berhasil:

![Screenshot 2024-11-26 141846](https://github.com/user-attachments/assets/ce5677aa-9531-4e5e-8b95-da8f611edc47)


- **Update**
	source code:
![Screenshot 2024-11-26 141156](https://github.com/user-attachments/assets/72a2e38a-ca52-43d5-9747-394dae47c7f8)


tampilan berhasil:

![Screenshot 2024-11-26 141904](https://github.com/user-attachments/assets/d2e328c9-5d99-4d34-b45f-8993276ca501)



- **Delete**
	source code:
![Screenshot 2024-11-26 141208](https://github.com/user-attachments/assets/8a6bd2a3-89b3-4ce6-8201-6a5f9dcf9099)


tampilan berhasil:

![Screenshot 2024-11-26 141922](https://github.com/user-attachments/assets/012434e5-b2ac-4126-8da1-c93a93b8eb77)


 source code tampil dan bersih:

![Screenshot 2024-11-26 142915](https://github.com/user-attachments/assets/660719cf-35db-4b08-92b8-550dfdfcc42e)




## **4. Buat Persistence Unit**  
 
1. **Buat Entity Classes dari Database**  
   - Klik kanan proyek → pilih **New > Entity Classes from Database**.  
2. **Pilih Koneksi Database**  
   - Pilih atau tambahkan koneksi database PostgreSQL baru.  
3. **Pilih Tabel yang Dibutuhkan**  
   - Geser tabel yang ingin digunakan ke kolom kanan.  
4. **Klik Finish**  
   - Persistence Unit dan entitas akan dibuat secara otomatis.

![Screenshot 2024-11-26 142935](https://github.com/user-attachments/assets/257d2d10-80ef-47a9-a11d-b006925f25cb)


* gambar hasil persistence unit di package

![Screenshot 2024-11-26 141429](https://github.com/user-attachments/assets/be65091e-33a4-4dc7-9552-34017b298217)


---

## **4. Buat Sign-Up**  
source code :


![Screenshot 2024-11-26 141505](https://github.com/user-attachments/assets/2102be2b-373a-404a-8621-64a1916ed727)


### - Validasi Password  
Tambahkan logika untuk memastikan password memenuhi kriteria keamanan:  
- Panjang minimal 8 karakter.  


![Screenshot 2024-11-26 141452](https://github.com/user-attachments/assets/514d213b-d665-428e-8b6b-a82187075a1c)


tampilan validasi password:

![Screenshot 2024-11-26 142509](https://github.com/user-attachments/assets/42d0d580-9a99-4dfb-8838-743e8d265632)


tampilan berhasil signup:

![Screenshot 2024-11-26 142327](https://github.com/user-attachments/assets/b47a7cbe-98cd-4e66-b2dc-be10ef6e1821)


tampilan berhasil login:

![Screenshot 2024-11-26 142350](https://github.com/user-attachments/assets/b360c757-f981-42a7-85c6-bdf98c603a7a)




---


## **5. Buat Upload CSV**  

### a. Siapkan File CSV  
Buat file CSV yang berisi data yang ingin diunggah ke database.  

source code :
![Screenshot 2024-11-26 141613](https://github.com/user-attachments/assets/1c76fcf9-7317-47fc-a954-1635c2d93fa1)


tampilan berhasil:

![Screenshot 2024-11-26 141949](https://github.com/user-attachments/assets/aabce93e-44ed-4e64-b684-8abc50126040)


---

## **6. Buat Report**  

### a. Buat Template Laporan  
Buat design jrxml dan sambungkan ke database untuk menampilkan data sesuai kebutuhan.  
![Screenshot 2024-11-26 141655](https://github.com/user-attachments/assets/09709276-eb86-4af0-b34b-adf60af4fe8e)


source code :  

![Screenshot 2024-11-26 141229](https://github.com/user-attachments/assets/a78f46ad-4553-4af4-88f2-ffa975199b5f)


tampilan berhasil:

![Screenshot 2024-11-26 142007](https://github.com/user-attachments/assets/7ec90ca2-329b-4bff-973c-210ca66b03ca)


---


### 🚀 Selamat Belajar dan Selamat Menerapkan JPA  dalam Pengembangan Aplikasi! 💻

--- 
