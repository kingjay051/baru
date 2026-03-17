# Clone Repo anda
```
git clone repo && cd nama repo
```

# run setup
```
bash setup.sh
```

# Ruun systemd
```
bash systemd.sh
```
# Pastikan config.py sudah terisi data yang diperlukan
```
OWNER_ID = int(os.environ.get('OWNER_ID', ''))
BOT_TOKEN = os.environ.get('BOT_TOKEN', '')
DATABASE_ID = int(os.environ.get('DATABASE_ID', ''))
MONGO_URL = os.environ.get('MONGO_URL', '')

API_ID = 
API_HASH = ''
```
<a href="https://heroku.com/deploy?template=https://github.com/kingjay051/baru">
  <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy">
</a>
