# Load forecasting

Aim of the project is to apply machine learning techniques to prediction of electricity demand data.  The data is from the Australian National Electricity Market (NEM).

## Using nem-data to download demand data

Use a third party package `nem-data` to download NEM data onto our local machine

```bash
git clone https://github.com/ADGEfficiency/nem-data
cd nem-data
python setup.py install
pip3 install -r requirements.txt
nem --reports demand --start 2018-01 --end 2018-03
```