# 202334317_이동훈_lecture_note_4

# Shell commands

### pwd

shows the current path in a hierarchical directory.

## path

```bash
/ : root
. : current directory
.. : upper-level directory
~ : home of current user
/[path] : absolute path
./[path] : relative path
../[path] : relative path

-l : show detailed information (long format)
-lh : same as above, but size in units
-la : all files

Pattern
* : all file names
g* : all file names begin with "g"
b*.txt : all file names begin with "b" and ends with .txt
Data??? : any filename that begins with the characters "Data" followed by exactly 3 more characters
```

### cd

Change Directory

### ls

LiSt files and directories

### cp

CoPy files and directories

```bash
cp file1 file2 : copies the contents of file1 into file2.
cp -i file1 file2 : Like aboce however, since "-i" (interactive) is specified, user choose overwrite or not.
cp file1 dir1 : copy content to inside of directory dir1
cp -R dir1 dir2 : copy all content of dir1 into dir2.
```

### mv

move files and directories or rename them

```bash
mv file1 file2 : remame file1 to file2 or replace
mv -i file1 file2 : Like aboce however, since "-i" (interactive) is specified, user choose replace or not.
mv file1 file2 dir1 : move content into inside of directory dir1
mv dir1 dir2 : rename dir1 to dir2 or move dir1 into dir2
```

### rm

delete files and directories permantely and irreversevely

```bash
rm file1 file2 : delete file1 and file2
rm -i file1 file2 : like above but user action needed
rm -r dir1 dir2 : delete dir1 and dir2 include their content
```

### mkdir

MaKe a new DIRectory

## General

### clear

clear console

### help

see document of target.

### man

yet another help command

### exit

exiting terminal