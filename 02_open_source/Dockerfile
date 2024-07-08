# Use the official Ollama image as the base
FROM ollama/ollama:latest

# Set the working directory
WORKDIR /app

# Copy the local ollama folder with the model into the container
COPY ./ollama /root/.ollama

# Expose the port used by Ollama (default is 11434)
EXPOSE 11434

# Run Ollama when the container starts
CMD ["ollama", "serve"]