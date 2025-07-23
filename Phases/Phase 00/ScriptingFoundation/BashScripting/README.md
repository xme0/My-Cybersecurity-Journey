
# Our first simple bash scripts

## Top Of Bash File
At the top of bash file add this line:
``` bash 
#!/bin/bash
```
this tells the system to execute the script using bash shell
## Run normal commands inside script
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


# Variables
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

Sure! Here's your revised and grammatically correct text in Markdown format:

---

# Parameters

## Passing Parameters

1. You can pass parameters when running a script using the following command:

   ```bash
   ./file.sh parameter1
   ```

   In this case, you can access the parameters using the `$` symbol followed by the parameter number:

   ```bash
   parameter1=$1
   ```

   You can pass multiple parameters. For parameters 1 to 9, use `$1` to `$9`. For parameters after that, use curly braces, like `${10}`, `${11}`.

   ### Special Variables:

   * **`$#`**: Holds the number of arguments passed to the script.
   * **`$@`**: Contains all arguments passed to the script as a space-separated list.

2. If you want to name the parameter and use it in a more interactive way, you can use the `read` command, like this:

   ```bash
   echo "Enter your name"
   read name
   echo "Your name is $name"
   ```
# Loops
## For Loops
