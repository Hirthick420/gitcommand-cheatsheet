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

## Cheat Card 9: `git --version`
**Purpose:** Show the installed Git version (quick sanity check).  
**Quick form:** `git --version`  
**Demo:**
~~~bash
git --version
# example: git version 2.43.0
~~~

## Cheat Card 10: `git rm`
**Purpose:** Remove a tracked file from the repo (and from disk).  
**Quick form:** `git rm <file>`  
**Demo (concept):**
~~~bash
echo "temp" > temp.txt
git add temp.txt && git commit -m "temp: add file"
git rm temp.txt && git commit -m "temp: remove file"
~~~
## Cheat Card 11: `git mv`
**Purpose:** Rename or move a tracked file (keeps history).  
**Quick form:** `git mv oldname newname`  
**Demo (concept):**
~~~bash
git mv notes.txt notes-old.txt
~~~
## Cheat Card 12: `git show`
**Purpose:** Display details about a commit or object.  
**Quick form:** `git show <ref>` (e.g., `git show HEAD`)  
**Demo:**
~~~bash
git show --stat HEAD
~~~
## Cheat Card 13: `git stash`
**Purpose:** Temporarily set aside uncommitted work.  
**Quick forms:**  
- Save: `git stash push -m "note"`  
- Restore & drop: `git stash pop`  
**Demo:**
~~~bash
git stash push -m "clean working tree"
git stash list
~~~
## Cheat Card 14: `git tag`
**Purpose:** Mark commits with a readable label (versions).  
**Quick forms:**  
- Create annotated: `git tag -a v1.0 -m "first tag"`  
- List tags: `git tag --list`  
**Demo:**
~~~bash
git tag -a v0.1 -m "milestone"
git tag --list
~~~
