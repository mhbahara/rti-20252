# Bab 10 — Experiment Execution Pipeline (Gambar 10.1)

```mermaid
graph LR
    A["📋 <b>Design</b><br/><i>Desain dari Bab 7</i>"]
    B["📝 <b>Execution<br/>Plan</b><br/><i>Skenario & jadwal</i>"]
    C["⚙️ <b>Controlled<br/>Execution</b><br/><i>Multiple run</i>"]
    D["📦 <b>Data<br/>Collection</b><br/><i>Pencatatan output</i>"]
    E["📊 <b>Data<br/>Logging</b><br/><i>ID, timestamp, param</i>"]
    F["✅ <b>Dataset for<br/>Analysis</b><br/><i>Terstruktur & lengkap</i>"]

    A -->|"Perencanaan"| B
    B -->|"Eksekusi"| C
    C -->|"Pencatatan"| D
    D -->|"Strukturisasi"| E
    E -->|"Validasi"| F

    style A fill:#FFF7ED,stroke:#EA580C,color:#7C2D12
    style B fill:#FFEDD5,stroke:#EA580C,color:#7C2D12
    style C fill:#FED7AA,stroke:#EA580C,color:#7C2D12
    style D fill:#FDBA74,stroke:#EA580C,color:#FFFFFF
    style E fill:#FB923C,stroke:#C2410C,color:#FFFFFF
    style F fill:#EA580C,stroke:#C2410C,color:#FFFFFF
```
