# List Linux commands

### Download file from ssh using scp
```bash
scp -P 34121 root@211.123.123.123:/root/dest/file.zip . 
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

### ZIP folder or compress
`-r` for recurring. So it will include all subfolder in that folder
```bash
zip -r <zip file name> <directory name>
```
And for unzip using unzip app. First, install unzip `sudo apt-get install unzip` 
```bash
unzip archive.zip
# or
unzip file.zip -d destination/
```

