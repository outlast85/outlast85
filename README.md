# Gal Cohen

Applied AI engineer 

Daily work spans frontier LLMs (Claude Opus, GPT-5, Haiku), diffusion video (Seedance, Kling, Wan, LTX), generative image (Nano Banana, Flux, Seedream), audio (MMAudio, ElevenLabs), and AI upscaling (SeedVR2) — through direct provider APIs and self-tuned local-GPU pipelines on a dual-GPU workstation (RTX 5090 + 3060).

## Open-source portfolio

Production workers + tools I run on my own rig. Each repo has a deep README explaining the model selection, hardware tuning, and architectural decisions.

| Repo | What |
|---|---|
| [seedvr2-worker](https://github.com/outlast85/seedvr2-worker) | SeedVR2 7B video upscaler — production-tuned for RTX 5090, 480p → 1080p in ~4m 29s |
| [ltx-worker](https://github.com/outlast85/ltx-worker) | LTX-2.3 22B distilled FP8 FLF2V worker — ComfyUI backend, Blackwell-tuned |
| [wan22-worker](https://github.com/outlast85/wan22-worker) | Wan 2.2 14B I2V worker — VRAM-maximized for RTX 5090, two-phase denoising |
| [wan21-worker](https://github.com/outlast85/wan21-worker) | Wan 2.1 T2V 1.3B worker — right-sized inference on RTX 3060 |
| [mmaudio-worker](https://github.com/outlast85/mmaudio-worker) | MMAudio ambient audio worker — two-phase Scout/Generate pipeline |
| [investor-tracker](https://github.com/outlast85/investor-tracker) | Python CLI for investor research — DuckDuckGo + 9 source scrapers, fuzzy bilingual dedup, LLM scoring |
