FROM python:3.12

WORKDIR /PythonProject_Logika_Informatika

COPY . .
COPY requirements.txt requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 5000

CMD ["gunicorn", "-b", "0.0.0.0:5000", "app:app"]



