# Anytranslate
Anytranslate is an wrapper API for google translate


This python program fetches the data from [Google translate](https://translate.google.com/) and provides them in a pythonic and usable way


## About

This is a API wrapper for Google Translate. This project was inspired from [google trans](https://pypi.org/project/googletrans/)

## How to use?
You can use this program by running following commands
```sh
sudo apt-get install poetry
git clone https://github.com/kbshal/Anytranslate
cd Anytranslate
poetry install
```

And finally start the program by 
```sh
uvicorn trans_api:app --reaload
```

## Why use this?

How is this better than [google trans]()?
- It is asynchronous.
- Data can be fetched in json format from endpoint
















