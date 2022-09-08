## Lab 02

- Name: Dylan Schneider
- Email schneider.228@wright.edu

## Part 1 Answers

The answers for this section are to help you record what steps  
are needed to create a file locally (in your cloned repo)  
and push them (sync) with GitHub

1. Add a file for tracking: add new file > lab02/lab02.md
2. Commit changes: write, commit changes
3. Sync local commits with GitHub: git push

## Part 2 Answers

For each, write the command used or answer the question posed.

1. sudo adduser bob
2. /home/bob
3. No, I'm not Bob
4. su bob
5. cd /home
6. no, permission is still denied because I'm not the owner. You'd have to use chown to change permissions
7. su
8. cd /home

## Part 3 Answers

For each, write the command used or answer the question posed.

1. sudo addgroup crew
2. sudo usermod -a -G crew bob
3. sudo chown :crew DirA
4. su bob
5. sudo chgrp crew DirA
6. because Bob is a member of the group that owns the directory

## Part 4 Answers

For each, write the command used or answer the question posed.

1. sudo touch sudowho.txt
2. -rw-r--r-- 
3. vi sudowho.txt

## Part 5 Answers

1. `ssh` command before configuring `config` file: ssh -i /home/pants/Downloads/labsuser.pem ubuntu@54.211.224.14
2. HostName: 54.211.224.14
3. User: pants
4. IdentityFile: /home/pants/Downloads/labsuser.pem
5. `~/.ssh/config` contents:

```
```
