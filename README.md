Basic flask app template

This template includes:

- flask
- template folder
- static folder
    - css folder
    - js folder
- base html template
- main html template
- base css file
- base js file
- requirements.txt

env var (change as needed):

import os

os.environ.setdefault("IP", "0.0.0.0")
os.environ.setdefault("PORT", "5000")
os.environ.setdefault("SECRET_KEY", "THisIsMySecretKey")

All static files are linked to base html template, main html template inherets from base
