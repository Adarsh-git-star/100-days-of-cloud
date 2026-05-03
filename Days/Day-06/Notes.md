# Day 6 - Text Processing Commands (awk, grep, sed)

## 🚀 What I Learned Today

Today I learned powerful Linux text processing commands: `grep`, `awk`, and `sed`.  
These commands are widely used in DevOps for log analysis, automation, and data processing.

---

## 🔍 grep Command (Search Text)

The `grep` command is used to search patterns inside files.

```bash
grep "error" log.txt
grep -i "error" log.txt     # Ignore case
grep -r "error" .           # Search recursively in directory
grep -v "error" log.txt     # Show lines NOT matching
