# Ajan Eğitimi ve Özelleştirme Rehberi

OpenClaw ajanları üç ana dosya üzerinden eğitilir:

### 1. IDENTITY.md (Kimlik)
Ajanın adı, türü ve temel karakterini belirler.
### 2. SOUL.md (Ruh ve Mantık)
Ajanın nasıl düşüneceği, karar vereceği ve tonu.
### 3. TOOLS.md (Yetenekler)
Ajanın kullanabileceği araçların (skills) listesi.

## Mikroservis Bağlantısı
Bir ajanın diğerine görev devretmesi için:
`sessions_spawn(target_agent, task)` komutunu kullanın.
