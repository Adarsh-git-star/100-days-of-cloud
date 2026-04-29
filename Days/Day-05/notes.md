# Day 5 - Linux Commands (touch, mkdir, alias, man, wildcards)

## 🚀 Commands Learned

## 📄 touch (Create / Update Timestamp)

touch file.txt
touch -a file.txt        # Update access time
touch -m file.txt        # Update modify time
touch -t 202604281200 file.txt  # Set custom timestamp
touch -c file.txt        # Do not create if file does not exist

mkdir project
mkdir -p project/src/components
mkdir -v test
mkdir -m 755 secure_folder

man ls
man mkdir
man touch

*.txt      # All .txt files
file?      # Single character match
file[1-3]  # Range match


Concepts Learned
File timestamps (access vs modify)
Creating nested directories using -p
Using aliases to improve workflow speed
Exploring commands using man
Handling multiple files using wildcards
