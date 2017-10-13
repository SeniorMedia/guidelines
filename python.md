# Python projects guidelines
A quick reminder on how to share your project with Seniormedia team when working with Python / Jupyter projects

## Dependencies
- Python >= 3.4
- Code has to be commented
- A `requirements.txt` file should install all required dependencies using a virtualenv and `pip install -r requirements.txt`

## Structure
- A `README.md` (or whatever extension you use) that describes system dependencies to install (brew, apt-get ...), what command / scripts to start (with correct order), algorythm sources ...
- All project sources (and only sources) have to be included into a `/src` root folder. Data files (like CSVs, txts ...) shouldn't be placed into this folder
- A `.env` file has to be placed in root folder where developer can easily set absolute paths for input and output required files and / or directories

## Versionning
- Project has to be hosted on Seniormedia Gitlab (except public libraires, numpy for example). Feel free to contact us if we didn't communicate you a git repository. No code has to be hosted on Github, even in private repository
