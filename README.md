<div align="center">

  <a href="https://github.com/electrichunter/secki">
    <img src="https://raw.githubusercontent.com/electrichunter/secki/main/assets/secki_banner.png" alt="Seçki Banner">
  </a>

  <pre>
    ____            _      _   
   / __ \          | |    | |  
  | |  | | ___  ___| | __ | |_ 
  | |  | |/ _ \/ __| |/ / | __|
  | |__| |  __/ (__|   <  | |_ 
   \___\_\\___|\___|_|\_\  \__|
  </pre>

  ### Özenle Seç, Değer Kat.
  
  <p><strong>Zevkini yansıtan koleksiyonlar oluştur, topluluğunla paylaş ve ilhamın merkezi ol.</strong></p>

  <p>
    <a href="https://github.com/electrichunter/secki/blob/main/LICENSE"><img src="https://img.shields.io/github/license/electrichunter/secki?style=for-the-badge&color=blueviolet" alt="Lisans"></a>
    <a href="#"><img src="https://img.shields.io/badge/durum-geliştirme-orange?style=for-the-badge" alt="Proje Durumu"></a>
    <a href="https://github.com/electrichunter/secki/actions/workflows/ci.yml"><img src="https://img.shields.io/github/actions/workflow/status/electrichunter/secki/ci.yml?style=for-the-badge&logo=githubactions" alt="CI/CD Durumu"></a>
    <a href="#"><img src="https://img.shields.io/github/stars/electrichunter/secki?style=for-the-badge&color=gold" alt="GitHub Yıldızları"></a>
  </p>
  
  <br>

  <p>
    <a href="#-proje-hakkında"><strong>Proje Hakkında</strong></a> ·
    <a href="#-canlı-demo--ekran-görüntüleri"><strong>Demo</strong></a> ·
    <a href="#-mimari-bakış"><strong>Mimari</strong></a> ·
    <a href="#-kurulum"><strong>Kurulum</strong></a> ·
    <a href="#-api-referansı"><strong>API</strong></a> ·
    <a href="#-katkıda-bulunma"><strong>Katkıda Bulun</strong></a>
  </p>
</div>

## <a name="-proje-hakkında"></a> 🚀 Proje Hakkında

**Seçki**, zevk sahibi küratörleri ve ilham arayanları bir araya getiren, özenle oluşturulmuş koleksiyonların değer kazandığı sosyal bir platformdur. Misyonumuz, anlamlı tavsiyeleri ve estetik bakış açısını ödüllendirerek dijital dünyayı daha güvenilir ve insan odaklı bir keşif alanına dönüştürmektir.

---

## <a name="-canlı-demo--ekran-görüntüleri"></a> 🖼️ Canlı Demo & Ekran Görüntüleri

<p align="center">
  <a href="[PROJENİZİN CANLI DEMO LİNKİ BURAYA]"><strong>Canlı Demoyu Ziyaret Et →</strong></a>
</p>
<br>
<p align="center">
  <img src="https://raw.githubusercontent.com/electrichunter/secki/main/assets/secki_demo.gif" alt="Seçki Uygulama Demosu" width="80%">
  <em><small>Koleksiyon oluşturma, keşif akışı ve profil sayfasının bir önizlemesi.</small></em>
</p>

---

## <a name="-mimari-bakış"></a> 🏛️ Mimarî Bakış

Seçki, modern ve ayrık (decoupled) bir mimari üzerine kurulmuştur. Bu yapı, esneklik, ölçeklenebilirlik ve bakım kolaylığı sağlar.

<p align="center">
  <img src="https://raw.githubusercontent.com/electrichunter/secki/main/assets/secki_mimari.png" alt="Seçki Mimarisi">
  <em><small>Temel sistem mimarisi.</small></em>
</p>

---

## <a name="-teknoloji-yığını"></a> 🛠️ Teknoloji Yığını

Bu projenin temelini oluşturan teknolojiler:

<table>
  <tr>
    <td align="center"><strong>Frontend</strong></td>
    <td align="center"><strong>Backend</strong></td>
    <td align="center"><strong>Veritabanı</strong></td>
    <td align="center"><strong>Deployment</strong></td>
  </tr>
  <tr>
    <td align="center">
      <a href="https://reactjs.org/" target="_blank"><img src="https://img.shields.io/badge/-React-61DAFB?logo=react&logoColor=white&style=for-the-badge" alt="React"></a><br>
      <a href="https://tailwindcss.com/" target="_blank"><img src="https://img.shields.io/badge/-TailwindCSS-38B2AC?logo=tailwind-css&logoColor=white&style=for-the-badge" alt="TailwindCSS"></a><br>
      <a href="https://www.typescriptlang.org/" target="_blank"><img src="https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white&style=for-the-badge" alt="TypeScript"></a>
    </td>
    <td align="center">
      <a href="https://fastapi.tiangolo.com/" target="_blank"><img src="https://img.shields.io/badge/-FastAPI-009688?logo=fastapi&logoColor=white&style=for-the-badge" alt="FastAPI"></a><br>
      <a href="https://www.python.org/" target="_blank"><img src="https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white&style=for-the-badge" alt="Python"></a>
    </td>
    <td align="center">
      <a href="https://www.postgresql.org/" target="_blank"><img src="https://img.shields.io/badge/-PostgreSQL-4169E1?logo=postgresql&logoColor=white&style=for-the-badge" alt="PostgreSQL"></a>
    </td>
    <td align="center">
      <a href="https://www.docker.com/" target="_blank"><img src="https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white&style=for-the-badge" alt="Docker"></a><br>
      <a href="https://www.nginx.com/" target="_blank"><img src="https://img.shields.io/badge/-Nginx-269539?logo=nginx&logoColor=white&style=for-the-badge" alt="Nginx"></a>
    </td>
  </tr>
</table>

---

## <a name="-kurulum"></a> 💻 Kurulum

Projeyi yerel makinenizde geliştirmeye başlamak için aşağıdaki adımları izleyin.

### **1. Ön Gereksinimler**
- Git
- Node.js (v16+) & npm
- Python (3.9+) & pip
- Docker (Opsiyonel, kolay kurulum için önerilir)

### **2. Ortam Değişkenleri (.env)**
Projenin çalışabilmesi için `backend` klasörü içine `.env` adında bir dosya oluşturun ve şablonu doldurun:
<details>
  <summary><strong><code>backend/.env.example</code> içeriğini görüntüle</strong></summary>
  
  ```bash
  DATABASE_URL="postgresql://user:password@localhost/secki_db"
  SECRET_KEY="COK_GIZLI_BIR_ANAHTAR_BURAYA_GELECEK"
  # Diğer ayarlar...
  ```
</details>

### **3. Kurulum Adımları**
```bash
# Projeyi klonlayın ve dizine girin
git clone [https://github.com/electrichunter/secki.git](https://github.com/electrichunter/secki.git)
cd secki

# Backend'i kurun ve çalıştırın (Terminal 1)
cd backend
pip install -r requirements.txt
uvicorn main:app --reload

# Frontend'i kurun ve çalıştırın (Terminal 2)
cd ../frontend
npm install
npm run dev
```
Uygulama artık `http://localhost:3000`'da, API ise `http://localhost:8000`'de çalışıyor olacak.

---

<detaylar>
  <özet><güçlü>📂 Proje Klasör Yapı ve API Referansını Görüntüle</güçlü></özet>

### <a isim="-proje-yapısı"></a> Klasör Yapı
'`'
secki/
├── arka uç/
│ ├── uygulaması/
│ └── main.py
├── ön uç/
│ ├── src/
│ └── App.tsx
└── README.md
'`'

### <a isim="-api-referansı"></a> API Referansı

| Yöntem | Uç nokta | Açıklama |
| :--- | :--- | :--- | 
| `GÖNDERI` | `/api/v1/auth/kayıt ol` | Yeni kullanıcı kaydı oluşturur. |
| `ALINMAK` | `/api/v1/kullanıcılar/ben` | Mevcut kullanıcın profil bilgilerini getirir. |
| `GÖNDERI` | `/api/v1/seçimler` | Yeni bir seçki (koleksiyon) oluşturur. |
| `ALINMAK` | `/api/v1/selections/{selection_id}`| Belirtilen ID'ye sahip seçkiyi getirir. |

</detaylar>

---

## <a isim="-katkıda-bulunma"></a> 🤝 Katkıda Bulunma

Seçki'yi daha da iyi bir hale getirmek için yapacağınız katkılara sonuna kadar açığız! Lütfen [Katkıda Bulunma Rehber'mizi (`KATKIDA BULUNMAK.md`)](https://github.com/electrichunter/secki/blob/main/CONTRIBUTING.md) okuyun ve projenin gelişimin dahil olmaktan çekinmeyin.

---

<div hizalamak="merkez">
  <i̇k>
  <p>Bu proje MIT Lisansı altında dağıtılmaktadır. Daha fazla bilgi iç <a href="LISANS">LISANS</a> dosyasına bakın.</p>
  <br>
  <a href="https://github.com/electrichunter/secki/graphs/contributors">
    <img src="https://contrib.rocks/image?repo=electrichunter/secki" />
  </a>
  <br><br>
  <p><güçlü>Ömer Faruk Uysal</güçlü></p>
  <p>
    <a href="https://github.com/electrichunter"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=beyaz" alt="GitHub"></a>
    <a href="https://www.linkedin.com/in/omerfarukuysal"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=beyaz" alt="Bağlantılı"></a>
  </p>
  <br>
  <p><küçük>Seçki © 2025</küçük></p>
</div>

[ ⁇ ️ Başa Dön](#)
