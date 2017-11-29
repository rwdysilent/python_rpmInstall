# python_rpmInstall
install python 2.7 by rpm
----
1. put these rpm packages in a new directory
2. run command:
```bash
yum localinstall * -y
```
3. create python link to python2.7
```
rm -f /usr/bin/python
ln -s /usr/bin/python2.7 /usr/bin/python
```
