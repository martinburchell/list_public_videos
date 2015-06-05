# list_public_videos

Lists any public videos on your YouTube account

## Set up

```
$ virtualenv ~/my_virtual_env
$ source ~/my_virtual_env/bin/activate
$ pip install google-api-python-client
```

1. Go to https://cloud.google.com/console and create a new project
2. Enable the YouTube Data API v3
3. Under **Credentials** create a new client ID for an installed application
4. Download the json and save it as `client_secrets.json` in the same directory as the script

```
$ ~/my_virtual_env/bin/python list_public_videos.py
```
