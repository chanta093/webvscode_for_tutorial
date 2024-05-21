
順番にターミナルで実行していく

1.
```
git clone https://github.com/chanta093/webvscode_for_tutorial.git
```
2.
```
python -m venv myenv
```
3.
```
source myenv/bin/activate
```
4.
```
pip install --upgrade pip
```
5.
```
sudo apt-get update
```
6.
```
sudo apt-get install build-essential
```
7.
```
wget http://prdownloads.sourceforge.net/ta-lib/ta-lib-0.4.0-src.tar.gz
tar -xvzf ta-lib-0.4.0-src.tar.gz
cd ta-lib/
./configure --prefix=/usr
make
sudo make install
cd ..
```

8.
```
pip install TA-Lib
```
9.
```
pip install -r requirements.txt
```
