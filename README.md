Oke, kamu sudah **ubah README.md di lokal**, dan sekarang ingin **mengupdate yang di GitHub**.
Berarti kamu hanya perlu melakukan **add → commit → push**.

Berikut langkah lengkapnya:

---

# ✅ **1. Pastikan kamu ada di folder project**

Misalnya:

```
cd C:\Users\nicho\Documents\myProject
```

---

# ✅ **2. Tambahkan perubahan ke staging**

```
git add README.md
```

Atau kalau mau semua file:

```
git add .
```

---

# ✅ **3. Commit perubahan**

```
git commit -m "Update README.md"
```

---

# ✅ **4. Push ke GitHub**

Sekarang tergantung branch kamu.

### Jika branch kamu **master**:

```
git push origin master
```

### Jika branch kamu **main**:

```
git push origin main
```

---

# ❗ Kalau kamu lupa kamu pakai branch apa

Cek dulu:

```
git branch
```

Akan muncul misalnya:

```
* master
```

Atau

```
* main
```

Itu branch yang harus kamu push.

---

# 🟦 Contoh alur paling umum di Windows Git

```
git add .
git commit -m "Update README.md"
git push origin master
```

---

# 🔍 Mau saya cek?

Kalau masih error, kirim screenshot atau hasil dari:

```
git branch
git remote -v
git status
```

Nanti aku bantu sampai berhasil.

