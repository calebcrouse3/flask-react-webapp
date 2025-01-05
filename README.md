Basic Setup:
- Poetry project `backend` in the project directory for python dependency management
- `backed` folder with flask code
- Run `npm create vite@latest frontend -- --template react` from project directory to initialize react app


Run Dev Server:
- Terminal 1: 
  - `poetry run python backend/main.py`
- Terminal 2:
  - `cd frontend`
  - `npm run dev`