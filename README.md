# FastAPI VNPAY Payment Project

This is a FastAPI project to integrate VNPAY payment gateway.

## Installation

```bash
pip install fastapi uvicorn sqlalchemy
```

## Run the Project

```bash
uvicorn main:app --reload
```

## API Endpoints

- `/auth` - Authentication endpoints
- `/payments` - Payment processing endpoints
- `/webhooks` - Webhook endpoints to handle payment notifications