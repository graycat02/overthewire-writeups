
## Level 6 ##

```bash
	ssh bandit6@bandit.labs.overthewire.org -p 2220
	find / -user bandit7 -group bandit6 -size 33c 2> /dev/null
	cat /var/lib/dpkg/info/bandit7.password
```