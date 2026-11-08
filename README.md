# 📚 Haftalık Özel Ders Programı

Özel ders öğretmenleri için geliştirilmiş, takvim entegrasyonlu ve mobil uyumlu haftalık ders programı uygulaması (PWA).

## ✨ Özellikler

- **Takvim Entegrasyonu:** Geçmiş ve gelecek haftalar arasında gezinme (← → tuşları veya butonlarla).
- **Esnek Saat Dilimleri:** 30 dakikalık dilimler (örn: 16:00 – 17:30 gibi buçuklu dersler).
- **Saat Birleştirme:** Boş saatler üzerinde fare ile aşağı sürükleyerek veya kart üzerindeki `＋ / －` butonlarıyla hızlı süre ayarlama.
- **Ders Durumu Takibi:** Planlandı (🕒), Yapıldı (✅) ve İptal (❌) durumları; tek tıkla yapıldı işaretleme.
- **Öğrenci Özeti:** Haftalık toplam ders ve tamamlanan saatlerin öğrenci bazında listesi ve renk kodlaması.
- **Toplu Kopyalama:** Bir haftanın programını sonraki haftalara tek tıkla kopyalama.
- **Çevrimdışı ve PWA Desteği:** Masaüstü ve tabletlerde "Ana Ekrana Ekle" ile uygulama olarak tam ekran çalışabilme.
- **Yedekleme:** JSON formatında dışa aktarma (Export) ve içe aktarma (Import).

## 🚀 Çalıştırma

Herhangi bir kurulum gerektirmez. `index.html` dosyasını doğrudan tarayıcıda açabilir veya yerel bir sunucu ile çalıştırabilirsiniz:

```bash
# Python ile yerel sunucu başlatmak için:
python3 -m http.server 8080
```
Tarayıcınızda `http://localhost:8080` adresine gidin.
