# AI Comedy Video Factory (Zero-Cost Automated Reels/Shorts Pipeline)
 
Automated 24/7 Indian Anthropomorphic Animal Comedy Video Factory running on **GitHub Actions + Kaggle Free GPU + Telegram Bot Delivery**.
 
## Repository Structure
- `kaggle/worker.py` — Complete 4-Phase Production Engine (DeepSeek/Groq/Gemini Script Director, FLUX.1-schnell + Img2Img Character Consistency Lock, Edge-TTS + gTTS Voice & Viral `.ass` Captions, Wan 2.2 Motion Animation, Pure-Python Studio SFX, and FFmpeg `-14 LUFS` Mastering).
- `kaggle/kernel-metadata.json` — Kaggle GPU Kernel Configuration.
- `.github/workflows/daily_factory.yml` — Scheduled twice-daily GitHub Actions trigger (8:00 AM IST & 6:00 PM IST).
 
## Required GitHub Actions Secrets
Go to **Settings > Secrets and variables > Actions** and add:
- `KAGGLE_USERNAME` (Required)
- `KAGGLE_KEY` (Required)
- `TELEGRAM_BOT_TOKEN` (Required)
- `TELEGRAM_CHAT_ID` (Required)
- `GROQ_API_KEY` or `DEEPSEEK_API_KEY` or `GEMINI_API_KEY` or `OPENROUTER_API_KEY` (At least one LLM key; offline fallback included)
- `HF_TOKEN` (Optional — for gated FLUX.1-schnell; auto-falls back to ungated SDXL-Turbo if omitted)
