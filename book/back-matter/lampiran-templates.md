# Lampiran A — Kumpulan Template Praktis

> Template-template dari setiap bab dikumpulkan di sini untuk referensi cepat.
> Setiap template merujuk ke bab asalnya untuk konteks dan penjelasan lengkap.

---

## Daftar Template

| # | Nama Template | Dari Bab | Bagian |
|---|---------------|----------|--------|
| A.1 | Research Mindset Self-Assessment | Bab 1 | I |
| A.2 | Problem Statement Builder | Bab 2 | I |
| A.3 | Literature Mapping & Gap Identification | Bab 3 | I |
| A.4 | RQ-Contribution-Hypothesis | Bab 4 | I |
| A.5 | Definisi Variabel, Metrik & Justifikasi | Bab 5 | II |
| A.6 | Mapping RQ ke Arsitektur Sistem | Bab 6 | II |
| A.7 | Desain Eksperimen Lengkap | Bab 7 | II |
| A.8 | Integration Checklist (Proposal Checkpoint) | Bab 8 | III |
| A.9 | Dokumentasi Setup Eksperimen | Bab 9 | III |
| A.10 | Execution Plan & Data Log | Bab 10 | III |
| A.11 | Data Validation Checklist | Bab 11 | III |
| A.12 | Result Presentation Plan | Bab 12 | IV |
| A.13 | Preprocessing Documentation Log | Bab 13 | IV |
| A.14 | Analysis & Interpretation Report | Bab 14 | IV |
| A.15 | Paper Structure Checklist | Bab 15 | IV |
| A.16 | Defense Preparation Sheet | Bab 16 | IV |

---

> **Catatan penggunaan:**
> Setiap template dirancang untuk diisi secara progresif seiring kemajuan riset. Template dari Bagian I (Bab 1–4) menghasilkan fondasi yang digunakan oleh template Bagian II (Bab 5–7), dan seterusnya. Untuk konteks lengkap, penjelasan setiap field, dan contoh pengisian, rujuk ke section "Template Praktis" di bab masing-masing.

---

## A.1 — Research Mindset Self-Assessment (Bab 1)

```
Nama Peneliti    : ____________________
Tanggal          : ____________________

1. Ketika membaca klaim "metode X 95% akurat":
   - Pertanyaan pertama saya: ____________________
   - Data apa yang saya butuhkan untuk memverifikasi: ____________________

2. Posisi paradigma:
   - Pendekatan saya: [ ] Positivis  [ ] Interpretivis  [ ] Design Science  [ ] Mixed
   - Alasan: ____________________

3. Identifikasi distorsi:
   - Asumsi tersembunyi dalam riset saya: ____________________
   - Sumber bias potensial: ____________________
   - Langkah mitigasi: ____________________

4. Komitmen etika:
   - Data yang saya tidak akan manipulasi: ____________________
   - Batasan yang saya akui sejak awal: ____________________
```

---

## A.2 — Problem Statement Builder (Bab 2)

```
PROBLEM STATEMENT BUILDER

Domain & Konteks
  Domain   : ____________________
  Konteks  : ____________________

System Context
  Input       : ____________________
  Process     : ____________________
  Output      : ____________________
  Outcome     : ____________________
  Constraints : ____________________
  Stakeholders: ____________________

Fenomena → Problem
  Fenomena yang diamati             : ____________________
  Gejala (symptom) yang terukur     : ____________________
  Masalah yang didiagnosis          : ____________________
  Masalah riset (researchable)      : ____________________
  Variabel yang terukur             : ____________________

Problem Quality Check
  [  ] Clarity — Apakah satu orang membaca akan paham?
  [  ] Measurability — Apakah ada metrik kuantitatif?
  [  ] Relevance — Apakah penting untuk domain?
  [  ] Testability — Apakah bisa gagal?
  [  ] Impact — Apakah ada kontribusi jika terjawab?

Problem Statement (1 paragraf):
  ____________________
```

---

## A.3 — Literature Mapping & Gap Identification (Bab 3)

