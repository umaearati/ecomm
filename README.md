<!-- uv --version
python
import shutil
print(shutil.which("uv"))
exit()
uv init ecomm
cd ecomm
code .
change pythonversion and toml file to 3.10
uv venv --python 3.10
source .venv/bin/activate
python --version

uv sync


git init
git add .
git commit -m "initial commit"
git remote add origin https://github.com/umaearati/ecomm.git
git branch -M main
git push -u origin main

git add .
git commit -m "your message"
git push
 -->
