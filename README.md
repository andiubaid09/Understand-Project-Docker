# 🚀 Docker Explained In A Simple Way  

[![Python](https://img.shields.io/badge/python-3.10-blue.svg)](https://www.python.org/)  
[![Docker](https://img.shields.io/badge/docker-ready-blue.svg)](https://www.docker.com/)   

Project sederhana untuk memahami **Docker & Docker Compose** dengan contoh nyata:  
- Flask web app  
- Redis sebagai backend penyimpan counter  

---

## ⚡ Prerequisites  

Pastikan sudah terpasang di device masing-masing:  
- [Docker Desktop](https://www.docker.com/products/docker-desktop/)  
- [Git](https://git-scm.com/)  
- (Opsional) [VSCode](https://code.visualstudio.com/)  

---

## 🔥 Step by Step Setup  

### 1️⃣ Clone repository ini  

```bash
git clone https://github.com/andiubaid09/Understand-Project-Docker.git
cd "Understand-Project-Docker"
```

### 2️⃣ Install dependencies

```bash
cd app
pip install -r requirements.txt
python app.py
```

### 3️⃣ Build image dengan Docker
```bash
docker compose build
```

### 4️⃣ Jalankan dengan Docker Compose
```bash
docker compose up
```
atau
```bash
docker compose up -d
```

#### 5️⃣ Akses aplikasi
Buka di browser
```bash
http://localhost:5000
```
Setiap refresh halaman, counter akan bertambah (disimpan di redis)

### 6️⃣ Stop container
```bash
docker compose down
```

### 🐳 Belajar Apa dari Proyek Ini?
- Cara menulis DockerFile untuk aplikasi Python
- Menjalankan banyak service sekaligus dengan docker compose
- Integrasi sederhana Flask ↔ Redis
