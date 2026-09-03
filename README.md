# Kelas-3E-Pemrograman

# 🧮 Logika Matematika - Menghitung Luas dan Keliling Lingkaran

## 📝 **Deskripsi Masalah**
Seorang siswa ingin menghitung luas dan keliling sebuah lingkaran berdasarkan jari-jari yang diketahui. Program akan menerima nilai jari-jari lingkaran sebagai input, kemudian menghitung luas dan keliling lingkaran menggunakan rumus yang telah ditentukan.

Masalah ini dapat digunakan untuk menerapkan operasi matematika dalam sebuah program. Program akan menerima nilai jari-jari lingkaran, kemudian menghitung luas dan keliling berdasarkan nilai tersebut. Hasil perhitungan akan ditampilkan sebagai output.

## 📥 **Input-Proses-Output**
**Input:** Nilai jari-jari lingkaran.

**Proses:** Program menghitung luas dengan rumus `Luas = π × r × r` dan menghitung keliling dengan rumus `Keliling = 2 × π × r`.

**Output:** Nilai luas dan keliling lingkaran.

```mermaid
%%{init: {
  "themeVariables": {
    "fontSize": "12px"
  },
  "flowchart": {
    "nodeSpacing": 15,
    "rankSpacing": 20,
    "padding": 8
  }
}}%%

flowchart TD
    A([START]) --> B[/INPUT nilai/]
    B --> C{Apakah nilai < 75?}

    C -->|Ya| D[/OUTPUT<br/>"Siswa harus mengikuti<br/>ujian remedial"/]
    C -->|Tidak| E[/OUTPUT<br/>"Siswa tidak perlu mengikuti<br/>ujian remedial"/]

    D --> F([END])
    E --> F

    style A fill:#dbeafe,stroke:#2563eb,stroke-width:2px,color:#1e3a8a
    style B fill:#dcfce7,stroke:#16a34a,stroke-width:2px,color:#14532d
    style C fill:#fef3c7,stroke:#d97706,stroke-width:2px,color:#78350f
    style D fill:#fee2e2,stroke:#dc2626,stroke-width:2px,color:#7f1d1d
    style E fill:#e0e7ff,stroke:#4f46e5,stroke-width:2px,color:#312e81
    style F fill:#dbeafe,stroke:#2563eb,stroke-width:2px,color:#1e3a8a
```
