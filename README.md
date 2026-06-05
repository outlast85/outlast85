# Gal Cohen

Applied AI engineer and founder. Hands-on since the GPT-3 launch in 2020.

I build multi-agent generative systems end-to-end — agent design, eval methodology, model selection, cross-provider failover, and production deployment. In 2026 I launched [Dobidy](https://dobidy.com), a live AI video product, with a US provisional patent on its multi-agent architecture.

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

## Stack

- **AI:** multi-agent orchestration, Best-of-N eval with judge models, prompt engineering, structured output (OpenAI strict JSON + Anthropic tool_use)
- **Providers:** Anthropic, OpenAI, BytePlus ModelArk, fal.ai, ElevenLabs, Vercel AI SDK
- **Diffusion stack:** ComfyUI, FP8 / int8 / GGUF quantization tradeoffs on Blackwell, dual-GPU scheduling
- **Production:** Next.js / React / TypeScript, Prisma + Postgres, Redis, Inngest, Vercel, Clerk, LemonSqueezy

## Connect

- LinkedIn: [linkedin.com/in/gal-cohen-b4958a373](https://www.linkedin.com/in/gal-cohen-b4958a373/)
- Live product: [dobidy.com](https://dobidy.com)
