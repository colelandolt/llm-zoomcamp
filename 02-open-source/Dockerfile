# Use the base image
FROM ollama/ollama

# Copy the contents of the local directory 'ollama_files' to '/root/.ollama' in the container
COPY ollama_files /root/.ollama

# Expose the port 11434
EXPOSE 11434

# Specify the default command to run in the container
CMD ["ollama run gemma:2b"]