## For collecting the logs of the running containers
```
sudo ./logcollector.sh
```
## For arranging the logs in the timestamp order 
```
cd logs
python3 logsassemble_epoch.py
```
## For sending multiple POST requests
### Parallelly
```
sudo ./send_postrequests_parallel.sh
```
### Sequentially
```
sudo ./send_postrequests_sequential.py
```
