# 🎒 Perangkat Lunak Deteksi Seragam 👞 

Repositori ini menyimpan kode sumber untuk Perangkat Lunak Deteksi Seragam, seperti yang dijelaskan dalam jurnal ["Development of a Uniform Detection Software Using YOLOv8 Algorithm for the University of Southern Mindanao Students"](https://github.com/gisketch/complete-uniform-detection-YOLOv8/files/11717858/THESIS.MANUSCRIPT.pdf) oleh Joshua Tejedor. Saya bertanggung jawab atas pemrograman dan pengembangan untuk proyek ini. Perangkat lunak ini menggunakan algoritma YOLOv8 untuk menganalisis rekaman video yang diambil oleh kamera, yang memungkinkannya untuk menentukan apakah mahasiswa di Universitas Mindanao Selatan (USM) mengenakan seragam lengkap atau tidak lengkap.

## Summary

Perangkat Lunak Deteksi Seragam adalah aplikasi canggih yang menggunakan algoritma YOLOv8 untuk deteksi objek secara real-time guna menentukan apakah mahasiswa Universitas Mindanao Selatan (USM) mengenakan seragam lengkap atau tidak lengkap. Dengan menganalisis rekaman video, perangkat lunak tersebut secara akurat mengidentifikasi mahasiswa dan mencatat status seragam mereka, sehingga tercipta lingkungan kampus yang lebih teratur dan disiplin. Dengan pendekatan yang efisien dan otomatis, perangkat lunak tersebut menggantikan inspeksi manual, menghemat waktu, dan memastikan kepatuhan terhadap kebijakan tata tertib universitas.

## Features

Perangkat Lunak Deteksi Seragam menawarkan fitur-fitur berikut:

- Deteksi real-time siswa yang mengenakan seragam lengkap atau tidak lengkap
- Pencatatan siswa yang terdeteksi dengan rincian seperti waktu deteksi, jenis kelamin, dan kelengkapan seragam
- Basis data log untuk analisis lebih lanjut dan penyimpanan catatan
- Antarmuka yang ramah pengguna untuk interaksi yang mudah

## Installation

### Backend (Python Flask Server)

1. Clone the repository:

```bash
git clone https://github.com/gisketch/complete-uniform-detection-YOLOv8
```

2. Navigate to the backend directory:

```bash
cd backend
```

3. Install the required dependencies:

```bash
pip install -r requirements.txt
```

4. Start the server:

```bash
python server.py
```

### Frontend (ReactJS)

1. Clone the repository:

```bash
cd frontend
```

2. Install the required dependencies:

```bash
npm install
```

3. Start the React development server:

```bash
npm run dev
```

## Screenshots

![image](https://github.com/gisketch/complete-uniform-detection-YOLOv8/assets/78424395/890c9cd5-a480-48b1-bee7-5b6cd752ef24)

![image](https://github.com/gisketch/complete-uniform-detection-YOLOv8/assets/78424395/a1999b35-e29d-4cf6-bfd3-9b9c197abac4)


## Contributing

Contributions to the Uniform Detection Software are welcome. If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request.
