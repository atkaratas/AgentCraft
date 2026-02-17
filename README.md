# AgentCraft: Ajan Fabrikası, Mikroservis Sandbox'ı ve Ücretsiz Yerel LLM

Bu repo, OpenClaw tabanlı otonom ajanların mikroservis mimarisiyle birbirine bağlı çalıştığı ve **Ollama** entegrasyonu sayesinde **tamamen ücretsiz** kullanılabildiği bir ekosistemdir.

## 🚀 Mimari
- **Lite AI Bots:** Ollama ile yerel çalışan, düşük gecikmeli ajanlar.
- **Microservices Mesh:** Ajanlar arası `sessions_send` protokolü.
- **0 Token Cost:** OpenAI/Anthropic ödemesi yapmadan kendi GPU/CPU'nuzda çalıştırın.

## 📂 İçerik
- `/templates`: 100+ Ajan profili (SOUL.md, IDENTITY.md).
- `/skills`: Mikroservis yetenekleri.
- `/docs`: **Ollama ile Ücretsiz Kullanım Rehberi** (`FREE_TIER_OLLAMA.md`).

## 🛠️ Hızlı Başlangıç (Ücretsiz Mod)
1. Ollama'yı yükleyin: `brew install ollama`
2. Modeli çekin: `ollama run qwen2.5-coder:7b`
3. Ajanı yerel makinenize indirin ve token ödemeden kullanmaya başlayın!

## 📖 Eğitim Rehberi
Ajanınızı eğitmek için `docs/TRAINING.md` dosyasını inceleyin.
