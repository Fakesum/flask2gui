# Flask2Gui
A Single find that you can install by:
```bash
git clone https://github.com/Fakesum/flask2gui.git
```

then you can use by:
```python
from flask2gui import gui_begin
import flask

app = flask.Flask(__name__)

@app.route("/")
def main():
    pass # Your Flask App here

if __name__ == "__main__":
    gui_begin(app)
```