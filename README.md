# Rangkuman Git (Version Control System)

Git atau Version Control System adalah merupakan tools yang digunakan untuk kolaborasi dalam sebuah project antar divisi (role) atau dengan orang lain dengan mudah dan tersetruktu.

Pada tanggal 13 November belajar tentang git yaitu dengan perintah yang dipelajari adalah:

## Repo ini menggunakan ssh 
ssh untuk git adalah agar saat mengakases repository dapat mengotentikasi dan mengamankan koneksi saat Anda mengakses repository.

## Kode Perintah Git

Git Init = Membuat atau meng inisialisasi sebuah repository git untuk di local

```bash
  git init
```

Git clone = Untuk Mengunduh (cloning) repository dari remote repository seperti dari Github, Gitlab, dan Bitbucket ke local.

```bash
  git clone <URL>
```

Git Remote = Mengelola remote repository yang digunakan.

```bash
  git remote add origin <URL-repo> # Menambahkan remote repository
  git remote -v                    # Melihat daftar remote repository
  git remote remove origin         # Menghapus remote repository
```

Git status = Menampilkan status file dari yang belum di tambahkan, update atau melihat perubahan pada file project.

```bash
  git status
```

Git add = Menambahkan keseluruhan semua file di dalam project ke local git.

```bash
  git add .
```

Git commit = Menyimpan perubahan di repository dengan pesan deskripsi.

```bash
  git commit -m ""
```

Git log = Melihat riwayat commit di repository..

```bash
  git log 
  git log --online  #melihat secara lebih singkat dan sekilas
```

Git branch = Menampilkan dan untuk melihat keseluruhan branch yang dimiliki.

```bash
  git branch
  git branch <nama-branch>         # Membuat branch baru
  git branch -d <nama-branch>      # Menghapus branch
```

Git Checkout = Berpindah ke branch atau commit tertentu atau yang diinginkan.

```bash
  git checkout <nama-branch> 
```

Git Merge = Menggabungkan branch saat ini dengan branch yang tersedia.

```bash
  git merge <nama-branch> 
```

Git Push = Mengirim perubahan dari branch lokal ke remote repository.

```bash
  git push origin <nama-branch>
```

Git Pull = Mengambil serta memperbarui perubahan dari remote repository dan menggabungkannya ke branch atau repository lokal.

```bash
  git pull origin <nama-branch>
```

Git Reset = Mengembalikan repository ke kondisi sebelumnya.

```bash
  git reset --hard <hash-commit/code-commit>
```






