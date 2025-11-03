# StockTrace

**StockTrace** — lightweight open-source system for tracking resources and fuel.

### ⚙️ Stack
- Python 3.11+  
- FastAPI · SQLModel · SQLite  
- XLSX / PDF reports  
- APScheduler (scheduled backups)

### 💡 Features
- Local resource & fuel accounting  
- Import/export with Excel (OpenPyXL, XlsxWriter)  
- Automatic backups  
- Ready for web UI expansion  

### 🚀 Quick Start
```bash
pip install -r requirements.txt
uvicorn app.main:app --reload
