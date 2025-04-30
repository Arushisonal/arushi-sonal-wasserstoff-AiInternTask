# arushi-sonal-wasserstoff-AiInternTask
📌 How to Play

Enter a seed word (e.g., "Rock") to start the game.
Type a guess that might "beat" the current word.
The AI determines if it beats the previous.
If correct, the score increases and your answer is saved.
If duplicate, the game ends.


⚙️ Tech Stack

Backend: FastAPI + Python
Frontend: HTML/CSS/JavaScript
Database: PostgreSQL
Cache: Redis
AI Integration: OpenAI API
Deployment: Docker & Docker Compose

🚀 How to Run
python3 -m venv AI
source AI/bin/activate
pip install -r requirements.txt
docker login -u aruhi04
docker-compose  up -d
uvicorn backend.main:app --reload



