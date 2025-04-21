pyinstaller --onefile --noconsole --add-data "hook-crypto.py;." --hidden-import=Crypto convert.py

将exe文件放在ncm文件所在的目录下，运行即可转换。
