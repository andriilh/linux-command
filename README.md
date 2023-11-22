
# List Linux commands

1. [Download file from ssh using scp](#1)
2. [Rename file](#2)
3. [ZIP folder or compress](#3)

<a name="1"></a>
### Download file from ssh using scp
```bash
scp -P 34121 root@211.123.123.123:/root/dest/file.zip . 
scp -P <port> <username>@<host>:<destination/file/to/download.zip> <local/destination>
```

<a name="2"></a>
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

<a name="3"></a>
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

