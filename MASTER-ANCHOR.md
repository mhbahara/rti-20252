# MASTER ANCHOR — Buku Ajar Riset Teknologi Informasi

> **Dokumen ini adalah referensi utama anti-drift.**
> Baca sebelum menulis setiap bab. Validasi setiap konten terhadap dokumen ini.
> Jika konten tidak lulus validasi → revisi atau buang.

---

## 1. IDENTITAS MATA KULIAH

| Aspek | Nilai |
|-------|-------|
| **Nama Resmi** | Riset Teknologi Informasi |
| **Identitas Akademik** | Applied Experimental Research in Information Systems & Software Engineering |
| **Paradigma** | Positivist + Pragmatic (Design Science) |
| **Level** | KKNI Level 6 (Sarjana) |
| **Prasyarat Logis** | Metodologi Penelitian (Metopen) — sebagai prerequisite konseptual |

---

## 2. TUJUAN UTAMA

> Pembaca mampu **merancang, menjalankan, dan mempertahankan eksperimen berbasis sistem** secara ilmiah.

### Bukan:
- ❌ Metodologi penelitian umum (itu Metopen)
- ❌ Tutorial coding / development
- ❌ Statistik teoritis / inferensial berat
- ❌ Filsafat ilmu mendalam

### Tetapi:
- ✅ Experimental system research
- ✅ Evidence-based engineering
- ✅ Reproducible experiment
- ✅ Applied quantitative research

---

## 3. RESEARCH PIPELINE (WAJIB TIDAK BERUBAH)

```
Problem → Gap → RQ → Hypothesis → Metric → Design →
Experiment → Data → Analysis → Conclusion → Defense
```

Setiap bab harus berada **di dalam pipeline ini**. Jika konten tidak bisa dipetakan ke pipeline → konten tersebut drift.

---

## 4. LEARNING PHASES (4 FASE)

| Fase | Nama | Minggu | Fokus |
|------|------|--------|-------|
| **Phase 1** | THINKING | M1–M4 | Problem → Gap → RQ → Hypothesis |
| **Phase 2** | DESIGNING | M5–M7 | Metric → System → Experiment |
| **Phase 3** | EXECUTING | M9–M12 | Implementation → Experiment → Data |
| **Phase 4** | SCIENTIFIC THINKING | M13–M16 | Analysis → Writing → Defense |

> M8 = UTS (Proposal Defense) — checkpoint, bukan fase baru.

---

## 5. BOUNDARY DENGAN METOPEN

| Prinsip | Metopen | Riset TI |
|---------|---------|----------|
| Fokus | Konsep & desain metodologi | Eksekusi eksperimen sistem |
| Paradigma | Umum (semua jenis) | Positivist + DSR |
| Statistik | Teori & inferensial | Applied & interpretatif |
| Literature | Konsep review | Praktik search & gap extraction |
| Output | Desain penelitian | Eksperimen + paper + defense |

**Rule praktis:**
- ❌ "Explain what research is" → itu Metopen
- ✅ "Show how to run experiment in system/software" → ini Riset TI

---

## 6. SIGNATURE MODELS (1 PER BAB — IDENTITAS BUKU)

| Bab | Model | Fungsi |
|-----|-------|--------|
| 1 | **Research Trust Model** | Reality→Data→Processing→Analysis→Inference→Knowledge |
| 2 | **Problem Formation Model** + **Problem Quality Model** | Symptom→Problem→Research Problem→Variable |
| 3 | **Research Positioning Model** | Studies→Comparison→Limitation→Gap→Position→Contribution |
| 4 | **RQ Formation Model** | Problem→Gap→RQ→Hypothesis→Experiment |
| 5 | **Measurement Alignment Model** | Problem→Concept→Variable→Metric→Data→Result |
| 6 | **System as Experiment Model** | RQ→Variable→System Component→Setup→Output |
| 7 | **Experimental Validity Model** | RQ→Hypothesis→Variable→Controlled Experiment→Conclusion |
| 9 | **Reproducible Implementation Model** | Design→Implementation→Environment→Consistency→Reproducibility |
| 10 | **Experiment Execution Pipeline** | Design→Plan→Execution→Collection→Logging→Dataset |
| 11 | **Data Trust Model** | Raw→Cleaning→Consistency→Validation→Trusted Data |
| 12 | **Data → Insight Model** | Validated Data→Presentation→Visualization→Pattern→Insight |
| 13 | **Data Refinement Pipeline** | Raw→Cleaning→Transformation→Normalization→Analysis Ready |
| 14 | **Data → Knowledge Model** | Data→Analysis→Interpretation→Explanation→Knowledge |
| 15 | **Scientific Argument Flow** | Problem→Gap→RQ→Method→Result→Analysis→Conclusion→Contribution |
| 16 | **Scientific Defense Model** | Work→Presentation→Questioning→Defense→Evaluation→Acceptance |

