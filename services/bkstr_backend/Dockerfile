FROM tiangolo/uvicorn-gunicorn-fastapi:python3.7

COPY . .

EXPOSE 5000

CMD ["uvicorn", "src.bookstore:app", "--reload", "--host", "0.0.0.0", "--port", "5000"]