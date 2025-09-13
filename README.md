# Smart Door Authentication Security Analysis - Morning Team

PBL Project: Analisis keamanan smart door authentication menggunakan data mining untuk konteks Indonesia.

## Tim & Tanggung Jawab

### Data Mining Algorithms (6 orang)
- **fizzxyz**: Isolation Forest algorithm → `algorithms/isolation_forest/`
- **afifahfathonah**: Random Forest algorithm → `algorithms/random_forest/`
- **putriput15**: K-Means Clustering algorithm → `algorithms/k_means_clustering/`
- **navitadamayantisyarif**: Dataset download & setup → `data/raw/`
- **thariq24**: Data preprocessing & Indonesian adaptation → `shared/preprocessing/`
- **geannnnn**: Quality assurance & data mapping → semua folder

## Struktur Repository

algorithms/          # Implementasi 3 algoritma utama
├── isolation_forest/    # Anomaly detection
├── random_forest/       # Classification
└── k_means_clustering/  # User behavior clustering

data/               # Dataset dan dokumentasi
├── raw/               # Smart Home IoT dataset
└── processed/         # Hasil preprocessing (akan dibuat)

shared/             # Tools bersama
└── preprocessing/     # Data processing utilities

results/            # Output analisis
└── performance_comparison/  # Comparative results

## Getting Started

### 1. Clone Repository
git clone https://github.com/dendiainul/smart-door-security-pbl-morning-team.git

### 2. Download Dataset
- Buka `data/raw/README.md` untuk instruksi download dataset
- Dataset: Smart Home IoT Anomaly Detection dari Kaggle

### 3. Mulai Development
- Setiap anggota bekerja di folder masing-masing
- Gunakan `shared/preprocessing/` untuk tools bersama
- Update progress di folder `algorithms/[nama_algoritma]/`

## Target PBL
- 3 algoritma data mining terimplementasi
- Analisis pola keamanan untuk konteks Indonesia
- Comparative performance analysis
- Deteksi modus operandi pencurian (jam rawan, pola suspicious)

## Dataset
Smart Home IoT devices dengan focus pada Smart Lock authentication patterns.
Detail lengkap di `data/raw/README.md`

## Collaboration Guidelines
- Commit dengan message yang jelas
- Update README di folder masing-masing
- Koordinasi preprocessing di `shared/` folder
- Document hasil di `results/` folder
