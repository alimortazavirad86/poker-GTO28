# Poker GTO Helper — Unified (Big Table)

Single-file Streamlit app with:
- Big visual table (Plotly) with seats, blinds, actions, pot evolution
- Decision box with best action + full action percentages
- **Mode toggle:** Strict GTO vs Exploit + ICM
- Entry point: `streamlit_app.py`

## Run locally
```bash
pip3 install -r requirements.txt
streamlit run streamlit_app.py
```

## Deploy (Streamlit Cloud)
- Repo root must contain `streamlit_app.py` and `requirements.txt`
- Set **Main file path** = `streamlit_app.py`
