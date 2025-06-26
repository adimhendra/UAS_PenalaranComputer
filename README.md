# UAS_PenalaranComputer
IMPLEMENTASI SISTEM CASE-BASED REASONING (CBR) BERBASIS PYTHON UNTUK ANALISIS PUTUSAN PENGADILAN PADA PERKARA PIDANA MILITER

Repositori ini berisi implementasi sistem *Case-Based Reasoning* (CBR) menggunakan Python untuk menganalisis dokumen putusan pengadilan pada perkara pidana militer. Sistem ini mencakup tahapan pre-processing, pembentukan basis kasus, retrieval kasus serupa, hingga evaluasi performa model.


1. **Clone repositori ini**
`git clone https://github.com/username/proyek-cbr-pidana-militer.git
cd proyek-cbr-pidana-militer'

2. **Buat virtual environment (opsional tapi disarankan)**
`python -m venv env
source env/bin/activate  # Untuk Linux/macOS
env\Scripts\activate     # Untuk Windows'

3. **Install dependencies**
`pip install -r requirements.txt'

🚀 Menjalankan Pipeline End-to-End
`python main.py'


📌 Contoh Penggunaan

### Menjalankan retrieval kasus dari input teks:
'python cbr/retrieve.py --input "Teks deskripsi kasus pidana militer..."'


### Menjalankan evaluasi:
'python evaluation/evaluate.py --predicted output/predicted.csv --groundtruth data/ground_truth.csv'



