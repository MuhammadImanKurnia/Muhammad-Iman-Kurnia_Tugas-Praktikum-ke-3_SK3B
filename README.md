# Muhammad-Iman-Kurnia_Tugas-Praktikum-ke-3_SK3B

Tugas Praktikum

Nama  : Muhammad Iman Kurnia

NIM   : 09011282328044

Kelas : SK3B

1. Lihat peralatan I/O, character device, yang ada pada system komputer
   
   Jawab :
   
   - untuk melihat peralatan I/O
     ![Screenshot from 2024-09-05 19-25-56](https://github.com/user-attachments/assets/da4f218f-25ba-451c-9ba5-0a445fad0db4)
   - untuk melihat character device
     ![Screenshot from 2024-09-05 19-26-28](https://github.com/user-attachments/assets/a76c8d16-6b72-489d-883f-fa641eb748fe)

2. Buatlah sub direktori januari, februari dan maret sekaligus pada direktori Latihan5
   
   Jawab :
   
   Pertama-tama kita membuat direktori bernama Latihan5 dengan mkdir, kemudian kita masuk ke direktori tersebut dengan cd, lalu didalamnya kita membuat 3 sub direktori yang     di beri nama januari, februari dan maret
   ![Screenshot from 2024-09-05 19-34-33](https://github.com/user-attachments/assets/7a73ee3e-2b03-4337-ad66-9a20253e4e0a)

3. Buatlah file dataku yang berisi nama, nim dan alamat anda pada sub direktori januari dan copy-kan file tersebut ke sub direktori februari dan maret
   
   Jawab :
   
   Pertama-tama kita membuat file dataku.txt dulu di sub direktori januari menggunakan command prompt vim, setelah di enter tampilannya akan seperti ini :
   ![Screenshot from 2024-09-05 19-52-12](https://github.com/user-attachments/assets/8a0e7567-eccf-427e-9863-e762a519b3b3)
   Isi nama, nim dan alamat (agar bisa mengetik di situ ketik dulu huruf i). Untuk keluar dari tampilan tersebut, pencet esc, lalu ketik :wq. Kemudian kita ingin mengcopy       file dataku.txt ke sub direktori februari dan maret. Caranya adalah menggunakan command prompt cp -v, lalu nama file yang ingin kita copy (misalnya dataku.txt), lalu         tujuannya
   ![Screenshot from 2024-09-05 19-56-23](https://github.com/user-attachments/assets/347e481e-3f75-4833-a74c-223922054ef4)

4. Ubahlah ijin akses file dataku pada sub direktori januari sehingga group dan others dapat melakukan write

   Jawab :

   Pertama-tama kita masuk ke sub direktori januari terlebih dahulu, kemudian kita ingin mengubah ijin akses file dataku.txt agar group dan others dapat melakukan write.        Caranya adalah menggunakan command prompt chmod. Caranya yaitu ketik chmod go+w, yang dimana go itu berarti group dan others, w adalah write, itu artinya group dan others    bisa melakukan write file tersebut. Setelah mengetik chmod go+w, kita ketik nama file yang ingin diganti ijin aksesnya (misalnya dataku.txt)
   ![Screenshot from 2024-09-06 10-34-34](https://github.com/user-attachments/assets/99b8e756-c550-4f9e-8068-d26c4f7fc5b0)

5. Ubahlah ijin akses file dataku pada sub direktori februari sehingga user dapat melakukan baik write, read maupun execute, tetapi group dan others hanya bisa read dan         execute

   Jawab :

   Pertama-tama kita masuk ke sub direktori februari terlebih dahulu, lalu kita menggunakan comman prompt chmod. Caranya, ketik chmod u=rwx,g=rx,o=rx. u=rwx berarti user        bisa melakukan read, write dan execute. g=rx berarti group hanya bisa melakukan read dan execute. o=rx berarti others hanya bisa melakukan read dan execute. Kemudian kita    ketik nama filenya
   ![Screenshot from 2024-09-06 11-07-39](https://github.com/user-attachments/assets/6fab3612-2024-455c-8cfd-1017a1922b0b)

6. Ubahlah ijin akses file dataku pada sub direktori maret sehingga semua dapat melakukan write, read dan execute

   Jawab :

   Pertama-tama kita masuk ke sub direktori maret terlebih dahulu, lalu kita menggunakan comman prompt chmod. Caranya, ketik chmod ugo=rwx, yang berarti user, group dan         others bisa melakukan read, write dan execute. Kemudian kita ketik nama filenya
   ![Screenshot from 2024-09-06 11-17-53](https://github.com/user-attachments/assets/9c12c636-eb16-426e-b4e1-3872ed206619)

7. Hapuslah direktori maret

   Jawab :

   
