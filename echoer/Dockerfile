FROM python:3.12

# Create app directory
WORKDIR /app

# Install app dependencies
COPY server.py /app

EXPOSE 8080
CMD [ "python", "server.py" ]