## `flask`

## How to run

### Register your app

Visit "My apps" console and set

- Name: as you like
- Redirect uris: `http://127.0.0.1:5000/callback`

Set scopes (whitelists) in "Authorization scopes" panel.

- [x] report:eye-color
- [x] report:beard-thickness
- [x] report:morning-person

### Run your app

```
$ pip install -r requirements.txt
$ export GENOMELINK_CLIENT_ID=<your_client_id>
$ export GENOMELINK_CLIENT_SECRET=<your_client_secret>
$ export GENOMELINK_CALLBACK_URL="http://127.0.0.1:5000/callback"
$ python app.py
```

then, visit `http://127.0.0.1:5000`

## How it works

See https://github.com/AWAKENS-dev/api-oauth-example-flask/issues/1
