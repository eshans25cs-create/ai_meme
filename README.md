
# AI Meme Generator (Simple)

Lightweight hackathon-ready prototype (simple version). Generates a meme from an uploaded image using a vision captioner and a small text generator, then overlays text on the image.

## What's included
- `app/streamlit_app.py` — Streamlit web UI to upload image and generate meme
- `src/meme_generator.py` — Simple pipeline (caption fallback + witty caption using a prompt)
- `assets/impact.ttf` — placeholder (not included, add an Impact-like TTF if you want)
- `demo/demo_script.txt` — 3-min demo script
- `slides/slide_notes.md` — slide content for editing the PPT

## Setup (local)
1. Extract this repo folder.
2. Create and activate a virtualenv:
   ```bash
   python -m venv venv
   source venv/bin/activate   # Windows: venv\Scripts\activate
   ```
3. Install requirements:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the app:
   ```bash
   streamlit run app/streamlit_app.py
   ```

## Notes
- This simple prototype uses small models and safer defaults. For better captions, swap the generation model with a larger LLM or use API-based models.
- Add an Impact-style font at `assets/impact.ttf` for classic meme look (optional).
- The project is ready to be uploaded to GitHub: extract the ZIP and upload the folder contents to a new repository.

