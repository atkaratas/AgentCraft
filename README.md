# Warlock4: Ajan Fabrikası ve Mikroservis Sandbox'ı

Bu repo, OpenClaw tabanlı otonom ajanların mikroservis mimarisiyle birbirine bağlı çalıştığı bir ekosistemdir.

## 🚀 Mimari
- **Lite AI Bots:** Düşük gecikmeli, spesifik görev odaklı mikro-ajanlar.
- **Microservices Mesh:** Ajanlar arası `sessions_send` ve `sessions_spawn` protokolü ile iletişim.
- **Sandbox:** Docker üzerinde izole edilmiş güvenli çalışma ortamı.

## 📂 İçerik
- `/templates`: 100+ Ajan profili (SOUL.md, IDENTITY.md).
- `/skills`: Mikroservis yetenekleri (API entegrasyonları, sistem kontrolü).
- `/docs`: Ajan eğitimi ve kurulum rehberleri.

## 🛠️ Kurulum
Ajanları yerel makinenize indirmek için:
```bash
git clone https://github.com/atkaratas/warlock4.git
cd warlock4
# Ajanı OpenClaw workspace'ine kopyalayın
cp -r templates/agent-name ~/.openclaw/workspace/
```

## 📖 Eğitim Rehberi
Ajanınızı eğitmek için `docs/TRAINING.md` dosyasını inceleyin.
