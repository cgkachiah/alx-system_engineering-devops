# Permissions Shell Project
###### 0. My name is Betty  ######
```
su betty
```
###### 1. Who am I ######
```
whoami
```
###### 2. Groups ######
```
groups
```
###### 3. New Owner ######
```
chwon
```
###### 4. Empty ######
```
touch
```
###### 5. Execute ######
```
chmod u+x hello
```
###### 6. Multiple Permissions ######
```
chmod ug+x,o+r hello
```
###### 7. Everybody ######
```
chmod ugoa+x hello
```
###### 8. James Bond ######
```
chmod 007 hello
```
###### 9. John Doe ######
```
chmod 753 hello
```
###### 10. Look in the mirror ######
```
chmod --reference=olleh hello
```
###### 11. Directories ######
```
chmod a+X *
```
###### 12. More directories ######
```
mkdir -m 751 my_dir
```