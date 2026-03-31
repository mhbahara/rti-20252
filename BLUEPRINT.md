# BLUEPRINT KONSOLIDASI — SELURUH BAB (M1–M16)

> Dokumen ini merangkum blueprint setiap bab secara ringkas.
> Gunakan sebagai peta navigasi saat menulis.
> Detail lengkap ada di `docs/disscus04.md`.

---

## BAGIAN I — FOUNDATION (Thinking Phase)

---

### BAB 1 — Etika Penelitian, Validitas, dan Paradigma (M1)

**CPMK:** CPMK01 | **CPL:** CPL03 | **Sub-CPMK:** 1.1

**Signature Model:** Research Trust Model
```
Reality → Data → Processing → Analysis → Inference → Knowledge
(setiap tahap membawa risiko distorsi; etika mengendalikan distorsi)
```

**Konsep Inti:**
- Etika = penjaga validitas ilmiah (bukan sekadar moral)
- Validitas: internal, external, construct
- Research vs Engineering Validation
- Kriteria kebenaran ilmiah
- Paradigma: positivism, interpretivism, pragmatism
- Posisi MK: positivist + design science

**Case Study:**
1. Basic: Manipulasi dataset ML — akurasi tinggi tapi data palsu
2. Advanced: AI bias — model terlihat bagus tapi bias tersembunyi

**Cognitive Traps:**
1. "Angka tinggi = benar"
2. "Data netral"
3. "Jika jalan, maka benar"
4. "Kegagalan tidak perlu dilaporkan"

**Final Statement:**
> "Penelitian bukan tentang mendapatkan hasil, tetapi tentang memastikan hasil tersebut dapat dipercaya."

**Output Praktis:** Esai analisis kasus etika + posisi paradigma

---

### BAB 2 — Problem Formulation & System Context (M2)

**CPMK:** CPMK01 | **CPL:** CPL03 | **Sub-CPMK:** 1.2

**Signature Model:** Problem Formation Model + Problem Quality Model
```
Reality → Observed Issue (Symptom) → Diagnosed Problem → Researchable Problem → Measurable Variable

Clarity → Measurability → Relevance → Testability → Impact
```

**Konsep Inti:**
- Topic vs Problem vs Research Problem (hierarki)
- Symptom vs Problem (akar masalah)
- System thinking: Input→Process→Output→Outcome + Constraints + Stakeholders
- Problem → Variable → Metric (transformasi)
- 5 Kriteria: Specific, Measurable, Relevant, Testable, Real-world

**Case Study:**
1. Basic: Rekomendasi film — akurasi tinggi tapi user tidak puas
2. Advanced: Fraud detection — 98% akurasi tapi fraud lolos (imbalance)

**Cognitive Traps:**
1. "Saya ingin menggunakan metode X"
2. "Semakin kompleks semakin bagus"
3. "Problem tidak perlu diukur"
4. "Semua problem bisa diteliti"

**Final Statement:**
> "Penelitian tidak dimulai dari solusi, tetapi dari masalah yang dipahami secara mendalam dan dapat diuji secara ilmiah."

**Output Praktis:** Problem statement (spesifik, measurable, konteks sistem)

---

### BAB 3 — Literature Review, Research Gap & Baseline (M3)

**CPMK:** CPMK01 | **CPL:** CPL03 | **Sub-CPMK:** 1.3

**Signature Model:** Research Positioning Model
```
Existing Studies → Method Comparison → Limitation Identification → Research Gap → Research Position → Contribution
```

**Konsep Inti:**
- Literature review = positioning, bukan ringkasan
- 4 jenis gap: Performance, Method, Data, Context
- Baseline: relevan, representatif, state-of-the-art
- Gap → RQ → Hypothesis → Experiment (bridge)
- Strategi pencarian: IEEE, ACM, Scopus, boolean query

**Case Study:**
1. Basic: Image classification — banyak paper, gap tidak jelas
2. Advanced: Deteksi penyakit — baseline lemah, kontribusi diragukan

**Cognitive Traps:**
1. "Semakin banyak referensi, semakin bagus"
2. "Belum ada = gap"
3. "Tidak perlu baseline"

**Final Statement:**
> "Literature review bukan tentang apa yang sudah diketahui, tetapi tentang apa yang belum diselesaikan dan bagaimana Anda mengisinya."

**Output Praktis:** Tabel literatur + gap statement + baseline selection

---

### BAB 4 — Research Question, Contribution & Hypothesis (M4)

**CPMK:** CPMK01 | **CPL:** CPL03 | **Sub-CPMK:** 1.4

**Signature Model:** RQ Formation Model
```
Problem → Research Gap → Research Question → Hypothesis → Experiment Design
```

