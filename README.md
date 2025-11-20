# Verse AI (AGI-XΩ) — Core

**Short:** Verse AI | Central brain of the Godverse. Multi-modal, adaptive, autonomous assistant (in development).

## What this repo contains
- `src/` : main python scripts
- `requirements.txt` : dependencies
- `README.md` : this file
- `.gitignore` : ignore rules

## Quick start (Termux)
1. Clone: `git clone https://github.com/<yourname>/Verse-AI.git`
2. `cd Verse-AI`
3. Create virtual env (optional): `python -m venv venv && source venv/bin/activate`
4. Install deps: `pip install -r requirements.txt`
5. Run: `python src/verse_ai.py`

## Notes
- Do NOT push large model files or secrets. Use cloud storage (Google Drive/S3) or Git LFS.
- Audio testing uses Termux `termux-microphone-record` (requires phone permission).