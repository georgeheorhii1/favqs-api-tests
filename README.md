# Favqs API tests

## Description

Simple API tests for FavQs service using pytest and requests.
Covers basic endpoints such as quotes retrieval and user-related requests.
## Setup

1. Install dependencies:

```bash
pip install -r requirements.txt
```

2. Create `.env` file:

```bash
cp .env.example .env
```

3. Fill in your credentials in `.env`:

* API_KEY
* USER_LOGIN
* USER_EMAIL

## Run

```bash
pytest
```
