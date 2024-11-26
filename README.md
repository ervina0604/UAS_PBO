
# 📚 **Aplikasi dengan Java Persistence API (JPA)**  


Langkah-langkah berikut mencakup pembuatan database hingga penerapan fitur aplikasi.

---

## **1. Buat Database dan Tabel Mahasiswa dan Login di PostgreSQL**  

![image](https://github.com/user-attachments/assets/f164d60c-a92e-405f-a01c-a0388171d6aa)
---

## **2. Buat Frame Gui dan button**
![image](https://github.com/user-attachments/assets/2e9b88c7-5454-4360-a8f3-7fc822673053)

![image](https://github.com/user-attachments/assets/c2144584-1ba8-486b-b01a-c8086e48d013)

![image](https://github.com/user-attachments/assets/25d3cabc-1f3b-45b7-831c-b78343bf05e8)

--- 


## **3. Buat Button CRUD **
    
- **Create**
	source code:
 ![image](https://github.com/user-attachments/assets/e846f9e1-3659-49c2-924e-7e886aee13c0)

tampilan berhasil:
![image](https://github.com/user-attachments/assets/f16f7f5c-c1a7-4e8b-a279-5b772db89a8b)


- **Update**
	source code:
 ![image](https://github.com/user-attachments/assets/abffd009-cbcf-4661-9b3f-5bf44c2961e2)

tampilan berhasil:
![image](https://github.com/user-attachments/assets/af7d27a5-9de4-4ac5-b23b-f5b8615c8963)


- **Delete**
	source code:
![image](https://github.com/user-attachments/assets/6901fded-a1d0-4dfb-b044-e319eceb6bb0)

tampilan berhasil:
![image](https://github.com/user-attachments/assets/cbfa5ba9-3c80-45e8-8b36-ad2cf734f77e)

 source code tampil dan bersih:
 ![image](https://github.com/user-attachments/assets/0c6498b7-4eea-4dd0-9cb7-aa3c76772ce4)



## **4. Buat Persistence Unit**  
 
1. **Buat Entity Classes dari Database**  
   - Klik kanan proyek → pilih **New > Entity Classes from Database**.  
2. **Pilih Koneksi Database**  
   - Pilih atau tambahkan koneksi database PostgreSQL baru.  
3. **Pilih Tabel yang Dibutuhkan**  
   - Geser tabel yang ingin digunakan ke kolom kanan.  
4. **Klik Finish**  
   - Persistence Unit dan entitas akan dibuat secara otomatis.
![image](https://github.com/user-attachments/assets/89dbebc4-088f-4b79-9179-1b84b88cfd82)

* gambar hasil persistence unit di package
 ![image](https://github.com/user-attachments/assets/679d630e-f133-4153-96da-2717387606d1)

---

## **4. Buat Sign-Up**  
source code :

![image](https://github.com/user-attachments/assets/ded6e61f-bb9e-4239-942a-364b5902a7cf)

### - Validasi Password  
Tambahkan logika untuk memastikan password memenuhi kriteria keamanan:  
- Panjang minimal 8 karakter.  
![image](https://github.com/user-attachments/assets/e9f4289b-6d08-4e1c-b8a7-81f2b0a0b865)

tampilan validasi password:
![image](https://github.com/user-attachments/assets/6e8694d3-380b-41d3-aa93-2e8433d6d10d)

tampilan berhasil signup:
![image](https://github.com/user-attachments/assets/4f89cdee-fbf8-4316-aabd-595c61d5b838)

tampilan berhasil login:
![image](https://github.com/user-attachments/assets/d889202a-8f21-4d40-b114-928596a02030)



---


## **5. Buat Upload CSV**  

### a. Siapkan File CSV  
Buat file CSV yang berisi data yang ingin diunggah ke database.  

source code :
![image](https://github.com/user-attachments/assets/ae02e24f-b8c1-499b-81b8-bbc724982372)

tampilan berhasil:
![image](https://github.com/user-attachments/assets/aecbf1b0-ab5e-4ae9-bda8-23ac6ca74c1c)

---

## **6. Buat Report**  

### a. Buat Template Laporan  
Buat design jrxml dan sambungkan ke database untuk menampilkan data sesuai kebutuhan.  
![image](https://github.com/user-attachments/assets/20e26c35-e121-4019-b340-46d3ebb636ab)

source code :  
![image](https://github.com/user-attachments/assets/4d1ffe37-12fe-4b49-87fa-6c64a748f2b0)

tampilan berhasil:
![image](https://github.com/user-attachments/assets/43e02fa6-ea2f-493e-89af-f4a26674cf0d)

---


### 🚀 Selamat Belajar dan Selamat Menerapkan JPA  dalam Pengembangan Aplikasi! 💻

--- 
