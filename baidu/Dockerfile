### 1. Get Linux
FROM python:3.6.4
RUN mkdir -p app
WORKDIR /app
COPY . /app
RUN pip install -r requirements.txt
ENV ENDPOINT=$ENDPOINT
ENV ADMIN_SECRET=$ADMIN_SECRET
ENV SPREADSHEET_ID=$SPREADSHEET_ID
ENV GOOGLE_CRED=$GOOGLE_CRED
CMD ["python", "/app/run.py"]
