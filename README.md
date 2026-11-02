# mywhoosh2garmin

Export the latest MyWhoosh activity to Garmin Connect.

## Setup

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
cp .env.example .env
# edit .env with your credentials
python main.py
```

Login/credentials are stored in `.env` (separate from source code).
