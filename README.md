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

1. use spx_2018_downloader.py file to formt spx_active_downloader.py
2. after need to format spx_active_contract_downloader.py
3. covert the datas into call,put and change the format as options

## _Expired Downloader_

1. use spx_2018_downloader.py file to formt spx_active_downloader.py
2. after need to format spx_active_expired_downloader.py
3. covert the datas into call,put and change the format as options
   
## Stocks

1. Need to extract the datas for symbols in slickchart using polygon.io
2. Extract th symbols data in json format and stored it in a separate folder
3. Then convert the json file into .csv format
