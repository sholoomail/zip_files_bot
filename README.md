# ZIP files telegram bot

A simple telegram bot that takes a list of files sent by the user and returns them zipped.

# Usage

To be able to run the code you need to rename `config.sample.ini` to `config.ini` and fill out the needed credentials. `session_dsn` is the session name wanted.

# Notes

 - The bot uses dictionaries to save states so it's not persistent between runs. 
 - The bot uses https://github.com/ukinti/garnet/ as the FSM. The storage type can be changed there.
 - The bot saves files in a temp directory.
 - The bot does not support password protection yet.

# Deploy


### Deploy To Render (Paid)

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?)


[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/sholoomail/zip_files_bot)
