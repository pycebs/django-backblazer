# django-backblazer
Django plugin for the Backblaze B2 Cloud Storage

## Installation
```
pip install django-backblazer
```

## Usage
Add the relevant variables to your settings.py file
```
BACKBLAZEB2_ACCOUNT_ID = 'your-account-id'
BACKBLAZEB2_APP_KEY = 'your-app-key'
BACKBLAZEB2_BUCKET_NAME = 'bucketname'
```
and make django-backblazer your default Django storage:
```
DEFAULT_FILE_STORAGE = 'xxx'
```

