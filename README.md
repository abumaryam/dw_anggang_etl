Untuk Aktivasi

### 1. PowerShell (Default di VS Code)
Ketik perintah ini dan tekan Enter:
```powershell
.\.venv\Scripts\Activate.ps1
```
*Jika muncul error "Scripts is not digitally signed", jalankan perintah ini dulu sekali saja: `Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process` lalu ulangi perintah aktivasi.*

### 2. Command Prompt (CMD)
Ketik perintah ini dan tekan Enter:
```cmd
.venv\Scripts\activate
```

### 3. Git Bash
Ketik perintah ini dan tekan Enter:
```bash
source .venv/Scripts/activate
```

---

**Tanda jika sudah aktif:**
Anda akan melihat teks `(.venv)` muncul di awal baris perintah di terminal Anda, seperti ini:
`(.venv) PS C:\dev\data_warehouse\etl_process>`


Kemudian Jalankan:
```powershell
pip install sqlalchemy pandas psycopg2-binary prefect
```