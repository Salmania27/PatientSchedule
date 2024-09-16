## Patient Scheduling Optimization
Untuk menjalankan program, pastikan telah menginstall:

- Python 3.x
- Libraries:
  - pandas 
  - numpy 
  Untuk menginstall library yang diperlukan, dapat dilakukan dengan menjalankan:

    `pip install pandas numpy`

## Installation

Clone repository:

  `git clone https://github.com/Salmania27/PatientSchedule.git`

Arahkan ke direktori: 

  `cd PatientSchedule`

## How to Run Program

Untuk menjalankan program dan mengoptimalkan jadwal pasien, ikuti langkah-langkah berikut.

Pastikan dataset pasien sudah tersedia format yang diperlukan, atau dapat mengunduh dataset pada https://docs.google.com/spreadsheets/d/1t6uK0kLCGacBpPgx0LEObrNGLc-C6oYM/edit?usp=drive_link&ouid=114372152585647695849&rtpof=true&sd=true

kemudian jalankan script Python PKA.py untuk menghasilkan jadwal yang optimal:

`python PKA.py`

Program akan mengeluarkan jadwal yang optimal ke konsol dan/atau file output.

## How it Works

1. Urutkan pasien berdasarkan waktu selesai
2. Ulangi daftar pasien yang telah diurutkan
3. Jadwalkan pasien jika waktu mulainya lebih lama atau sama dengan waktu selesai pasien yang dijadwalkan terakhir
4. Keluarkan jadwal setelah semua pasien dievaluasi
5. Pendekatan ini memastikan bahwa sebanyak mungkin pasien dijadwalkan tanpa ada konflik dalam slot waktu 

## Input
<img width="610" alt="image" src="https://github.com/user-attachments/assets/c51e3fc2-da90-4205-88c2-0986c77e25fe">


## Output
<img width="561" alt="image" src="https://github.com/user-attachments/assets/751fb1eb-fe7c-49a2-b814-c471e7ccfe78">

