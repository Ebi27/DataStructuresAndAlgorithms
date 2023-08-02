FROM python:3.9-slim
WORKDIR /Netflix

# Copy the Python requirements file into the container
COPY requirements.txt .

# Install the required Python packages
RUN pip install -r requirements.txt

# Copy the rest of the application files into the container
COPY . /Netflix

