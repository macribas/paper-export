# Export Dropbox Paper Docs

## About
Python script to export Paper Docs from a Dropbox account.
It can export in either HTML or Markdown.
It only works in accounts that have Paper In the FileSystem (PiFS). Script checks the account for that condition.

## Usage
1. [Create an app and generate an API Key](https://www.dropbox.com/developers/reference/getting-started?_tk=guides_lp&_ad=guides2&_camp=get_started#app%20console). Needs to have files.content.read scope.
2. Replace <YOUR_API_KEY_HERE> by your API key
3. [Install Python3](python.org/downloads/)
4. Install the [Python Dropbox SDK](https://dropbox-sdk-python.readthedocs.io/en/latest/index.html)
```pip install dropbox```
5. Run `python3 paper.py` in the directory you cloned this repo
6. Follow the instructions on screen

## Disclaimer
Dropbox does not maintain this script and is not responsible for it. This is meant for educational purposes only.

## Contact
Marcel Ribas - @macribas - mribas@dropbox.com
https://github.com/macribas/paper-export
