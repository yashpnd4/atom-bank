# Atom Bank

One bank account project, built twice:

- `console/main.py` is an object-oriented Python console application using only the standard library.
- `web/app.py` is a Streamlit web application.
- Both versions store demo accounts in their own `data.json`.

## Console version

```bash
cd console
python main.py
```

## Web version

```bash
cd web
python -m pip install -r requirements.txt
streamlit run app.py
```

This repository is an educational demo, not a real banking system. The included JSON stores start empty and contain no personal information or credentials.
