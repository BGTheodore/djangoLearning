sudo apt install python3-venv
mkdir flask_app && cd flask_app
python3 -m venv venv
source venv/bin/activate

(inside venv)
pip install Flask
python -m flask --version
export FLASK_APP=hello.py
flask run