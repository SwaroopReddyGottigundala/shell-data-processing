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