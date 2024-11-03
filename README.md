# moodlex_backend

How to start the container:
1. Type in command line from the directory with the main.py: docker build -t moodlex_backend .
2. Then type next command: docker run -d --name moodlex-backend-container -p 8000:8000 moodlex_backend