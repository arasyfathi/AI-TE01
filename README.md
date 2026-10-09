# 🤖 Tugas Mata Kuliah Kecerdasan Buatan (AI-TE01)

<p align="center">
  <img src="https://cdn.pixabay.com/animation/2022/08/06/11/57/11-57-26-645_512.gif" alt="Search Algorithms" width="460">
</p>

<p align="center">
  <b>Implementasi & Analisis Algoritma Pencarian (Search Algorithms)</b><br>
  Program Studi S1 Teknik Elektro — Universitas Telkom
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Mata%20Kuliah-Kecerdasan%20Buatan-blue.svg" alt="Course">
  <img src="https://img.shields.io/badge/Kelas-AI--TE01-orange.svg" alt="Class">
  <img src="https://img.shields.io/badge/Bahasa-Python%20%7C%20C%2B%2B%20%7C%20Java%20%7C%20JS-brightgreen.svg" alt="Language">
</p>

---

## 👨‍🎓 Identitas Mahasiswa

* **Nama Mahasiswa** : Fathi Arasy
* **Program Studi**  : S1 Teknik Elektro
* **Mata Kuliah**    : Kecerdasan Buatan (Artificial Intelligence)
* **Kode Kelas**     : AI-TE01
* **Topik Tugas**    : Search Algorithms & Graph Traversal (Linear, Binary, BFS, DFS, Dijkstra, UCS, A*, IDDFS)

---

## 📌 Deskripsi Tugas

Repositori ini dibuat untuk memenuhi tugas mata kuliah **Kecerdasan Buatan (AI)**. Repositori ini berisi implementasi berbagai algoritma pencarian fundamental dalam ilmu komputer dan kecerdasan buatan, yang terbagi dalam dua kategori utama:
1. **Uninformed Search (Blind Search)**: Linear Search, Binary Search, Breadth-First Search (BFS), Depth-First Search (DFS), Uniform Cost Search (UCS), dan Iterative Deepening DFS (IDDFS).
2. **Informed Search (Heuristic Search)**: A* Search dan Dijkstra's Algorithm (pencarian jalur terpendek berbobot).

Seluruh kode dan algoritma tersimpan rapi di dalam direktori **[`Search_Algorithm/`](Search_Algorithm/)**.

---

## 📂 Struktur Direktori Proyek

```text
AI-TE01/
│
├── Search_Algorithm/                       # Direktori utama implementasi algoritma
│   ├── A Search/                           # Informed Search: Algoritma A* (Heuristik)
│   ├── Binary_Search/                      # Uninformed Search: Binary Search
│   ├── Breadth_First_Search/               # Uninformed Search: BFS (Level-order)
│   ├── Depth_First_Search/                 # Uninformed Search: DFS (Depth-order)
│   ├── Dijkstra's_Algorithm/               # Shortest Path: Dijkstra
│   ├── Iterative Deepening DFS Algorithm/  # Uninformed Search: IDDFS
│   ├── Linear_Search/                      # Uninformed Search: Linear Search
│   ├── Uniform_Cost_Search/                # Uninformed Search: UCS (Cheapest Path)
│   │
│   ├── run_all.py                          # 🔥 Script demonstrasi eksekusi seluruh algoritma
│   └── README.md                           # Dokumentasi teknis mendalam
│
└── README.md                               # Laporan & dokumentasi utama repositori tugas
```

---

## 📊 Matriks Analisis & Kompleksitas Algoritma

| No | Algoritma | Kategori | Time Complexity (Worst) | Space Complexity | Struktur Data |
| :-: | :--- | :--- | :---: | :---: | :--- |
| 1 | **Linear Search** | Array Search | $O(n)$ | $O(1)$ | Array / List |
| 2 | **Binary Search** | Divide & Conquer | $O(\log n)$ | $O(1)$ | Sorted Array |
| 3 | **Breadth-First Search (BFS)** | Uninformed Graph | $O(V + E)$ | $O(V)$ | Queue (FIFO) |
| 4 | **Depth-First Search (DFS)** | Uninformed Graph | $O(V + E)$ | $O(V)$ | Stack (LIFO) / Rekursif |
| 5 | **Dijkstra's Algorithm** | Shortest Path | $O((V + E) \log V)$ | $O(V)$ | Priority Queue (Min-Heap) |
| 6 | **Uniform Cost Search (UCS)** | Uninformed Graph | $O((V + E) \log V)$ | $O(V)$ | Priority Queue (Min-Heap) |
| 7 | **A\* Search** | Informed Heuristic | $O(b^d)$ | $O(b^d)$ | Priority Queue ($f = g + h$) |
| 8 | **IDDFS** | Depth-bounded | $O(b^d)$ | $O(bd)$ | Stack / Recursive Call |

---

## 🚀 Cara Menjalankan Program (Execution Guide)

### 1. Menjalankan Seluruh Algoritma Sekaligus (Demo Interaktif)
Pastikan Python 3 sudah terpasang, lalu jalankan script `run_all.py` dari root proyek:

```bash
python Search_Algorithm/run_all.py
```

*Atau masuk terlebih dahulu ke folder `Search_Algorithm`:*
```bash
cd Search_Algorithm
python run_all.py
```

Script ini akan otomatis menguji dan menampilkan hasil eksekusi dari:
- **Linear Search**: Pencarian target pada list acak
- **Binary Search**: Pencarian target pada list terurut
- **BFS & DFS**: Urutan traversal simpul graf
- **Dijkstra**: Perhitungan bobot jarak terpendek dari simpul awal ke semua simpul
- **UCS**: Pencarian jalur dengan total biaya terkecil menuju node tujuan

---

### 2. Menjalankan Algoritma Individual
Untuk menguji algoritma spesifik per folder:

```bash
# Contoh Binary Search (Python)
python "Search_Algorithm/Binary_Search/binary_search_python.py"

# Contoh BFS (Python)
python "Search_Algorithm/Breadth_First_Search/breadth_first_search_python.py"
```

---

## 📄 Lisensi
Proyek tugas ini disusun untuk keperluan akademik dan dilisensikan di bawah [Apache License 2.0](Search_Algorithm/LICENSE).
