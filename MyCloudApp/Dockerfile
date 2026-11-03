# 1. Base Image choose karein
FROM python:3.9-slim

# 2. Working directory set karein
WORKDIR /app

# 3. Requirements file copy karke packages install karein
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

# 4. Baaki saara application code copy karein
COPY . .

# 5. Application ka port expose karein
EXPOSE 5000

# 6. Container run hone par yeh command chalegi
CMD ["python", "app.py"]
