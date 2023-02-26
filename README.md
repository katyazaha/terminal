|            TASK                 |      COMMANDS
---------------------------------------------------
| show where am I                 | pwd
| make a directory                | mkdir dir_name
| change dir                      | cd dir_name
| make 3 dir                      | mkdir {dir1,dir2,dir3}
| change dir1                     | cd dir1
| create 5 files(3 txt,2 js)      | touch {1,2,3}.txt {3,4}.json
| make 3 dir                      | mkdir {dir4,dir5,dir6}
| list                            | ls -l
| open text file                  | vim 1.txt
| write smth                      | i hello
| save and exit                   | Esc + :wq or :x
| change dir and go up            | cd ..
-------------------------------------------------------------
| move 2 files to another dir     | mv dir1/{1,2}.txt dir2
| copy 2 files to another dir     | cp dir3/{3,4}.json dir1/dir4
| find file with a name           | find . -name "*name*"
| view file content               | cat file.txt
| show first lines of a text file | head -5 file.txt
| show the last few lines         | tail -5 file.txt
| show file content of a big file | less file.txt
| show system date and time       | date