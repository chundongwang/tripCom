# tripCom
Trip companion


## Setup
```
python -m venv .venv
.venv\Scripts\Activate.ps1
pip install pip-tools
pip-compile requirements.in
pip install -r requirements.txt
```

Make sure `.streamlit\secrets.toml` is created with following content:
```
OPENAI_API_KEY=XXX
```

## Run
```
streamlit run .\streamlit_app.py
```