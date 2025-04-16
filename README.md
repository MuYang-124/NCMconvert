pyinstaller --onefile --noconsole --add-data "hook-crypto.py;." --hidden-import=Crypto convert.py
