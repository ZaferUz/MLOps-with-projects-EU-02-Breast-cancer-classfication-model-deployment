# download the main image as python3
FROM python:3.7.9

# Create working directory
WORKDIR /app

# Copy the current directory into the image's /app folder
COPY . /app

# Install all the dependicies we need to run our environtment 
RUN pip install -r requirements.txt

# Start the container
ENTRYPOINT ["python"]

CMD ["app.py"]
