# List Linux commands

### Download file from ssh using scp
```bash
scp -P 15963 root@149.129.237.204:/root/backups/appsbackup.zip . 
scp -P <port> <username>@<host>:<destination/file/to/download.zip> <local/destination>
```

### Rename file
Using copy and remove old
```bash
cp <old> <new>
rm <old>
```
Rename by move
```bash
mv <file> <new name>
```


