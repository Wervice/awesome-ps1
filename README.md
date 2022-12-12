# awesome-ps1
A list of amazing PS1 shell prefixes for linux. Just copy the PS1 variable to your .bashrc file in your home folder.

# 1. Aqua
```
PS1='\[\e[0;38;5;82m\]$ \[\e[0;38;5;45m\]\u \[\e[0;38;5;45m\](\[\e[0;38;5;39m\]\W\[\e[0;38;5;45m\]) \[\e[0;1;38;5;45m\]>\[\e[0m\]'

```
# 2. Green
```
PS1='\[\e[0;2;38;5;46m\]$ \[\e[0;2;38;5;46m\]\u \[\e[0;2;38;5;47m\](\[\e[0;1;38;5;46m\]\W\[\e[0;2;38;5;47m\]) \[\e[0;1;38;5;46m\]>\[\e[0m\]'
```
# 3. Yellow Blinking
```
PS1='\[\e[0;2;5;38;5;226m\]$ \[\e[0;2;5;38;5;226m\]\u \[\e[0;2;5;38;5;214m\](\[\e[0;1;5;38;5;226m\]\W\[\e[0;2;5;38;5;214m\]) \[\e[0;1;5;38;5;226m\]>\[\e[0m\]'
```
# 4. Block
```
PS1='\[\e[0;4;53m\]\u\[\e[0;2;4;53m\]@\[\e[0;1;4;53m\]\w\[\e[0;1;4;53m\]>\[\e[0m\]'
```
# 5. Red Root
```
PS1='\[\e[0;2;38;5;160m\]# \[\e[0;1;38;5;160m\]\u \[\e[0;1;38;5;160m\]~\[\e[0m\]'
```
# 6. Server
```
PS1='\[\e[0;2m\]$ \[\e[0m\]\u\[\e[0m\]@\[\e[0m\]$(ip route get 1.1.1.1 | awk -F"src " '"'"'NR==1{split($2,a," ");print a[1]}'"'"') \[\e[0m\](\[\e[0m\]\u\[\e[0m\]) \[\e[0;1m\]>\[\e[0m\]'
```
# 7. Emoji
```
PS1='\[\e[0m\]💰 \[\e[0m\]😀@💻 \[\e[0m\]➡️ \[\e[0m\]'
```
# 8. Simple
```
PS1='\[\e[0;2m\]\$ \[\e[0m\]\u\[\e[0;2m\]@\[\e[0m\]\h \[\e[0m\](\[\e[0m\]\W\[\e[0m\]) \[\e[0;1m\]~ \[\e[0m\]'
```
# 9. Italic Block
```
PS1=' \[\e[0;2;3m\][ \[\e[0;2;3m\]\u \[\e[0;2;3m\]@ \[\e[0;1;3m\]\w \[\e[0;2;3m\]] \[\e[0m\]'
```
###### ❤️ Did you like it? [Check out my other respositories](https://www.github.com/wervice)
