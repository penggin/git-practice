# 202334317_이동훈_lecture_note_5

## Standard Output

By default, standard output is screen

Using “>” after command, you can save output to file

Using “>>” after command, you can append output to file

### cat

display the content of file

## Standard input

By default, standard input is from keyboard

using “<”, you can input from a file

you can use “>” and “<” at once

## Pipeline “|”

pipeline feeds output of previous command to input of next command

`command1 | command2 | command3`

## Backslash

backslash can be used to ignore line change in command

## permission

Linux has multi user

files and directories have a permission assigned differently to owner / group / others

`-rwxrwxrwx`

### change permission

`chmod` changes permission

6 = 110 = rw- for owner

0 = 000 = —- for group

0 = 000 = —- for others

### superuser

put sudo before the command if you are a superuser

type exit to get out of a superuser session

## misc

### history

`history` shows previous command history