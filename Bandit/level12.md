
## Level 12 ##

```bash
	ssh bandit12@bandit.labs.overthewire.org -p 2220
	mkdir /tmp/WC79vCr6GtD4DEGg # temp folder with random name so other users wouldn't find it by accident
	cd /tmp/WC79vCr6GtD4DEGg
	cp $HOME/data.txt data.txt
	# ls | xargs file
	xxd -r data.txt data.gz
	gzip -d data.gz
	bzip2 -d data
	mv data.out data.gz
	gzip -d data.out
	tar -xf data
	tar -xf data5.bin
	bzip2 -d data6.bin
	tar -xf data6.bin.out
	mv data8.bin data8.gz
	gzip -d data8.gz
	cat data8
```
