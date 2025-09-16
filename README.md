# Assignment-Linux and GIT Command Cheat Sheet

> One branch per command; and at last all merged into main.
## Cheat Card 1: `echo`
**Purpose:** Print text to the terminal or append to a file.  
**Quick form:** `echo "text"` or `echo "text" >> file.txt`  
**Demo:**
~~~bash
echo "Heyyy, Git world!"
echo "first line" >> notes.txt
~~~
## Cheat Card 2: `whoami`
**Purpose:** Shows the current username.  
**Quick form:** `whoami`  
**Demo:**
~~~bash
whoami
# prints your Linux user name
~~~
## Cheat Card 3: `date`
**Purpose:** Prints the current date and time.  
**Quick form:** `date`  
**Demo:**
~~~bash
date "+%Y-%m-%d %H:%M:%S"
~~~
## Cheat Card 4: `uname -a`
**Purpose:** Shows system/kernel info.  
**Quick form:** `uname -a`  
**Demo:**
~~~bash
uname -a
# kernel, architecture, etc.
~~~

## Cheat Card 5: `head`
**Purpose:** Show the first lines of a file.  
**Quick form:** `head -n 5 file.txt`  
**Demo:**
~~~bash
head -n 3 README.md
~~~
## Cheat Card 6: `tail`
**Purpose:** Show the last lines of a file.  
**Quick form:** `tail -n 5 file.txt`  
**Demo:**
~~~bash
tail -n 3 README.md
~~~
## Cheat Card 7: `wc -l`
**Purpose:** Count lines in a file.  
**Quick form:** `wc -l file.txt`  
**Demo:**
~~~bash
wc -l README.md
~~~
## Cheat Card 8: `git diff`
**Purpose:** See what changed in files before committing.  
**Quick form:** `git diff`  
**Demo:**
~~~bash
# shows unstaged changes
git diff
~~~


