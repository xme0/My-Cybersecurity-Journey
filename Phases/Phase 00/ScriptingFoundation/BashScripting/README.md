
# Our first simple bash scripts

## Top Of Bash File
At the top of bash file add this line:
``` bash 
#!/bin/bash
```
this tell the system to execute the script using bash shell
## Run normal commends inside script
you can also perform normal linux commands inside script, just like this :
```bash
#!/bin/bash
echo "hi"
ls
```
## Run the bash file
1. make it executable 
```
chmod +x file.sh
```
2. run the file 
```
./file.sh
```


# variables
## To declare a variable:
```bash
#!/bin/bash
name="value"
```
no spaces before or after the =
## To use the variable:
```bash
echo $name
```
just add $ before the variable name 

## Debugging
To run in debugging mode:
```
bash -x ./file.sh
```

If you want to debug at a certain point you can insert **set -x** into your script and **set +x** to end the section