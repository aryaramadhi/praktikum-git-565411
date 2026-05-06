## Tugas 1
<img width="872" height="174" alt="Screenshot 2026-05-06 194215" src="https://github.com/user-attachments/assets/c47bb35d-743b-4178-8309-a748344a60c2" />
# praktikum-git-565411

## Tugas 2
![Branch Protection Rule](branchprotection.png)

## Tugas 3: Konflik & Rebase

### 1. Resolusi Konflik Manual
Saya membuat konflik antara branch `experiment/color-A` dan `experiment/color-B`. 
Konflik diselesaikan secara manual di VS Code dengan memilih warna yang diinginkan.

### 2. Interactive Rebase (Squash)
Saya menggunakan `git rebase -i` untuk merapikan riwayat commit pada branch `feature/dark-mode`. 
Tiga commit kecil digabungkan menjadi satu commit tunggal: `feat: implementasi mode gelap dan transisi yang lembut`.

## Bukti Proses Rebase:
![Proses Rebase](<Screenshot 2026-05-06 213916.png>)

## Tugas 4

# Proyek Praktikum Git Arya Ramadhi

## Deskripsi Project
Proyek ini adalah tugas praktikum untuk mempelajari alur kerja Git profesional, mulai dari manajemen branch hingga teknik rebase.

## Cara Menjalankan
1. Buka link berikut: `git clone [https://github.com/aryaramadhi/praktikum-git-565411]`


## Dokumentasi Perintah Git
* `git checkout -b [nama-branch]`: Membuat branch baru dan langsung berpindah ke sana.
* `git merge [nama-branch]`: Menggabungkan perubahan dari branch lain ke branch aktif.
* `git pull origin [nama-branch]`: Mengambil dan menggabungkan perubahan terbaru dari GitHub ke laptop.
* `git rebase -i HEAD~[jumlah]`: Melakukan interactive rebase untuk merapikan riwayat commit (squash).
* `git push origin [nama-branch] --force`: Memaksa pengiriman commit ke GitHub (digunakan setelah rebase).

## Hasil Tugas
![Tampilan Web](<Screenshot 2026-05-06 222806.png>)

### Dokumentasi Perintah Git (Tugas 4 tambahan)
* `git checkout -b [nama]`: Membuat branch baru dan berpindah ke sana.
* `git merge [nama]`: Menggabungkan branch.
* `git rebase -i`: Merapikan riwayat commit (squash).
* `git push --force`: Mengirim perubahan setelah rebase.