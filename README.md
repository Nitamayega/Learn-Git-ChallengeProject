# 🚀 Challenge Project

Repositori ini digunakan untuk latihan Git dasar dan manajemen branch.

---

## 🎯 Langkah Inisialisasi Proyek

### 1. Buat Folder Proyek
```bash
mkdir ChallengeProject
cd ChallengeProject
```
![alt text](assets/1.png)
### 2. Buka Folder di Visual Studio Code
```bash
code .
```
![alt text](assets/2.png)

### 3. Buat File README.md
```bash
# Challenge Project

Ini adalah repositori latihan Git.
```
![alt text](assets/3.png)

### 4. Inisialisasi Git dan Commit Awal
```bash
git init
git add .
git commit -m "init: project initialized"
```
![alt text](assets/4.png)

### 5. Buat New Branch
```bash
git branch ParentGe
```
![alt text](assets/5.png)

### 6. Setup Remot Repository
- Bikin repo kosong di GitHub (tanpa README)
![alt text](assets/6-1.png)
- Salin URL GitHub
![alt text](assets/6-2.png)

### 7. Push ke Branch
```bash
git push origin main
git status -- melihat status perubahan saat ini
```
![alt text](assets/7.png)

## 🔁 Fast-Forward Merge (dengan remote)
### 8. Checkout ParentName dan modifikasi file
![alt text](assets/8.png)

### 9. Lakukan fast-forward merge
![alt text](assets/9.png)

## Three-Way Merge Flow
### 10. Clone repo ke folder baru (simulasi developer lain)
![alt text](assets/10.png)

### 11. Checkout branch ChildName dan ubah README.md
![alt text](assets/11.png)

### 12. Kembali ke repo awal dan buat perubahan juga di main
![alt text](assets/12.png)

### 13.  Buka GitHub → Buat Pull Request dari ChildName ke main
![alt text](assets/13.png)