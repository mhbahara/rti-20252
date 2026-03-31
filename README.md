# Riset Teknologi Informasi — Buku Ajar OBE

> **Applied Experimental Research in Information Systems & Software Engineering**
> Universitas Putra Bangsa (UPB), Kebumen — Fakultas Sains dan Teknologi, Program Studi Teknik Informatika

---

## Tentang Project Ini

Project ini adalah repository pengembangan **buku ajar berbasis OBE** (Outcome-Based Education) untuk mata kuliah *Riset Teknologi Informasi*. Buku ini mengajarkan mahasiswa **cara menjalankan riset eksperimental** di bidang TI dan Software Engineering — bukan sekadar teori metodologi penelitian.

**Paradigma:** Positivist + Pragmatic (Design Science Research)
**Format:** B5 (17.6 cm × 25 cm), 250–350 halaman, 16 bab dalam 4 bagian

---

## Struktur Folder

```
rti-20252/
├── MASTER-ANCHOR.md          # Single source of truth — anti-drift document
├── BOOK-SPEC.md              # Spesifikasi teknis buku
├── BLUEPRINT.md              # Consolidated blueprint 16 bab
├── REFERENCES.md             # Master reference library (APA 7th)
├── PROJECT-TRACKER.md        # Progress tracking semua deliverable
├── README.md                 # ← Anda di sini
│
├── book/                     # Konten buku
│   ├── front-matter/         # Halaman judul, kata pengantar, daftar isi/gambar/tabel
│   ├── bagian-1-foundation/  # Bab 1–4: Foundation of Research Thinking (M1–M4)
│   ├── bagian-2-design/      # Bab 5–7: Research Design & Planning (M5–M7)
│   ├── bagian-3-execution/   # Bab 8–12: Research Execution (M9–M12)
│   ├── bagian-4-analysis/    # Bab 13–16: Analysis & Communication (M13–M16)
│   └── back-matter/          # Daftar pustaka, glosarium, indeks, lampiran
│
├── assets/
│   ├── diagrams/             # Signature model & mindmap diagrams
│   └── figures/              # Supplementary figures
│
├── templates/
│   └── WRITING-TEMPLATE.md   # Template per-bab (copy untuk setiap bab baru)
│
├── worksheets/               # 16 worksheet praktis (1 per bab)
│   ├── ws-01-problem-statement.md
│   ├── ws-02-literature-matrix.md
│   └── ... (ws-03 s/d ws-16)
│
├── rps/                      # RPS (Rencana Pembelajaran Semester) files
│
└── docs/                     # Dokumentasi diskusi
    ├── disscus01.md          # Diskusi v1 — Draft awal RPS
    ├── disscus02.md          # Diskusi v2 — Gap analysis 
    ├── disscus03.md          # Diskusi v3 — Refinement
    └── disscus04.md          # Diskusi v4 — Final consolidation
```

---

## Struktur Buku

| Bagian | Bab | Judul | Fase |
|--------|-----|-------|------|
| **1 — Foundation** | 1 | Research Mindset in IT | Thinking (M1–M4) |
| | 2 | Problem Formulation | |
| | 3 | Literature Gap & Positioning | |
| | 4 | Systematic Literature Review | |
| **2 — Design** | 5 | Research Question & Hypothesis | Designing (M5–M7) |
| | 6 | Research Design Patterns | |
| | 7 | Metrics & Measurement | |
| **3 — Execution** | 8 | Experiment Setup & Toolchain | Executing (M9–M12) |
| | 9 | Data Collection Strategies | |
| | 10 | Validity & Threats | |
| | 11 | Reproducibility & Replication | |
| | 12 | Ethics in IT Research | |
| **4 — Analysis** | 13 | Statistical Thinking for IT | Scientific Thinking (M13–M16) |
| | 14 | Result Interpretation | |
| | 15 | Writing & Presentation | |
| | 16 | Defense & Argumentation | |

---

## Cara Memulai Menulis Bab

1. Baca **MASTER-ANCHOR.md** untuk memahami boundary dan aturan
2. Baca **BLUEPRINT.md** untuk detail konten bab yang akan ditulis
3. Copy **templates/WRITING-TEMPLATE.md** ke folder bab yang sesuai
4. Tulis mengikuti 13-section structure
5. Validasi terhadap **BOOK-SPEC.md** (format & gaya)
6. Cek referensi di **REFERENCES.md**
7. Update **PROJECT-TRACKER.md** setelah selesai

---

## Research Pipeline (Immutable)

```
Problem → Gap → RQ → Hypothesis → Metric → Design → Experiment → Data → Analysis → Conclusion → Defense
```

> Setiap bab harus menjaga konsistensi dengan pipeline ini.

---

## Boundary Rule

| ❌ Bukan Riset TI (Metopen) | ✅ Riset TI (buku ini) |
|------------------------------|------------------------|
| "Jelaskan apa itu riset" | "Show how to run experiment in system/software" |
| Filosofi umum penelitian | Applied experimental research in IT/SE |
| Metodologi generik | Design Science + Experimental SE |

---

*Last updated: Fase 0 — Preparation Complete*