```
LITERATURE MAPPING

Topik      : ____________________
Database   : ____________________
Query      : ____________________
Tahun      : ____________________
Hasil awal : ____ paper → Screening → ____ paper final

Literature Matrix (concept-centric):

| Study | Tahun | Method | Data | Result | Limitation |
|-------|-------|--------|------|--------|------------|
|       |       |        |      |        |            |
|       |       |        |      |        |            |

Pola yang ditemukan:
  Metode dominan     : ____________________
  Dataset umum       : ____________________
  Limitasi berulang  : ____________________

GAP IDENTIFICATION

Gap 1: [Jenis: performance / method / data / context]
  Deskripsi : ____________________
  Bukti     : ____________________
  Signifikansi: ____________________

Gap 2: [Jenis: ____]
  Deskripsi : ____________________
  Bukti     : ____________________
  Signifikansi: ____________________

Baseline Selection:
| Baseline | Relevansi | Representatif | Source |
|----------|-----------|---------------|--------|
|          |           |               |        |
|          |           |               |        |
```

---

## A.4 — RQ-Contribution-Hypothesis (Bab 4)

```
RQ-CONTRIBUTION-HYPOTHESIS

Gap Statement  : ____________________

Research Question:
  Tipe         : [ ] Comparison  [ ] Improvement  [ ] Exploratory
  Formulasi    : ____________________
  Variabel IV  : ____________________
  Variabel DV  : ____________________
  Metrik       : ____________________
  Dataset      : ____________________
  Baseline     : ____________________

Quality Check RQ:
  [  ] Variabel spesifik
  [  ] Metrik jelas
  [  ] Baseline ada
  [  ] Konteks disebutkan
  [  ] Memerlukan eksperimen (bukan hanya survei literatur)

Contribution Statement:
  Apa yang baru diketahui : ____________________
  Jenis kontribusi        : [ ] Improvement  [ ] Comparison  [ ] Novel approach
  Gap yang diisi          : ____________________

Hypothesis Pair:
  H₀ : ____________________
  H₁ : ____________________
  Threshold              : ____________________
  Justifikasi threshold  : ____________________
```

---

## A.5 — Definisi Variabel, Metrik & Justifikasi (Bab 5)

```
VARIABLE & METRIC DEFINITION

Research Question: ____________________

| Variabel | Tipe | Konsep | Metrik | Skala | Satuan | Cara Mengukur | Justifikasi |
|----------|------|--------|--------|-------|--------|---------------|-------------|
|          | IV   |        |        |       |        |               |             |
|          | DV   |        |        |       |        |               |             |
|          | CV   |        |        |       |        |               |             |

Alignment Check:
  RQ → Concept → Variable → Metric → Data → Result
  [  ] Setiap langkah terdokumentasi
  [  ] Tidak ada "lompatan logis"
  [  ] Metrik mengukur apa yang dimaksud (construct validity)
```

---

## A.6 — Mapping RQ ke Arsitektur Sistem (Bab 6)

```
SYSTEM-EXPERIMENT MAPPING

Research Question: ____________________

Variable → Component Mapping:
| Variabel | Tipe | Komponen Sistem | Cara Manipulasi/Pengukuran |
|----------|------|-----------------|---------------------------|
|          | IV   |                 |                           |
|          | DV   |                 |                           |
|          | CV   |                 |                           |

4 Prinsip Desain:
  [  ] Traceability — Setiap komponen bisa ditelusuri ke variabel
  [  ] Variable Isolation — IV bisa diubah tanpa mengubah CV
  [  ] Measurement Integration — Pengukuran DV built-in
  [  ] Reproducibility — Setup bisa direkonstruksi

Experimental Setup:
  Input data     : ____________________
  Parameter      : ____________________
  Output format  : ____________________
```

---

## A.7 — Desain Eksperimen Lengkap (Bab 7)

```
EXPERIMENT DESIGN

Research Question : ____________________
Hypothesis        : ____________________
Tipe Eksperimen   : [ ] Comparison  [ ] Ablation  [ ] Parameter

Kondisi Eksperimen:
| Kondisi | Deskripsi | IV Value | CV Settings |
|---------|-----------|----------|-------------|
| Control |           |          |             |
| Treatment |         |          |             |

Fairness Checklist:
  [  ] Dataset identik untuk semua kondisi
  [  ] Preprocessing setara
  [  ] Tuning effort setara
  [  ] Environment identik
  [  ] Metrik evaluasi sama

Threat Analysis:
| Threat Type | Ancaman Spesifik | Mitigasi |
|-------------|-----------------|----------|
| Internal    |                 |          |
| External    |                 |          |
| Construct   |                 |          |
| Conclusion  |                 |          |

Statistical Plan:
  Uji statistik   : ____________________
  Justifikasi      : ____________________
  Alpha            : ____________________
  Effect size min  : ____________________
```

---

## A.8 — Integration Checklist / Proposal Checkpoint (Bab 8)

