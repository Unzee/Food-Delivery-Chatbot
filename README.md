# Food-Delivery-Chatbot


About files-

1.main.py, generic_helper.py, db_helper.py: Contains Python FastAPI backend code.

2.db.sql: Contains the database. This is imported into MySQL db by using MySQL workbench tool.

3.index.html, style.css: website code.


Installing these modules are necessary-

1.pip install mysql-connector.

2.pip install "fastapi[all]".


To start fastapi backend server-
1. Go to backend directory in command prompt
2. Run this command: uvicorn main:app --reload

ngrok for https tunneling-
1. To install ngrok, go to https://ngrok.com/download and install ngrok version that is suitable.
2. Extract the zip file and place ngrok.exe in a folder.
3. Open windows command prompt, go to that folder and run this command: ngrok http 80000

NOTE: ngrok can timeout. It is needed to restart the session if session expired message pops up.
