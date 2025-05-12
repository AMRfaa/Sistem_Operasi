1.	Membuat dan mengelola file
    
        a. Membuat directory 
           • mkdir Modul4
        b. Membuat file
           • touch file1.txt
        c. Membuat folder
           • mkdir folderbaru
        d. Mengcopy paste file 
           • cp file1.txt folderbaru
           • cd folderbaru
        e. Menghapus file dan folder
           • rm filesampah.txt
           • rmdir foldersampah
        f. Mengubah nama file
           • mv file1.txt file2.txt
        g. Memindahkan file di dalam folder yang sama
           • mv file2.txt folderbaru
        h. Memindahkan file di luar folder yang ingin dipindahkan
           • mv file2.txt /home/amrxfaa/Modul4
       
3.	Mengatur izin 
    
        a. Mengubah dengan Symbol
           • chmod u+x file2.txt
             Menambahkan izin eksekusi (x) ke pemilik file (user/u).
           • chmod g+x file2.txt
             Menambahkan izin eksekusi ke grup (group/g).
           • chmod o+w file2.txt
             Menambahkan izin tulis (write) ke others (pengguna lain).
           • chmod ug-x file2.txt
             Menghapus izin execute (x) dari user (u) dan group (g).
        b. Mengubah dengan Oktal
           • chmod 755 file2.txt
           • chmod 000 file2.txt

4.	Mengubah kepemilikan
   
        a. Membuat User
           • sudo adduser jamal
        b. Mengubah kepemilikan
           • ls -l
           • sudo chown jamal file2.txt
           • sudo chown jamal folderbaru
        c. Mengubah kepemilikan secara menyeluruh dalam satu folder
           • sudo chown -R jamal:jamal Modul4
            


      

     

        


