# ember

A progressive web app for decentralized resource distribution during
natural disaster relief.

## Build & Run

*To download the map file, you need to have Git LFS installed.*

Navigate to your desired directory, then clone the repository:

```bash
git clone https://github.com/hyojunm/ember.git
```

Set up a virtual environment and install dependencies:

```bash
python3 -m venv my_env
source my_env/bin/activate
python3 -m pip install -r requirements.txt
```

Initialize the sqlite database file (if needed):

```bash
python3 -m app.util.init_db
```

Run the app:

```bash
flask run --debug
```
