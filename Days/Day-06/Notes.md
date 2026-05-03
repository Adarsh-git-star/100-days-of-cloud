# Day 6 - Text Processing Commands (awk, grep, sed)

## 🚀 What I Learned Today

Today I learned powerful Linux text processing commands: `grep`, `awk`, and `sed`.  
These commands are widely used in DevOps for log analysis, automation, and data processing.

---

## 🔍 grep Command (Search Text)

The `grep` command is used to search patterns inside files.

grep "error" log.txt
grep -i "error" log.txt     # Ignore case
grep -r "error" .           # Search recursively in directory
grep -v "error" log.txt     # Show lines NOT matching

⚙️ awk Command (Pattern Scanning & Processing)

The awk command is used to process structured data.

awk '{print $1}' file.txt
awk -F "," '{print $2}' data.csv   # Set delimiter
awk -v name="Adarsh" '{print name}' file.txt
awk -f script.awk file.txt         # Use script file


✂️ sed Command (Stream Editor)

The sed command is used to edit and transform text.

sed 's/error/fix/g' log.txt
sed -i 's/error/fix/g' log.txt   # Edit file directly
sed -n '1,5p' log.txt            # Print specific lines
sed -r 's/[0-9]+/NUMBER/g' data.csv
sed -f script.sed log.txt        # Use script file


💡 Key Options Summary
awk Options
-F → Set field separator
-v → Define variable
-f → Use script file
grep Options
-i → Ignore case
-r → Recursive search
-v → Invert match
sed Options
-i → Edit file directly
-e → Multiple commands
-n → Silent output
-r → Extended regex
-f → Script file
-l → Line length
