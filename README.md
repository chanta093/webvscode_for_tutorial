1.
>  python -m venv myenv
2.
> source myenv/bin/activate

> pip install --upgrade pip

3.
> sudo apt-get update
4.
> sudo apt-get install build-essential

5.
> wget http://prdownloads.sourceforge.net/ta-lib/ta-lib-0.4.0-src.tar.gz
> tar -xvzf ta-lib-0.4.0-src.tar.gz
> cd ta-lib/
> ./configure --prefix=/usr
> make
> sudo make install
> cd ..

6.
> pip install TA-Lib

8.
9.
> pip install -r requirements.txt

ccxt==4.3.28
lightgbm==3.2.1
TA-Lib==0.4.21
requests==2.22.0
pandas==1.3.4
seaborn==0.13.2
numba==0.59.1
numpy==1.26.4
git+https://github.com/richmanbtc/crypto_data_fetcher.git@v0.0.18#egg=crypto_data_fetcher
#
