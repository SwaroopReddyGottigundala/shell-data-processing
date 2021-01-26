# Shell Data Processing
## Basic Powershell Commands
mkdir - make a directory

cd - change directory

ls - list

ni - create new file

## Curl command

curl "URL" -O "rj.txt"

## Git bash commands
``` bash 
tr ' ' '\12' < "rj.txt" 
tr ' ' '\12' < "rj.txt" | sort 
tr ' ' '\12' < "rj.txt" | sort | uniq -c 
tr ' ' '\12' < "rj.txt" | sort | uniq -c | sort -nr > "result.txt"
```
## Data file
[rj.txt](https://github.com/SwaroopReddyGottigundala/shell-data-processing/blob/main/rj.txt)

## Result.txt
[result.txt](https://github.com/SwaroopReddyGottigundala/shell-data-processing/blob/main/result.txt)