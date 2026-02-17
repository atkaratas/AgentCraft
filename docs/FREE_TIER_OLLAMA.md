# Ollama ile Ücretsiz Ajan Çalıştırma Rehberi

AgentCraft ajanlarını hiçbir token ücreti ödemeden, tamamen yerel (local) makinenizde çalıştırmak için bu adımları izleyin.

## 1. Ollama Kurulumu
Ajanların beyni olarak Ollama kullanacağız.
- **macOS:** `brew install ollama`
- **Windows/Linux:** [ollama.com](https://ollama.com) adresinden indirin.

## 2. Model İndirme
Ajanlarımız için optimize edilmiş modelleri indirin:
```bash
ollama run qwen2.5-coder:7b
# Veya daha hafif bir model için:
ollama run llama3.2:3b
```

## 3. OpenClaw Konfigürasyonu
`~/.openclaw/openclaw.json` dosyanızı Ollama'yı kullanacak şekilde güncelleyin:

```json
{
  "agent": {
    "model": "ollama/qwen2.5-coder:7b",
    "providers": {
      "ollama": {
        "url": "http://localhost:11434/v1"
      }
    }
  }
}
```

## 4. Avantajlar
- **0 Token Maliyeti:** Tüm işlemler sizin donanımınızda döner.
- **Gizlilik:** Verileriniz internete çıkmaz, Mac Mini'nizde kalır.
- **Hız:** İnternet gecikmesi olmadan anlık tepki.

---
*AgentCraft - Powered by OpenClaw & Ollama*
