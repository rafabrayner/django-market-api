# Pull base image
FROM python:3.11

# Set environment variables
ENV PIP_DISABLE_PIP_VERSION_CHECK 1
ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1

# Set work directory
WORKDIR /code

# Install dependencies
COPY requirements.txt .
RUN echo "nameserver 8.8.8.8" > /etc/resolv.conf \
    && apt-get update \
    && apt-get -y install libpq-dev gcc \
    && pip install -r requirements.txt

# Copy project
COPY . .