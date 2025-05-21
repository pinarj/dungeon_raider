# Dungeon Raider 3D

🎮 Basit ama heyecanlı bir 3D zindan macera oyunu! Oyuncu olarak sandıkları toplayıp portallardan geçerek seviyeleri tamamlamaya çalışıyorsun. Dikkat! Seni kovalayan düşmandan kaçman gerek.

## 🚀 Proje Açıklaması

Bu proje, Python, PyOpenGL ve Pygame kullanılarak geliştirilmiş bir 3D oyun prototipidir. Oyunda bir oyuncu karakter, rastgele konumlandırılmış sandıkları toplar, düşmandan kaçar ve kapılardan geçerek bir sonraki seviyeye geçer. Oyunda toplam 3 seviye bulunur.

## 🛠 Gereksinimler

Aşağıdaki Python kütüphaneleri gereklidir:

```bash
pip install pygame PyOpenGL PyOpenGL_accelerate
```

## ⚙️ Nasıl Çalıştırılır?

1. Python 3.8+ kurulu olmalı.
2. Kod klasörünün içinde `assets/` adında bir klasör bulunmalı.
3. Aşağıdaki görseller `assets/` klasörüne eklenmelidir:
   - `player.png`
   - `chaser.png`
   - `treasure.png`
   - `acik_sandik.png` → (açık sandık için)
   - `gate.png`
   - `floor1.png`, `floor2.png`, `floor3.png` (her level için zemin)
   - `obstacle.png`

4. Oyunu başlatmak için terminalden:

```bash
python dungeon_raider.py
```

---

## 🎮 KEP (Kontrol Eylem Planı)

| Tuş         | Görev                                   |
|-------------|------------------------------------------|
| **W**       | Oyuncuyu ileri hareket ettirir           |
| **A**       | Oyuncuyu sola döndürür                   |
| **S**       | Oyuncuyu geri hareket ettirir            |
| **D**       | Oyuncuyu sağa döndürür                   |
| **Mouse**   | Kamerayı çevirerek çevreyi görmeni sağlar |
| **ESC**     | Oyunu kapatır                            |

---

## 📌 Özellikler

- 3 seviye boyunca zemin ve atmosfer değişimi
- Sandık toplandığında açık sandık animasyonu
- Kapıdan geçerek seviye atlama
- Düşmandan kaçma
- Skor sistemi ve süre sayaçlı HUD

---

> Bu oyun, eğitim amaçlı bir bilgisayar grafikleri projesidir. Öğrencilerin temel oyun mekaniği, 3D sahne yönetimi ve kullanıcı etkileşimi konularını öğrenmesine yardımcı olur.