# VLESS Panel

A Python FastAPI-based VLESS/XHTTP panel.

## Stack

- Python
- FastAPI
- Uvicorn
- HTTPX
- WebSocket
- XHTTP

## Entry Point

The application entry point is:

`main.py`

## Run

```bash
pip install -r requirements.txt
uvicorn main:app --host 0.0.0.0 --port 8000