```
PROPOSAL INTEGRATION CHECKLIST

Koneksi Vertikal (Flow Atas-Bawah):
  [  ] Problem → Gap: masalah terdokumentasi di literatur
  [  ] Gap → RQ: pertanyaan menjawab gap spesifik
  [  ] RQ → Hypothesis: hipotesis memprediksi jawaban
  [  ] Hypothesis → Metric: metrik mengukur variabel dalam hipotesis
  [  ] Metric → System: komponen sistem menghasilkan/mengukur metrik
  [  ] System → Experiment: desain eksperimen menggunakan sistem

Koneksi Horizontal (Konsistensi):
  [  ] Istilah sama di semua bagian
  [  ] Variabel yang disebut di RQ = variabel di hipotesis = metrik di desain
  [  ] Scope tidak berubah dari masalah ke eksperimen

Rubrik Self-Assessment:
| Kriteria | 1 (Lemah) | 2 (Cukup) | 3 (Baik) | Skor |
|----------|-----------|-----------|----------|------|
| Koherensi |          |           |          |      |
| Specificity |        |           |          |      |
| Feasibility |        |           |          |      |
| Rigor     |          |           |          |      |
```

---

## A.9 — Dokumentasi Setup Eksperimen (Bab 9)

```
EXPERIMENT SETUP DOCUMENTATION

Hardware:
  CPU  : ____________________
  RAM  : ____________________
  GPU  : ____________________
  Storage: ____________________

Software:
  OS      : ____________________
  Runtime : ____________________
  Framework: ____________________

Dependencies:
| Library | Version | Sumber | Hash/Checksum |
|---------|---------|--------|---------------|
|         |         |        |               |

Konfigurasi:
  Config file    : ____________________
  Seed           : ____________________
  Hyperparameters: ____________________

Reproducibility Check:
  [  ] Dependency terdokumentasi (requirements.txt / lock file)
  [  ] Seed ditetapkan
  [  ] Config di version control
  [  ] README instruksi reproduksi
```

---

## A.10 — Execution Plan & Data Log (Bab 10)

```
EXECUTION PLAN

| Run # | Skenario | Seed | Parameter | Status | Waktu | Output File |
|-------|----------|------|-----------|--------|-------|-------------|
| 1     |          |      |           |        |       |             |
| 2     |          |      |           |        |       |             |
| ...   |          |      |           |        |       |             |

Jumlah runs per skenario : ____
Total runs               : ____

DATA LOG (per run):
  Run ID     : ____________________
  Timestamp  : ____________________
  Skenario   : ____________________
  Input      : ____________________
  Output     : ____________________
  Anomali    : ____________________
  Catatan    : ____________________
```

---

## A.11 — Data Validation Checklist (Bab 11)

```
DATA VALIDATION CHECKLIST

Completeness:
  [  ] Semua skenario tercakup
  [  ] Jumlah run sesuai rencana
  [  ] Tidak ada file output yang hilang
  Missing: ____ dari ____ data points

Format Consistency:
  [  ] Semua file format sama (CSV/JSON/...)
  [  ] Header konsisten
  [  ] Tipe data konsisten (numerik tetap numerik)

Range & Logic:
  [  ] Nilai dalam range yang masuk akal
  [  ] Tidak ada waktu negatif
  [  ] Akurasi 0–100%, bukan di luar range
  Anomali ditemukan: ____________________

Cross-Validation:
  [  ] Run identik → hasil mendekati (tidak beda ordo magnitudo)
  [  ] Trend konsisten dengan ekspektasi teori (jika ada)

Keputusan:
  [  ] Data siap analisis
  [  ] Perlu cleaning (lihat Bab 13)
  [  ] Perlu re-run (skenario: ____)
```

---

## A.12 — Result Presentation Plan (Bab 12)

```
RESULT PRESENTATION PLAN

Research Question: ____________________
Metrik Utama     : ____________________

Tabel Hasil:
| Skenario | Metrik 1 (mean ± std) | Metrik 2 (mean ± std) | n |
|----------|----------------------|----------------------|---|
|          |                      |                      |   |

Visualisasi yang Direncanakan:
| # | Jenis Grafik | Pesan Utama | Metrik |
|---|-------------|-------------|--------|
| 1 |             |             |        |
| 2 |             |             |        |

Bias Check:
  [  ] Y-axis mulai dari 0 (atau dijustifikasi)
  [  ] Error bar/CI ditampilkan
  [  ] Semua data disertakan (tidak cherry-picked)
  [  ] Tidak menggunakan 3D tanpa alasan
```

