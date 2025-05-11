# Vercel Python API

This is a simple Python API deployed on Vercel that returns student marks based on names.

## API Usage

Make a GET request to the API endpoint with a `name` parameter:

```
GET /api?name=John&name=Alice
```

The response will be in JSON format:

```json
{
    "marks": [85, 92]
}
```

## Project Structure

```
TDS_W2_VERCEL/
├── api/
│   └── index.py
├── q-vercel-python.json
├── requirements.txt
└── README.md
```

## Local Development

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. Run the server:
   ```bash
   python -m http.server
   ```

## Deployment

This project is configured for deployment on Vercel. Simply push to your repository and Vercel will handle the deployment automatically. 