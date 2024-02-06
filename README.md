# Bash commands 
**Getting Help in Linux**
MAN Pages

`man command` # => Example: `man ls`

### **SHORTCUTS**:
- `h`=> getting help 
- `q` => quit 
- `enter`=> show next line 
- `space`=> show next screen 
- `/string` => search forward for a string 
- `?string` => search backwards for a string 
- `n / N` => next/previous appearance 

**checking if a command is a shell built-in or an executable file**
- type rm  # => rm is /usr/bin/rm 
- type cd  #=> cd is a shell builtin
  
**getting help for shell built-in commands** 
- help command  # => Example: help cd 
- command --help  # => Example: rm --help 

**searching for a command, feature or keyword in all man pages**
- man -k uname 
- man -k "copy files" 
- apropos passwd 
 