---

## A.13 — Preprocessing Documentation Log (Bab 13)

```
PREPROCESSING LOG

Dataset          : ____________________
Jumlah data awal : ____________________

Cleaning:
| Masalah | Jumlah Kasus | Penanganan | Justifikasi |
|---------|-------------|------------|-------------|
| Missing |             |            |             |
| Duplikat|             |            |             |
| Error   |             |            |             |

Transformation:
| Transformasi | Variabel | Detail | Alasan |
|-------------|----------|--------|--------|
|             |          |        |        |

Normalization:
  Metode    : ____________________
  Alasan    : ____________________
  Parameter : (dihitung dari: training set / seluruh data)

Leakage Check:
  [  ] Parameter normalisasi dari training set saja
  [  ] Tidak ada informasi test set dalam preprocessing
  [  ] Cross-validation dilakukan setelah split

Jumlah data akhir: ____________________
Script tersedia  : [ ] Ya → path: ____ | [ ] Belum
```

---

## A.14 — Analysis & Interpretation Report (Bab 14)

```
ANALYSIS & INTERPRETATION

1. Statistik Deskriptif:
   | Skenario | Mean | Std | Median | Min | Max | n |
   |----------|------|-----|--------|-----|-----|---|
   |          |      |     |        |     |     |   |

2. Uji Hipotesis:
   Uji yang digunakan : ____________________
   Justifikasi        : ____________________
   Hasil: p = ____, effect size (d/r/η²) = ____
   CI 95%             : [____, ____]

3. Keputusan:
   [  ] H₀ ditolak → H₁ diterima
   [  ] H₀ tidak ditolak

4. Interpretasi:
   Hubungan ke RQ     : ____________________
   Practical significance: ____________________
   Perbandingan literatur: ____________________

5. Limitation:
   | Jenis | Ancaman | Dampak | Mitigasi |
   |-------|---------|--------|----------|
   |       |         |        |          |

6. Failure Analysis (jika H₀ tidak ditolak):
   Penyebab potensial: ____________________
   Boundary condition : ____________________
   Insight            : ____________________
```

---

## A.15 — Paper Structure Checklist (Bab 15)

```
PAPER STRUCTURE CHECKLIST

Title  : ____________________
Target : [ ] Jurnal  [ ] Konferensi  [ ] Laporan

Section Check:
  [  ] Abstract — masalah, metode, hasil utama, kontribusi (max 250 kata)
  [  ] Introduction — konteks → gap → RQ → kontribusi → struktur paper
  [  ] Related Work — concept-centric, gap positioning
  [  ] Method — reproducible: desain, variabel, metrik, setup, prosedur
  [  ] Results — tabel + grafik + observasi (tanpa interpretasi)
  [  ] Discussion — interpretasi, perbandingan, implikasi, limitation
  [  ] Conclusion — jawaban RQ, kontribusi, future work

Consistency Matrix:
  [  ] RQ di Introduction = RQ di Method = RQ di Conclusion
  [  ] Variabel di Method = variabel di Results
  [  ] Klaim di Discussion didukung data di Results
  [  ] Limitasi di Discussion diaddress di Conclusion/Future Work

Writing Quality:
  [  ] Clarity — mudah dipahami tanpa re-read
  [  ] Precision — tidak ada istilah ambigu
  [  ] Conciseness — tidak ada kalimat redundan
```

---

## A.16 — Defense Preparation Sheet (Bab 16)

```
DEFENSE PREPARATION

Slide Deck Plan:
  Total slides : ____ (target: 10–12 konten + title/closing)
  Time per slide: ~2 min
  Total time    : ____ menit

Slide Outline:
| # | Pesan Utama | Visual | Waktu |
|---|-------------|--------|-------|
| 1 | Title       |        | 30s   |
| 2 | Problem & Motivation |  | 2min  |
| 3 | Research Gap |       | 2min  |
| ...| ...        |        |       |

Anticipatory Defense Matrix:
| Kategori | Pertanyaan Potensial | Jawaban (data-based) |
|----------|---------------------|---------------------|
| Problem  |                     |                     |
| Gap      |                     |                     |
| Method   |                     |                     |
| Results  |                     |                     |
| Generalization |               |                     |

Latihan:
  Latihan 1: [tanggal] — [catatan timing & feedback]
  Latihan 2: [tanggal] — [catatan timing & feedback]
  Latihan 3: [tanggal] — [catatan timing & feedback]
```

---

<!-- STATUS: 🟢 Complete -->
