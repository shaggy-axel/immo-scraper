# installation
```bash
git clone git@github.com:shaggy-axel/immo-scraper.git && cd immo-scraper
python3.9 -m venv .venv
. .venv/bin/activate
pip install -r requirements.txt
cat env_sample > .env # and change env values in .env
```

# run scraper
```
python src/manage.py
```