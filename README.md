# Kelas-3E-Pemrograman

# 🧮 Logika Matematika - Menghitung Luas dan Keliling Lingkaran

## 📝 **Deskripsi Masalah**
Seorang siswa ingin menghitung luas dan keliling sebuah lingkaran berdasarkan jari-jari yang diketahui. Program akan menerima nilai jari-jari lingkaran sebagai input, kemudian menghitung luas dan keliling lingkaran menggunakan rumus yang telah ditentukan.

Masalah ini dapat digunakan untuk menerapkan operasi matematika dalam sebuah program. Program akan menerima nilai jari-jari lingkaran, kemudian menghitung luas dan keliling berdasarkan nilai tersebut. Hasil perhitungan akan ditampilkan sebagai output.

## 📥 **Input-Proses-Output**
**Input:** Nilai jari-jari lingkaran.

**Proses:** Program menghitung luas dengan rumus `Luas = π × r × r` dan menghitung keliling dengan rumus `Keliling = 2 × π × r`.

**Output:** Nilai luas dan keliling lingkaran.



### 💻 **Pseudocode**

```text
INPUT r

Luas ← π × r × r
Keliling ← 2 × π × r

OUTPUT Luas
OUTPUT Keliling
```

## 📊 **Flowchart**

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
    A([START]) --> B[/INPUT jari-jari r/]
    B --> C[Luas = π × r × r]
    C --> D[Keliling = 2 × π × r]
    D --> E[/OUTPUT<br/>Luas dan Keliling/]
    E --> F([END])

    style A fill:#dbeafe,stroke:#2563eb,stroke-width:2px,color:#1e3a8a
    style B fill:#dcfce7,stroke:#16a34a,stroke-width:2px,color:#14532d
    style C fill:#fef3c7,stroke:#d97706,stroke-width:2px,color:#78350f
    style D fill:#fef3c7,stroke:#d97706,stroke-width:2px,color:#78350f
    style E fill:#e0e7ff,stroke:#4f46e5,stroke-width:2px,color:#312e81
    style F fill:#dbeafe,stroke:#2563eb,stroke-width:2px,color:#1e3a8a
```

## 🧪 **Test Case**

| Test Case | Input Jari-jari | Kondisi | Hasil yang Diharapkan |
|---|---:|---|---|
| 1 | 7 cm | r = 7 | Luas = 154 cm², Keliling = 44 cm |
| 2 | 14 cm | r = 14 | Luas = 616 cm², Keliling = 88 cm |

## 🐍 **Implementasi Python**

Implementasi program dibuat menggunakan Python dan dijalankan melalui Visual Studio Code.

Source code dapat dilihat pada **[main.py](main.py)**.

## 📸 **Hasil Pengujian**

Program telah berhasil diuji menggunakan dua nilai jari-jari, yaitu 7 cm dan 14 cm sesuai dengan test case. Hasil perhitungan luas dan keliling sesuai dengan nilai yang telah ditentukan.

<img width="346" height="87" alt="Tangkapan Layar 2026-09-03 pukul 14 06 55" src="https://github.com/user-attachments/assets/61091f81-48fb-4b4e-8429-1e32468fa1f1" />


<img width="369" height="87" alt="Tangkapan Layar 2026-09-03 pukul 14 07 56" src="https://github.com/user-attachments/assets/b9b00f11-6c9e-4d17-a0ae-acfbc21f235a" />

