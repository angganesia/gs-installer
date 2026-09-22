# 🚀 GS (Git Auto Sync) Installer

**GS** adalah skrip otomatisasi Shell (Bash & Zsh) sederhana namun powerful untuk mempercepat alur kerja Git kamu. Skrip ini secara otomatis melakukan `git add`, membuat pesan commit berbasis timestamp/status, `git pull --rebase`, dan `git push` hanya dengan satu perintah ringkas.

---

## 📦 Fitur Utama

- **Otomatisasi Git Routine:** Eksekusi `git add .`, `git commit`, `git pull --rebase`, dan `git push` sekaligus.
- **Auto-Generated Commit Message:** Jika pesan commit dikosongkan, skrip akan membuat pesan commit otomatis berdasarkan berkas yang diubah beserta stempel waktu (*timestamp*).
- **Menu Bantuan Terintegrasi:** Mendukung opsi `--help`, `-h`, `-help`, atau `help`.

---

## 🛠️ Cara Instalasi

Jalankan skrip `installer` melalui terminal kamu:

```
bash installer
```
or 
```
chmod +x installer && ./installer
```