# Step 1: Create a python venv

```
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

# Step 2: Remove the previous git

```
rm -rf .git
git init
```

# Step 3: Install pre-commit

```
pre-commit install
```
