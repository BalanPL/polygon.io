# polygon.io

# Historical data 
## _Index Downloader_
### SPX, SPY, QQQ

- SPX is considered for example. 
1. use index/spx_historical_index_downloader.py to download 1minute historical data from 2000-01-01 to 2024-10-10 and save it as csv files 
2. use the csv files and format it to the desired mysql format 
3. use spx_index_ddl.sql to create the table in mysql using mysql workbench 
4. load the formatted files to mysql using to_mysql.py

## _Option Downloader_
- spx is considered for example_

1. use spx-active-downloader.py to download the data and use the csv files  for spx_contract_downloader.py
2. use the spx_contract_downloader.py json file as a input for spx-option-downloader.py 
3. later we get the historical data

# _Expired Downloader_

1. use spx-active-downloader.py to download the data and use the csv files  for spx_contract_downloader.py
2. use the spx_contract_downloader.py json file as a input for spx-Expired-downloader.py 
3. later we get the historical data

## Stocks

1. Need to extract the datas for symbols in slickchart using polygon.io
2. Extract th symbols data in json format and stored it in a separate folder
3. Then convert the json file into .csv format
