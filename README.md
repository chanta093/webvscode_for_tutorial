1.
```
python -m venv myenv
```
2.
```
source myenv/bin/activate
```
3.
```
pip install --upgrade pip
```
4.
```
sudo apt-get update
```
5.
```
sudo apt-get install build-essential
```
6.
```
wget http://prdownloads.sourceforge.net/ta-lib/ta-lib-0.4.0-src.tar.gz
tar -xvzf ta-lib-0.4.0-src.tar.gz
cd ta-lib/
./configure --prefix=/usr
make
> sudo make install
> cd ..
```

7.
```
pip install TA-Lib
```
8.
```
pip install -r requirements.txt
```