---

## 7. QUALITY GATES (VALIDASI SETIAP BAB)

Sebelum menganggap bab selesai, jawab 3 pertanyaan ini:

### Gate 1 — Relevansi
> "Apakah bab ini mendorong pembaca **berpikir**, bukan sekadar membaca?"

### Gate 2 — Eksperimental
> "Apakah bab ini mengarah ke **eksperimen**, bukan hanya teori?"

### Gate 3 — Output
> "Apakah bab ini menghasilkan **output penelitian nyata** (artefak, data, analisis)?"

**Jika salah satu jawabannya "tidak" → bab sedang drift.**

---

## 8. CONTENT RULES

### 8.1 Struktur Setiap Bab (WAJIB)
1. Narasi pembuka (semi-formal, book-grade)
2. Signature Model (diagram + penjelasan)
3. Definisi kunci
4. Konsep inti (deep, bukan deskriptif)
5. Research vs Engineering perspective
6. Research Reality (fenomena nyata)
7. Cognitive Traps (kesalahan berpikir yang umum terjadi)
8. Case Study — Basic (bad vs good)
9. Case Study — Advanced (bad vs good)
10. Template praktis
11. Mindmap ringkasan
12. AI-Ready Prompt (untuk scaling)
13. Final Statement (kalimat penutup kuat)

### 8.2 Batasan Konten
- **Max 2 case study per bab** (basic + advanced)
- **Max 4-5 cognitive traps** per bab
- **1 signature model** per bab (tidak boleh lebih)
- Setiap tambahan harus lulus **Rule of 3**:
  1. Menguatkan konsep inti
  2. Terhubung ke eksperimen
  3. Bisa digunakan dalam praktik riset

### 8.3 Gaya Penulisan
- **Semi-formal academic** (mudah dibaca, tetap ilmiah)
- Narasi mengalir, ada analogi
- Terminologi presisi
- Referensi tetap kuat (APA/IEEE)
- Tidak terlalu opini tanpa dasar

### 8.4 Transisi Antar Bab
Setiap bab WAJIB punya:
- **Opening bridge**: "Dari bab sebelumnya, kita sudah memahami..."
- **Closing bridge**: "Dengan [konsep bab ini], kita siap melangkah ke..."

---

## 9. CPL YANG DIBEBANKAN

| CPL | Deskripsi | Domain |
|-----|-----------|--------|
| **CPL01** | Sikap sesuai Pancasila, etis, bertanggung jawab, lifelong learning | Afektif |
| **CPL02** | Menyusun karya ilmiah, komunikasi, kerja tim, kepemimpinan | Soft skills |
| **CPL03** | Penalaran matematis, logis, kritis, sistematis (fundamental computing) | Kognitif |
| **CPL06** | Desain & pengembangan aplikasi multi-platform, keberlanjutan, keamanan | Engineering |

---

## 10. CPMK MAPPING

| CPMK | Fokus | CPL Utama | CPL Pendukung |
|------|-------|-----------|---------------|
| CPMK01 | Problem Framing | CPL03 | CPL06 |
| CPMK02 | Experimental Design | CPL06 | CPL03 |
| CPMK03 | Execution | CPL06 | — |
| CPMK04 | Evaluation | CPL03 | CPL02 |
| CPMK05 | Reporting | CPL02 | — |
| CPMK06 | Defense | CPL02 | CPL03 |

---

## 11. CORE MESSAGE BUKU

> **"Penelitian bukan tentang membuat sistem bekerja,
> tetapi tentang membuktikan bahwa apa yang ditemukan benar, valid, dan dapat dipercaya."**

---

## 12. POSITIONING BUKU

**Buku ini BUKAN:**
- Buku metodologi penelitian (sudah banyak)
- Buku tutorial coding (bukan tujuannya)
- Buku statistik (itu domain Metopen/Statistika)

**Buku ini ADALAH:**
- Panduan berpikir sebagai peneliti eksperimental di bidang TI
- Framework end-to-end: dari problem → defense
- Training manual untuk menghasilkan penelitian yang **valid, reproducible, dan defensible**

---

*Dokumen ini adalah sumber kebenaran tunggal (single source of truth) untuk seluruh proses penulisan buku.*
*Terakhir diperbarui: 30 Maret 2026*
