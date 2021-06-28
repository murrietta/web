# web

## Setup
Using python 3.7 as availble on Raspbian Buster (Linux raspberrypi 5.10.17-v7l+ #1421 SMP Thu May 27 14:00:13 BST 2021 armv7l GNU/Linux)

See requirements.txt for modules needed.

## Miscellaneous Tips
I needed these at one time or another, so saving them here until memorized:

### Tar and gz my files
From this [https://superuser.com/questions/334827/how-to-gzip-multiple-files-into-one-gz-file] SO post:

- You want to tar your files together and then gzip the result:
```
tar czvf archivename.tar.gz ./path/to/files/*.py
```
- To untar the gzip'd tar file you do:
```
tar xvzf archivename.tar.gz -C /path/to/parent/dir
```