# BestAI Models

Modelli GGUF (**Q5_K_M**) per l'app **BestAI** — un comico surreale che gira **in locale** sul telefono (llama.cpp).
Ogni lingua ha **2 taglie**: **BestAI 1.0** (Qwen3-0.6B, leggero) e **BestAI Pro 1.0** (Qwen3-1.7B, più coerente).

> ⚠️ **I modelli NON sono nella lista dei file qui sopra** — sono troppo grandi (>100 MB, limite di GitHub).
> Stanno nelle **[Releases](../../releases)**, la sezione giusta per i file binari. Link diretti qui sotto. 👇

## Download

### 🇮🇹 Italiano — release [`it-v4`](../../releases/tag/it-v4)
| Taglia | Modello | Dimensione | Download |
|---|---|---|---|
| BestAI 1.0 | Qwen3-0.6B | 444 MB | [bestai-it-standard-q5.gguf](../../releases/download/it-v4/bestai-it-standard-q5.gguf) |
| BestAI Pro 1.0 | Qwen3-1.7B | 1,26 GB | [bestai-it-pro-q5.gguf](../../releases/download/it-v4/bestai-it-pro-q5.gguf) |

### 🇬🇧 English — release [`en-v4`](../../releases/tag/en-v4)
| Taglia | Modello | Dimensione | Download |
|---|---|---|---|
| BestAI 1.0 | Qwen3-0.6B | 444 MB | [bestai-en-standard-q5.gguf](../../releases/download/en-v4/bestai-en-standard-q5.gguf) |
| BestAI Pro 1.0 | Qwen3-1.7B | 1,26 GB | [bestai-en-pro-q5.gguf](../../releases/download/en-v4/bestai-en-pro-q5.gguf) |

### 🇫🇷 Français — release [`fr-v4`](../../releases/tag/fr-v4)
| Taglia | Modello | Dimensione | Download |
|---|---|---|---|
| BestAI 1.0 | Qwen3-0.6B | 444 MB | [bestai-fr-standard-q5.gguf](../../releases/download/fr-v4/bestai-fr-standard-q5.gguf) |
| BestAI Pro 1.0 | Qwen3-1.7B | 1,26 GB | [bestai-fr-pro-q5.gguf](../../releases/download/fr-v4/bestai-fr-pro-q5.gguf) |

🇩🇪 Deutsch · 🇪🇸 Español — *in arrivo.*

## Dettagli tecnici

- **Base:** Qwen3-0.6B / Qwen3-1.7B, fine-tuning **QLoRA** (unsloth).
- **Quantizzazione:** Q5_K_M (buon compromesso qualità/peso per mobile).
- **Dataset:** v4 esteso (~8.900 esempi/lingua), generato con un blend di modelli "maestro".
- **Stile:** risposte assurde/surreali comiche a domande normali, una sola idea, 2-3 frasi.

## Checksum (md5)

| File | md5 |
|---|---|
| bestai-it-standard-q5.gguf | `fde626a7974e23b86b0669afcb03a842` |
| bestai-it-pro-q5.gguf | `88932b2966f682e214338805c62cf6d5` |
| bestai-en-standard-q5.gguf | `f2f407be1560c1a624a0d8162c215455` |
| bestai-en-pro-q5.gguf | `e2afa6facc9922327a99c377fc8ab720` |
| bestai-fr-standard-q5.gguf | `b04d4175a1f3f63cb929bc4b0b39aebf` |
| bestai-fr-pro-q5.gguf | `a2eed8ea9332ef43ece047e726564846` |
