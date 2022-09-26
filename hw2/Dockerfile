FROM python:3
COPY requirements.txt files/requirements.txt
RUN python -m pip install -r files/requirements.txt
COPY app.py files/app.py
EXPOSE 8080
CMD ["python", "files/app.py"]
