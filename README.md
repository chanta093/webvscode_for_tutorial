1.
```
python -m venv myenv
```

```
source myenv/bin/activate
```
```
pip install --upgrade pip
```
3.
```
sudo apt-get update
```
4.
```
sudo apt-get install build-essential
```
5.
```
wget http://prdownloads.sourceforge.net/ta-lib/ta-lib-0.4.0-src.tar.gz
tar -xvzf ta-lib-0.4.0-src.tar.gz
cd ta-lib/
./configure --prefix=/usr
make
> sudo make install
> cd ..
```

6.
```
pip install TA-Lib
```
7.
```
pip install -r requirements.txt
```
