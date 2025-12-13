# Desain Analisis Algoritma  
## Trip Planner dengan Kahn vs DFS 

Repositori ini berisi implementasi dan analisis **perbandingan algoritma Topological Sort** menggunakan  
**Kahn’s Algorithm** dan **Depth First Search (DFS)** pada kasus **Trip Planner**.

Studi kasus difokuskan pada **perencanaan perjalanan dengan beberapa destinasi per hari**, yang secara alami
membentuk struktur **Layered Directed Acyclic Graph (Layered DAG)**.

---

## 📌 Studi Kasus
Trip planner disusun berdasarkan:
- Beberapa tempat wisata dikunjungi **dalam satu hari**
- Urutan antar hari **harus terjaga**
- Urutan dalam satu hari **fleksibel**

Struktur ini **bukan linear murni** dan **bukan dense DAG**, melainkan **Layered DAG**, sehingga cocok
untuk menguji performa algoritma topological sort dalam kondisi realistis.
