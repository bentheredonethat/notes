# Notes

### Entry Template


__command__ - _Description_

__Examples:__

```
bash code in here
```
---

## File Management

__mv__ - _Move file or Rename file_

__Examples:__

```
mv sourceFile destinationFile
mv sourceFile destinationLocation
mv myFile.txt myFolder/
```
---

__cp__ - _Copy file or folder_

__Examples:__

```
cp filename.cpp myCopy.cpp
cp -r myFolder/ myNewFolder
```
---

* cp (folder and individual files)
* rm (file and directories)
 
__Examples:__

```
rm <filename>
```

* rmdir (remove directory) that is empty
__Examples:__

```
rmdir <directory name>
```
* ln -s (symbolic link)
__Examples:__

```
ln -s myfile myotherfile
```
* scp (secure copy
__Examples:__

```
scp  <filename>
```
* pwd (print file name of dir)
__Examples:__

```
pwd 

i.e.  where you are now in filesystem
```
* ls (hidden files and files starting or ending with specific patterns like all files ending in txt or all files starting with the letter b)
__Examples:__

```
<filename/dir> etc.
```
* tar (saves  many files together into a single tape or disk archive, and can restore individual files from
       the archive.)
__Examples:__

```
tar -xf archive.tar #extact all files from archive.tar.
```
## File Transfer

* curl (transfer URL)
* wget retrieve networks
__Examples:__

```
wget [OPTION] ... [URL]...
```
* scp copies files between hosts on a network
__Examples:__

```
scp -1 forces scp to use protocol 1
```
* rsync (copies files)
__Examples:__

```
rsync [option..] src[...[dest]
```

## Pipe tools

* cat
* sort
* uniq
* grep
