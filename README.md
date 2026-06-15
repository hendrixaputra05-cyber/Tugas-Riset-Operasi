# Tugas-Riset-Operasi
yoweslah ngnu kae
```mermaid
graph LR
    %% Koneksi Antar Jalur (Contoh Lintas Utara/Selatan Jawa)
    GMR --> PWK & CN
    PSE --> PWK & CNP
    
    PWK --> CN & CNP
    BDG --> TSM & PWT
    TSM --> KYA
    
    CN --> TG & PWT
    CNP --> TG & PWT
    
    PWT --> SMT & KYA
    KYA --> KTA & YK
    KTA --> YK
    
    TG --> SMT
    SMT --> SLO & CU
    
    YK --> SLO & MN
    SLO --> MN
    
    CU --> SBI & KTS
    MN --> KTS & SGU
    KTS --> SGU & ML
    
    SBI --> SGU
    SGU --> PB & JR
    ML --> JR
    
    PB --> KTG
    JR --> KTG

    class GMR,PSE,KTG startEnd;
