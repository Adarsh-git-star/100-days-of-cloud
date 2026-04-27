# Day 4 - Linux File Management (All Commands)

##   Commands Learned

---

##   cat (Read / Create / Combine)

```bash
cat file.txt
cat -n file.txt
cat -b file.txt
cat -s file.txt
cat -v file.txt
cat file1.txt file2.txt > combined.txt
cat combined.txt

cat file.txt | grep text

cp file.txt copy.txt
cp -r folder1 folder2
cp -i file.txt copy.txt
cp -u file.txt copy.txt
cp *.txt backup/

mv file.txt newname.txt
mv file.txt folder/
mv -i file.txt newname.txt
mv -u file.txt folder/
mv -v file.txt newname.txt

rm file.txt
rm -r folder_name
rm -i file.txt
rm -f file.txt
rm *.txt

ls *.txt
ls file?.txt
ls file[1-3].txt
