# Day 7 - Linux Commands (cut, sort, head, tail)

## 🚀 What I Learned Today

Today I learned useful Linux commands for data extraction, sorting, and file viewing:  
`cut`, `sort`, `head`, and `tail`.

These commands are widely used in DevOps for handling logs, filtering data, and quick file inspection.

---

## ✂️ cut Command (Extract Fields)

The `cut` command is used to extract specific fields from a file.

```bash
cut -d "," -f 1 data.csv
cut -d "," -f 2 data.csv
cut -d "," -f 1,3 data.csv
cut -d "," -f 2 --complement data.csv

```
🔄 sort Command (Sort Data)

The sort command is used to arrange data.
```
sort numbers.txt
sort -n numbers.txt
sort -r numbers.txt
sort -u numbers.txt
sort -k 2 data.csv
sort -t "," -k 2 data.csv
```
👉 Options:

-r → reverse order
-n → numeric sort
-k → sort by column
-u → remove duplicates
-t → set delimiter
📄 head Command (View Start of File)

The head command shows the beginning of a file.
```
head file.txt
head -n 5 file.txt
head -c 10 file.txt
```

👉 Options:

-n → first N lines
-c → first N bytes

📄 tail Command (View End of File)

The tail command shows the end of a file.
```
tail file.txt
tail -n 5 file.txt
tail -c 10 file.txt
tail -f log.txt
```
👉 Options:

-n → last N lines
-c → last N bytes
-f → follow logs in real time
