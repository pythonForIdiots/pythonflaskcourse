# Writing your first flask app
1. We gonna start with a simple hello world app! The first step is creating a file app.py in your application folder.
2. Subsequently use Visual Studio Code to insert following code step by step. Lines that start with "#“ do not contain code, but helpful instructions for you: 
```python
#Load the applications you need to run for your first webserver
from flask import Flask
#Create an app that hosts the service 
app = Flask(__name__)
#app.route tell your server to which url it should respond. "/" means your base folder such as example.com/
@app.route('/')

def index():
    return "Web App with Python Flask!"

if __name__ == "__main__":
#app.run starts the app and contains variables and configures the app to run on localhost ("host=0.0.0.0"), the port (you can use a different one than 80) and sets it in debug mode ("debug=True")
    app.run(host='0.0.0.0', port=80, debug=True)
```
3. Now, if you get back to your terminal, running the following command should result in white website showing "Web App with Python Flask!" when you open [this link (http://localhost/)](http://localhost/)
```bash
python3 app.py
```
