# About Bash projects

## 0. Knowing Exactly Path
Write a script that prints the absolute path name of the current working directory.

```bash
pwd
```

## 1. What’s in there?
Display the contents list of your current directory.
```bash
ls
```
## 2. There is no place like home
Write a script that changes the working directory to the user’s home directory.

You are not allowed to use any shell variables
```bash
cd ~
```
## 3. The long format
Display current directory contents in a long format
```bash
ls -l
```
## 4. Hidden files
Display current directory contents, including hidden files (starting with .). Use the long format.
```bash
ls -al
```
## 5. I love numbers
Display current directory contents.
    -Long format
    -with user and group IDs displayed numerically
    -And hidden files (starting with .)
```bash
ls -lna
```
## 6. Welcome
Create a script that creates a directory named my_first_directory in the /tmp/ directory.
```bash
mkdir /tmp/my_first_directory/
```
## 7. Betty in my first directory
Move the file betty from /tmp/ to /tmp/my_first_directory.
```bash
mv /temp/betty /temp/my_first_directory/betty
```
## 8. Bye bye Betty
Delete the file betty.
The file betty is in /tmp/my_first_directory
```bash
rm /tmp/my_first_directory/betty
```
## 9. Bye bye My first directory
mandatory
Delete the directory my_first_directory that is in the /tmp directory.
```bash
rmdir /tmp directory/my_first_directory
```
## 10. Back to the future
mandatory
Write a script that changes the working directory to the previous one.
```bash
cd ..
```