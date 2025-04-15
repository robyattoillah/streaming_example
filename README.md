# Setup
Create environment:
```
python -m venv env
```

Activate environment:
```
# Windows
.\env\Scripts\activate

# Linux
source env/bin/activate
```

Install dependencies:
```
pip install -r requirements.txt
```

Running the apps:
```
python main.py
```

# Using the apps
- Head to `http://localhost:8005/static/index.html` to access the UI

Note:
- Change the apiUrl in `index.html` to the url of the chatbot endpoint
- Don't forget to change the sessionId and the bearerToken in `index.html` (manually unfortunately)

note: get the session id by hitting `/get-session-id` with Postman for example