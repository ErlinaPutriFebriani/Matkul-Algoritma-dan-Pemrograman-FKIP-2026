# Laporan Tugas Pertemuan 1 - Algoritma dan Pemrograman

**Nama:** Erlina Putri Febriani  
**NIM:** 2225250136  
**Program Studi:** S1 Pendidikan Matematika | FKIP UNTIRTA  
**Mata Kuliah:** Algoritma dan Pemrograman (2026)  

---

## 1. Deskripsi Masalah
Program ini dibuat untuk menghitung **Volume** dan **Luas Permukaan** dari sebuah bangun ruang Kubus berdasarkan panjang sisi ($s$) yang dimasukkan oleh pengguna. Kasus uji utama menggunakan nilai sisi $s = 10\text{ cm}$.

**Rumus Matematika:**
* **Volume Kubus ($V$):** $s^3 = s \times s \times s$
* **Luas Permukaan Kubus ($L$):** $6s^2 = 6 \times s \times s$

---

## 2. Identifikasi Input - Proses - Output
* **Input:** Panjang sisi kubus ($s$) bertipe desimal (`float`).
* **Proses:**
  * $\text{Volume} = s \times s \times s$
  * $\text{Luas Permukaan} = 6 \times s \times s$
* **Output:** Menampilkan nilai `Volume` dan `Luas Permukaan`.

---

## 3. Pseudocode
```text
ALGORITMA HitungKubus

DEKLARASI:
    VAR s, volume, luas : REAL

ALGORITMA:
    WRITE "Masukkan panjang sisi kubus: "
    READ s

    volume <- s * s * s
    luas <- 6 * s * s

    WRITE "Volume Kubus         = ", volume
    WRITE "Luas Permukaan Kubus = ", luas
END ALGORITMA