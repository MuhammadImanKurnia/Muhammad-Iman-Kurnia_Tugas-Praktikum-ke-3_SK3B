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

   Pertama-tama kita masuk ke direktori Latihan5 dulu. Untuk menghapus direktori maret, kita bisa menggunakan command prompt rm -r, ini akan menghapus direktori tersebut        beserta isi didalamnya. Caranya, kita ketik rm -r, kemudian kita ketik nama sub direktori yang ingin kita hapus
   ![Screenshot from 2024-09-06 11-38-13](https://github.com/user-attachments/assets/711a3463-1e1a-4acd-8b06-afe94ab22ebe)

8. Ubahlah kepemilikan sub direktori februari sehingga user dan group hanya read, dan cobalah untuk membuat membuat direktori baru _haha_ pada sub direktori februari

   Jawab :

     ![Screenshot from 2024-09-07 14-03-40](https://github.com/user-attachments/assets/23fdedb4-a828-4b37-9d4d-bafe94d9fec1)

     ![Screenshot from 2024-09-07 14-04-06](https://github.com/user-attachments/assets/eac5a809-284d-477a-907b-aa75d88445c9)

9. Modifikasi umask dari file dataku pada sub direktori januari menjadi 027 dan berapakah nilai defaultnya?

   Jawab :

   umask 027 adalah command prompt yang membuat file baru memiliki izin akses default 640 (rw-r-----) dan direktori baru akan memilki izin default 750 (rwxr-x---). Karena       kita sudah membuat file dataku.txt sebelumnya, kita bisa menggunakan command prompt chmod untuk mengubah izinnya secara manual. Caranya kita ketik chmod 640 dataku.txt,      ini akan membuat file dataku.txt memiliki izin akses 640 (rw-r-----)
   ![Screenshot from 2024-09-06 12-47-22](https://github.com/user-attachments/assets/e68a5fd2-8415-4282-8e8d-726c380eb5d1)
   Untuk pertanyaan berapa nilai defaultnya, nilai default dari umask 027 adalah 640 (rw-r-----) untuk file baru dan 750 (rwxr-x---) untuk direktori baru

10. Buatlah link dari file dataku ke file dataku.ini dan file dataku.juga dan dengan perintah list perhatikan berapa link yang terjadi

    Jawab :

    Untuk membuat link dari file dataku.txt ke file dataku.ini dan file dataku.juga, kita bisa menggunakan command prompt ln -s
    ![Screenshot from 2024-09-06 13-02-06](https://github.com/user-attachments/assets/6be84b7f-88cb-49ca-b9b6-57a5373b8bb0)
    Lalu dengan command prompt ls -l, kita bisa melihat berapa link yang terjadi
    ![Screenshot from 2024-09-06 13-05-57](https://github.com/user-attachments/assets/4199a3ec-2a08-44ab-ad24-b613ff4463cd)
    Jika kita lihat, ada dua link yang terjadi



