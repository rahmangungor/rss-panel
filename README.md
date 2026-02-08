# 📡 Sinyal: Minimalist RSS & YouTube Dashboard

**Sinyal**, modern web teknolojileriyle harmanlanmış, gazete estetiğine sahip minimalist bir içerik takip panelidir. Algoritmalardan kurtulup, kendi haber akışınızı özgürce yönetmeniz için tasarlandı.

[Canlı Demoyu Görüntüle](https://rahmangungor.github.io/rss-panel/) ---

## ✨ Özellikler

* **📰 Gazete Estetiği:** Okuma odaklı, göz yormayan "Newsreader" ve "Inter" tipografisi.
* **📺 YouTube Desteği:** Sadece kanal ID'si veya linki ile YouTube kanallarını takip edebilme.
* **🚀 Akıllı Proxy Sistemi:** CORS engellerini aşmak için otomatik değişen 3 farklı proxy katmanı.
* **💾 Gelişmiş Önbellek:** Verileri tarayıcı hafızasında (LocalStorage) saklayarak hızlı yükleme ve kota dostu kullanım.
* **🌓 Çift Görünüm:** İster "Kart" (Grid) görünümüyle görsel odaklı, ister "Liste" görünümüyle hızlı tarama.
* **💹 Ekonomi Paneli:** Güncel USD/TRY ve EUR/TRY kurlarını anlık takip edin.
* **📱 Tam Mobil Uyumluluk:** Responsive tasarım sayesinde her cihazda kusursuz deneyim.

---

## 🛠️ Teknik Detaylar

Bu proje "No-Backend" mantığıyla, tamamen istemci tarafında çalışır:

| Teknoloji | Kullanım Amacı |
| :--- | :--- |
| **Tailwind CSS** | Modern ve hızlı arayüz tasarımı |
| **Vanilla JavaScript** | Veri işleme ve DOM yönetimi |
| **Lucide Icons** | Minimalist ve vektörel ikon seti |
| **LocalStorage API** | Kullanıcı ayarları ve RSS kaynaklarının kalıcılığı |

### Nasıl Çalışır?
Sistem, eklediğiniz RSS linklerini asenkron olarak fetch eder. Tarayıcıların güvenlik (CORS) engellerine takılmamak için isteği güvenli proxy servisleri üzerinden yönlendirir ve gelen XML verisini JSON'a dönüştürerek ekrana basar.

---
### RSS Kaynak
https://gist.github.com/e-budur/983d969c0f6cf756bbbb60a2892aa964

###info
Created with Vibe Coding