# 🤖 Tugas Mata Kuliah Kecerdasan Buatan (AI-TE01)

<p align="center">
  <img src="https://cdn.pixabay.com/animation/2022/08/06/11/57/11-57-26-645_512.gif" alt="AI Project Banner" width="460">
</p>

<p align="center">
  <b>Koleksi Tugas & Implementasi Kecerdasan Buatan (Artificial Intelligence)</b><br>
  Program Studi S1 Teknik Elektro — Universitas Telkom
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Mata%20Kuliah-Kecerdasan%20Buatan-blue.svg" alt="Course">
  <img src="https://img.shields.io/badge/Kelas-AI--TE01-orange.svg" alt="Class">
  <img src="https://img.shields.io/badge/Bahasa-C%2B%2B%20%7C%20Python%20%7C%20Java-brightgreen.svg" alt="Language">
</p>

---

## 👨‍🎓 Identitas Mahasiswa

* **Nama Mahasiswa** : Fathi Arasy
* **Program Studi**  : S1 Teknik Elektro
* **Mata Kuliah**    : Kecerdasan Buatan (Artificial Intelligence)
* **Kode Kelas**     : AI-TE01

---

## 📌 Isi Repositori Tugas

Repositori ini mencakup 2 topik utama mata kuliah Kecerdasan Buatan:

### 1. 🔍 Search Algorithms (`Search_Algorithm/`)
Implementasi lengkap 8 algoritma pencarian klasik:
* **Uninformed Search**: Linear Search, Binary Search, BFS, DFS, UCS, dan IDDFS.
* **Informed Search**: A* Search dan Dijkstra's Algorithm.
* **Bahasa**: Python, C++, Java, JavaScript, Rust, C#, Swift, R.

### 2. 🩺 Sistem Pakar Diagnosis Penyakit Jantung (`Expert-System-Implementation-main/`)
Sistem pakar medis (*Medical Expert System*) interaktif berbasis bahasa C++ untuk mendiagnosis penyakit kardiovaskular dan merekomendasikan terapi pengobatan:
* **Backward Chaining**: Menentukan diagnosis penyakit jantung berdasarkan inferensi gejala klinis pasien (Rule base).
* **Forward Chaining**: Menentukan rekomendasi terapi obat & tindakan medis berdasarkan hasil diagnosis yang terkonfirmasi.
* **Bahasa**: C++ (Standalone Native Executable).

---

## 📂 Struktur Direktori Proyek

```text
AI-TE01/
│
├── Search_Algorithm/                       # Proyek 1: Algoritma Pencarian
│   ├── A Search/                           # A* Search
│   ├── Binary_Search/                      # Binary Search
│   ├── Breadth_First_Search/               # Breadth-First Search (BFS)
│   ├── Depth_First_Search/                 # Depth-First Search (DFS)
│   ├── Dijkstra's_Algorithm/               # Dijkstra's Algorithm
│   ├── Iterative Deepening DFS Algorithm/  # IDDFS
│   ├── Linear_Search/                      # Linear Search
│   ├── Uniform_Cost_Search/                # Uniform Cost Search (UCS)
│   ├── run_all.py                          # Demo runner seluruh algoritma
│   └── README.md                           # Panduan teknis Search Algorithms
│
├── Expert-System-Implementation-main/      # Proyek 2: Sistem Pakar (Expert System)
│   ├── Project1-SubmittedFiles/
│   │   ├── Project1-A05071238.cpp          # Kode utama program (Main driver)
│   │   ├── knowledge_base-...h             # Basis pengetahuan gejala & diagnosis
│   │   ├── rules-...h                      # Aturan inferensi (Backward Chaining)
│   │   ├── forward_knowledge_base-...h     # Basis pengetahuan terapi & obat
│   │   ├── forward_rules-...h              # Aturan rekomendasi (Forward Chaining)
│   │   ├── expert_system.exe               # File binary mandiri (Standalone executable)
│   │   └── Project-1-A05071238-Bigyan.pdf  # Laporan & dokumentasi proyek
│   └── README.md
│
└── README.md                               # Laporan & dokumentasi utama repositori
```

---

## 🚀 Panduan Menjalankan Program (How to Run)

### A. Menjalankan Sistem Pakar (Expert System)
Masuk ke direktori file sistem pakar dan jalankan program eksekusinya:

```bash
cd Expert-System-Implementation-main/Project1-SubmittedFiles
./expert_system.exe
```

*(Atau kompilasi ulang menggunakan compiler C++):*
```bash
g++ -std=c++17 -static Project1-A05071238.cpp -o expert_system.exe
./expert_system.exe
```

Program akan memandu proses diagnosis secara interaktif dalam Bahasa Indonesia dengan pertanyaan `Y` (Ya) atau `T` (Tidak).

---

### B. Menjalankan Algoritma Pencarian (Search Algorithms)
Jalankan script demo python dari root:

```bash
python Search_Algorithm/run_all.py
```

---

## 📄 Lisensi
Seluruh kode pada repositori ini disusun untuk keperluan akademik perkuliahan di bawah lisensi [Apache License 2.0](Search_Algorithm/LICENSE).
