# Purpose
- the main purpose that we use nginx is that it takes incoming HTTPS request on port 80 and forwards them to th Flask application running locally. This way, users only interact with nginx and not the Flask server directly. 

# Benefits
- Security: flask app is ot exposed directly to the internet, mking the system safer
- Performance: nginx is better at handling multiple requests at once
- Easier access: users just use a normal web address without worrying about internal ports.
- Stability: nginx helps manage traffic so the Flask app doesn't get overloaded
