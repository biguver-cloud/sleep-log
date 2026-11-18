# sleep-log

睡眠と翌日の気分・体調の関係を記録して振り返る個人用アプリ(FastAPI + Next.js)

## 構成

```
backend/   FastAPI(API サーバー)
frontend/  Next.js(画面)
```

## 開発環境のセットアップ

### バックエンド

```powershell
cd backend
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
fastapi dev app/main.py   # http://localhost:8000 (API ドキュメント: /docs)
pytest                    # テスト
```

### フロントエンド

```powershell
cd frontend
npm ci
npm run dev   # http://localhost:3000
```
