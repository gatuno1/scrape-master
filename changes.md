# Changes Log

## Latest changes

Updated change log

## Commit 1fd6cd9 - Jan 20, 2025

Add change log & app debug config

- Added `changes.md` file: to maintain changes log.
- Added streamlit app debug configuration for VSCode.

## Commit d4e9ec9 - Jan 15, 2025

- Bugfix: migrated to v1.0 call
  When using generic openai-compatible model, the chat completation call is using `client` object as recommended in v1.0 API.

## Commit 6fef093 - Jan 14, 2025

Prompt improvement & some linting.

- Modifications on scaper and pagination Prompts, to be clearer for the LLM.
- Added links to Youtube videos for this project in `README.md`, as [`silasneo/scrape-master`](https://github.com/silasneo/scrape-master) fork did.

## Commit 6fb318d - Jan 14, 2025

- Bugfix: duplicated text in pagination prompt.
  Removed error of adding twice the main pagination prompt text when scraping for pagination links with a LLM call.

## Commit de25815 - Jan 13, 2025

- Formatting & linting on all files.
  Includes removal of unused imports, removal of old comments, added header with she-bang for python, formatted python code for better readability, corrected problems with f-strings and logging options, etc.

## Commit 9a88bbb - Jan 9, 2025

- Created `.gitignore` file with exclusions for `output` dir, and common cases for python, virtual environment, windows, vscode and pycharm.
  Hint from [`amgrbi96/AI-scraper`](https://github.com/amgrbi96/AI-scraper) fork.
- Streamlit opt-out configuration added.
- Ordered contents of `requirements.txt` files.
- Removed empty `test.py` file.
