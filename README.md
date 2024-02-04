# TechMinds-AI
OPEN YAM.HTML TO INTERACT WITH BOT
Directory Structure:
- backend: Python FastAPI backend code.   -files for backend -> main.py, db_helper,generic_helper;
- db: Database dump for MySQL (import using MySQL Workbench).    food.sql
- dialogflow_assets: Training phrases and intents for Dialogflow.     - assets traing phases file
- frontend: Code for the website.     - Yum.html images and stuff

Module Installation:

pip install mysql-connector
pip install "fastapi[all]"

Or, use the requirements file:

pip install -r backend/requirements.txt


Starting FastAPI Backend Server:
1. Navigate to the backend directory in your command prompt.
2. Run:

uvicorn main:app --reload


Using ngrok for HTTPS Tunneling:
1. Install ngrok from https://ngrok.com/download.
2. Place ngrok.exe in a folder.
3. In the command prompt, run:

ngrok http 8000

Note: Ngrok sessions may timeout; restart if a "session expired" message appears.


OPEN YAM.HTML TO INTERACT AND TEST THE BOT

