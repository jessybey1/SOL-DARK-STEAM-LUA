# 🛡️ SOLIDARK 

SOLIDARK, Lua dosyalarını hızlı, güvenli ve şık bir arayüzle yönetmek, düzenlemek ve optimize etmek için geliştirilmiş yeni nesil bir masaüstü yardımcı aracıdır. Windows işletim sistemiyle tam uyumlu, koyu cam görünümlü (Acrylic Glass effect) modern ve estetik bir kullanıcı arayüzü sunar.

---

## ✨ Özellikler

* **Modern & Estetik Arayüz:** Koyu tema severler için özel olarak tasarlanmış, yarı saydam ve Windows akrilik bulanıklık efektli şık gamer arayüzü.
* **Gelişmiş Lua Yamalama Motoru:** Lua betiklerinizi analiz eder, kritik sözdizimi ve tanımsız-ad hatalarını tarayarak güvenli bir biçimde devre dışı bırakır veya yamalar.
* **Hata Bildirim Sistemi:** Gecikmeli hata bildirimleri ve dinamik değişken kapsamı kontrolleriyle kodunuzdaki sorunları anında tespit eder.
* **Hafif ve Bağımsız:** Herhangi bir Python kurulumuna gerek duymadan, her bilgisayarda tek tıkla doğrudan çalışır (`.exe`).

---

## 🚀 Çalıştırma ve Kullanım

SOLIDARK tamamen bağımsız bir Windows programı (`.exe`) olarak derlenmiştir. Çalıştırmak için Python veya herhangi bir ek kütüphane kurmanıza gerek yoktur.

1. `dist` klasörü içerisindeki **`SOLIDARK.exe`** dosyasına çift tıklayın.
2. Açılan modern arayüz üzerinden işlem yapmak istediğiniz Lua dosyalarını seçin.
3. Analiz ve yamalama işlemlerini tek tıkla başlatın.

---

## 🛠️ Geliştiriciler İçin (Kaynak Koddan Çalıştırma)

Eğer projeyi kaynak koddan düzenlemek ve Python ortamında çalıştırmak isterseniz:

### Gereksinimler
* Python 3.14+ (Tkinter desteği aktif olmalıdır)
* Pillow (Görsel işleme için)

### Kurulum ve Çalıştırma
```bash
# Gerekli kütüphaneleri kurun
pip install Pillow

# Programı çalıştırın
python SOLIDARK.py
