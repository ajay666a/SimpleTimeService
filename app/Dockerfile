FROM python:3.11-slim

RUN useradd -m appuser
WORKDIR /home/appuser

COPY --chown=appuser:appuser app.py requirements.txt ./

RUN pip install --no-cache-dir -r requirements.txt

USER appuser
EXPOSE 8080
CMD ["python", "app.py"]
