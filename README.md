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
Don't forget to change the sessionId and the bearerToken in `index.html` (manually unfortunately)

note: get the session id by hitting `/get-session-id` with Postman for example