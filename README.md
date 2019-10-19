<<<<<<< HEAD
# Tugas1

## Mengenal VCS (Version Control System)
   
    VCS atau Version Control System adalah sebuah infrastruktur yang dapat 
mendukung  perkembangan software secara kolaboreatif. Setiap anggota yang 
berada di dalam sebuah tim pengembangan software dapat menulis kode 
programnya masing-masing kemudian digabungkan ke server yang sudah memiliki
VCS yang digunakan
    
    Selain mengandalkan konkurensi yng dapat mempercepat pengembangan sofware,
VCS juga mempunyai kemampuan untuk kembali ke software sebelumnya jika 
terjadi suatu bencana terhadap bersu software yang sedang dikembangkan saat ini.
Kemampuan ini disebut reversibility. Selain itu, dengan menggunakan VCS setiap
perubahan pada software seperti add file atau edit isi file dapat dipantau
bagian manay yang diubah dan siapa yang mengubah. Sehingga pengerjaan software
akan lebih transparan dan terukur.

    Berikut adalah daftar VCS yang perlu di kenal sebagai programmer:
1. Bazaar
2. Subversion (SVN)
3. Mercurial
4. CVS
5. RCS
6. Perforce
7. ClearCase
8. GNU Arch
9. GNU CSSC
10. Git


### Langkah langkah menggunakan Git

A. Opsi 1 - Install GIT di Windows

	1.Buka web dan download GIT di windows
	2.Setelah selesai download, instal dan ikuti semua instruksi hingga selesai
	3.Jalankan perintah berikut di teminal
`git config --global user.name "Ario Teduh"`
`git config --global user.email "ArioTeduh@yaemail.com"`

 
B. Menggunakan git

	1.Membuat/Mengatur/Mengambil repository
		git init #Run di GIT untuk mengubah direktori menjadi repository
		git clone /path/to/local/repository #untuk mengambil repository lokal
		git clone user.name@host:/path/to/remote/repository #Untuk memeriksa repository tersimpan
	2.Perintah ADD dan COMMIT
		git add <file_name>
		git commite -m "Tambahkan catatan untuk commit anda"
	3. Mengirim perubahan
		anda bisa menggunakan perintah push setelah git push original master dijalankan dari direktori kerja
		git remote add origin <server>
	4. Branches
		git checkout -b feature_n * #Feature_n adalah nama branch-nya
		git checkout master
		git checkout -h feature_n
		git push origin feature_n
	5. Update & Merging #update dan menggabungkan branch lain ke yg sudah aktif
		git merge feature_n
		git add <nama_file>
		git diff <nama _sumber_branch> <nama_target_branch>
	6. Tagging
		git tag 1.1.0 1c2d2d56fa
	7. Log
		git log --author =Ario
		git log --pretty=oneline
		git log --name-status
	Mengganti perubahan di lokal
		git checkout -- <filename>
	Jika perubahan/commit di drop dan master branch lokal dibutuhkan untuk menunjukan history terakhir server
		git fetch origin
		git reset --hard origin/master

=======
# Tugas 2

## Praktik IDLE Python Untuk Membuat Konversi Nilai Variable

Langkah-langkah membuat program konversi nilai variable;

	1. Buke IDLE python
	2. Masukan Script 
		Bentuk dari script nya adalah;
		a=input("masukan nilai a=:")
		b=input:"masukan nilai b=:")
		#Disini nilai a dan b adalah input
		print=("variable a=",a)
		print=("variable b=",b)
		#sampai sini adalah proses program
		print("hasil penggabungan {0}&{1}=%s". format(a,b)%(a+b))
		#Outputnya adalah penggabungan dari dua variabel a dan b
		
		
		#Konversi nilai variabel
		a=int(a)
		b=int(b)
		print("hasil penjumlahan {0}+{1}=%d". format(a,b)%(a+b))
		print{"hasil pembagian {0}+{1}=%f". format(a,b)%(a/b))
		#Didapat disini adalah script penjumlahan dan pembagian
	3. Lalu play script tersebut kemudian akan muncul Python.Shell	
	4. Lalu kita akan diminta untuk memasukan variabel contoh a=10,b=20
	5. Setelah kita memasukan variabel, output dari script kita tadi akan terlihat

Sekian adalah langkah-langkah untuk konversi nilai variable




 