**Konsep Inti:**
- RQ = instrumen pengarah eksperimen
- 3 jenis RQ: Comparison, Improvement, Exploratory
- Contribution: improvement, comparison, novel approach
- Hypothesis: H0 (null) + H1 (alternative) — harus testable
- RQ → Variable → Metric → Data → Analysis

**Case Study:**
1. Basic: RQ terlalu umum → tidak bisa diuji
2. Advanced: RQ tanpa baseline → tidak ada pembanding

**Cognitive Traps:**
1. "RQ = judul dalam bentuk tanya"
2. "RQ tidak perlu metric"
3. "RQ bisa dijawab tanpa eksperimen"

**Final Statement:**
> "Research Question bukan sekadar pertanyaan, tetapi blueprint dari eksperimen yang akan dilakukan."

**Output Praktis:** RQ (clear & testable) + contribution statement + hypothesis (H0/H1)

---

## BAGIAN II — MEASUREMENT & DESIGN (Designing Phase)

---

### BAB 5 — Metric, Measurement & Data (M5)

**CPMK:** CPMK02 | **CPL:** CPL06 | **Sub-CPMK:** 2.1

**Signature Model:** Measurement Alignment Model
```
Problem → Concept → Variable → Metric → Data → Result
```

**Konsep Inti:**
- Concept → Metric (operationalization)
- Jenis data: nominal, ordinal, interval, ratio
- Metric selection: sesuai problem, representatif, sensitif
- Multi-metric evaluation
- Data quality: completeness, consistency, validity, representativeness

**Case Study:**
1. Basic: Accuracy tinggi, dataset imbalance → metric menipu
2. Advanced: User satisfaction vs system metric → metric teknis ≠ user experience

**Final Statement:**
> "Penelitian yang baik bukan hanya mengukur, tetapi memastikan bahwa apa yang diukur benar-benar merepresentasikan realitas."

**Output Praktis:** Definisi variabel + metrik + tipe data + justifikasi

---

### BAB 6 — System Design sebagai Experimental Artifact (M6)

**CPMK:** CPMK02 | **CPL:** CPL06 | **Sub-CPMK:** 2.2

**Signature Model:** System as Experiment Model
```
Research Question → Variable → System Component → Experimental Setup → Output (measured)
```

**Konsep Inti:**
- Sistem bukan tujuan → alat uji hipotesis
- Mapping RQ → system component
- 4 prinsip: Traceability, Modularity, Controllability, Measurability
- Control & isolation variabel

**Case Study:**
1. Basic: Model ML tidak bisa diuji (monolith, tidak modular)
2. Advanced: Multiple feature change, no clear impact

**Final Statement:**
> "Dalam penelitian, sistem bukan dibangun untuk digunakan, tetapi untuk membuktikan sesuatu secara ilmiah."

**Output Praktis:** Diagram arsitektur + mapping ke variabel eksperimen

---

### BAB 7 — Experimental Design & Validity (M7)

**CPMK:** CPMK02 | **CPL:** CPL06 | **Sub-CPMK:** 2.3

**Signature Model:** Experimental Validity Model
```
RQ → Hypothesis → Variable Design → Controlled Experiment → Data → Analysis → Conclusion (Validity Level)
```

**Konsep Inti:**
- Eksperimen = menguji hubungan sebab-akibat (causality)
- Korelasi ≠ kausalitas
- 4 validitas: internal, external, construct, conclusion
- Jenis eksperimen: comparison, ablation study, parameter study
- Controlled experiment: ubah 1, kontrol sisanya

**Case Study:**
1. Basic: Eksperimen tanpa kontrol → semua variabel berubah
2. Advanced: Baseline tidak fair → perbandingan bias

**Final Statement:**
> "Eksperimen bukan sekadar menjalankan sistem, tetapi membangun bukti yang dapat dipercaya."

**Output Praktis:** Dokumen desain eksperimen lengkap (variabel, skenario, validity, baseline)

---

## BAGIAN III — EXECUTION (Executing Phase)

---

### BAB 8 — Proposal & Checkpoint / UTS

**Catatan:** Bab ini bersifat integratif — merangkum Bab 1–7 ke dalam proposal.
Konten utama: template proposal + rubrik penilaian + tips defense.

---

### BAB 9 — Implementation & Environment (M9)

**CPMK:** CPMK03 | **CPL:** CPL06 | **Sub-CPMK:** 3.1

**Signature Model:** Reproducible Implementation Model
```
Experiment Design → Implementation → Environment Setup → Execution Consistency → Reproducibility → Trustworthy Result
```

**Konsep Inti:**
- Implementasi ≠ coding biasa → memastikan konsistensi & reproducibility
- Environment control: hardware, software, dependency, OS
- Repeatability vs Reproducibility
- Dokumentasi wajib: setup, parameter, dataset
- Best practice: version control, config logging, environment isolation

