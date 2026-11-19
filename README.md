# Laboratorium 8: regresja – ile wyda klient, który zostaje?

## Krok po kroku
1. **Use this template / Fork** (albo nowe repozytorium z plikami z zipa).
2. **Code → Codespaces → Create codespace on main**.
3. W terminalu:
   ```bash
   pip install -r requirements.txt
   ```
4. Otwórz `lab8_student.ipynb`, jądro **Python 3**, wykonuj komórki po kolei (*Shift + Enter*). Uzupełnij luki `___` (6 luk).
5. Zapisz pracę:
   ```bash
   git add .
   git commit -m "Lab 8: regresja"
   git push
   ```
6. **D3 (dla chętnych):** `app.py` to kalkulator ryzyka z laboratorium 7 (czyta już `klienci_wartosc.csv`). Dodaj prognozę wydatków i oczekiwany zysk z kuponu, sprawdź `streamlit run app.py` (port 8501), wdróż na Render (*New → Web Service*, ustawienia w `render.yaml`).

## Pliki
| Plik | Co to jest |
|---|---|
| `lab8_student.ipynb` | notatnik z zadaniami Z1–Z9 |
| `klienci_wartosc.csv` | 1206 klientów: dane z lab. 7 + `wydatki_6m` (dane syntetyczne) |
| `pieciu_klientow.csv` | 5 klientów do rozgrzewki (Z1) |
| `app.py`, `requirements.txt`, `render.yaml` | aplikacja z lab. 7 do rozbudowy (D3) |
