# Free Tier Agent Execution with Ollama

Follow these steps to run AgentCraft agents on your local machine with zero token costs.

## 1. Install Ollama
We use Ollama as the local brain for our agents.
- **macOS:** `brew install ollama`
- **Windows/Linux:** Download from [ollama.com](https://ollama.com).

## 2. Download a Model
Download the optimized models for our agents:
```bash
ollama run qwen2.5-coder:7b
# Or for a lighter model:
ollama run llama3.2:3b
```

## 3. OpenClaw Configuration
Update your `~/.openclaw/openclaw.json` file to use Ollama:

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

## 4. Advantages
- **Zero Token Cost:** All processing happens on your hardware.
- **Privacy:** Your data stays on your machine and never leaves your network.
- **Speed:** Instant response without internet latency.

---
*AgentCraft - Powered by OpenClaw & Ollama*