**Output Praktis:** Dokumentasi setup + README eksperimen

---

### BAB 10 — Experiment Execution & Data Collection (M10)

**CPMK:** CPMK03 | **CPL:** CPL06 | **Sub-CPMK:** 3.2

**Signature Model:** Experiment Execution Pipeline
```
Design → Execution Plan → Controlled Execution → Data Collection → Data Logging → Dataset for Analysis
```

**Konsep Inti:**
- Execution plan: skenario, jumlah run, variasi parameter
- Multiple run wajib (bukan single run)
- Data logging: ID, timestamp, parameter, result, environment
- Konsistensi eksekusi

**Output Praktis:** Log eksperimen + dataset mentah

---

### BAB 11 — Data Validation & Integrity (M11)

**CPMK:** CPMK03 | **CPL:** CPL06 | **Sub-CPMK:** 3.3

**Signature Model:** Data Trust Model
```
Raw Data → Data Cleaning → Consistency Check → Validation → Trusted Data → Analysis Ready
```

**Konsep Inti:**
- 4 pilar data quality: accuracy, consistency, completeness, validity
- Validation process: format → range → consistency → logic
- Anomaly detection: outlier, missing, inconsistency
- Data vs experiment alignment

**Output Praktis:** Dataset tervalidasi + catatan anomali

---

## BAGIAN IV — ANALYSIS & SCIENTIFIC COMMUNICATION

---

### BAB 12 — Result Presentation & Visualization (M12)

**CPMK:** CPMK04 | **CPL:** CPL03 | **Sub-CPMK:** 4.1

**Signature Model:** Data → Insight Model
```
Validated Data → Structured Presentation → Visualization → Pattern Recognition → Insight
```

**Konsep Inti:**
- Tabel (presisi) vs grafik (insight)
- Mapping: tujuan → jenis visualisasi
- Multi-metric presentation
- Visualization bias: scale manipulation, selective data, misleading

**Output Praktis:** Tabel + grafik + observasi awal

---

### BAB 13 — Data Preprocessing (M13)

**CPMK:** CPMK04 | **CPL:** CPL03 | **Sub-CPMK:** 4.2

**Signature Model:** Data Refinement Pipeline
```
Raw Data → Cleaning → Transformation → Normalization → Processed Data → Analysis Ready
```

**Konsep Inti:**
- Cleaning: missing values, duplicates, errors
- Transformation: encoding, aggregation, feature creation
- Normalization & scaling
- 4 prinsip: consistency, transparency, reproducibility, minimal distortion

**Output Praktis:** Dataset bersih + dokumentasi preprocessing

---

### BAB 14 — Data Analysis, Interpretation & Failure Analysis (M14)

**CPMK:** CPMK04 | **CPL:** CPL03 | **Sub-CPMK:** 4.3

**Signature Model:** Data → Knowledge Model
```
Data → Analysis → Interpretation → Explanation → Knowledge
```

**Konsep Inti:**
- Analysis vs interpretation ("apa yang terjadi" vs "mengapa terjadi")
- Link wajib: result → RQ → hypothesis → conclusion
- Failure analysis: kegagalan = sumber insight
- Limitation: wajib diakui
- Statistical + logical reasoning

**Output Praktis:** Hasil analisis + interpretasi + failure analysis + limitation

---

### BAB 15 — Scientific Writing (M15)

**CPMK:** CPMK05 | **CPL:** CPL02 | **Sub-CPMK:** 5.1

**Signature Model:** Scientific Argument Flow
```
Problem → Gap → RQ → Method → Result → Analysis → Conclusion → Contribution
```

**Konsep Inti:**
- Penulisan = menyusun argumen ilmiah (bukan dokumentasi)
- IMRAD + extension
- Logical flow: Why → What → How → Result → So What
- Konsistensi antar bagian (problem↔RQ↔method↔result↔conclusion)
- Writing quality: clarity, precision, conciseness, consistency

**Output Praktis:** Laporan ilmiah lengkap (IMRAD)

---

### BAB 16 — Presentation & Defense (M16)

**CPMK:** CPMK06 | **CPL:** CPL02 | **Sub-CPMK:** 6.1

**Signature Model:** Scientific Defense Model
```
Research Work → Presentation → Questioning → Defense (Argumentation) → Evaluation → Acceptance
```

**Konsep Inti:**
- Presentasi = simulasi peer-review langsung
- Argumentation: claim + evidence + reasoning
- Anticipating questions: problem, gap, method, metric, result
- Handling questions: langsung, data-based, akui keterbatasan

**Output Praktis:** Slide + defense argument + jawaban berbasis data

---

*Dokumen ini merupakan peta navigasi untuk seluruh proses penulisan buku.*
*Terakhir diperbarui: 30 Maret 2026*
