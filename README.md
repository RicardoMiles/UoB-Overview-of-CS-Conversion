# UoB-Overview-of-CS-Conversion


## The essential script for MVB lab machine
`chromeCommand.sh`,`cleanup.sh`,`firefoxCommand.sh` in the repo are regularly used command on lab machine coping with randomly broken error.

### `chromeCommand.sh` Usage
Open the directory in terminal, type and run at first time

```bash
chomod u+x chromeCommand.sh
./chromeCommand.sh
```
For the next time, just run:

```bash
./chromeCommand.sh
```

This script is used to remove block on multi-machines permission. If you log out or shut a lab machine without killing every process of Chrome, the super annoying error in open Chrome browser will occur. To solve this, run script to allow multi-machines Chrome process.

### `cleanup.sh` Usage
Open the directory in terminal, type and run at first time

```bash
chomod u+x cleanup.sh
./cleanup.sh
```
For the next time, just run:

```bash
./cleanup.sh
```

For the unreasonable concern, you will be blocked to run any programme because of the storage hazard. Especially the virtual machine used in Overview of Software Tools. The hard disk storage allocated to every user on linux lab machine seems to be big enough, but it will be occuppied by some cache of Intellij, Clion or Web Browsers. Remove them and run vagrant again.

### `firefoxCommand.sh` Usage
Open the directory in terminal, type and run at first time

```bash
chomod u+x firefoxCommand.sh
./cleanup.sh
```
For the next time, just run:

```bash
./firefoxCommand.sh
```

Firefox may meet some black magic about cache and could not run, but you cannot remove them in GUI interface and a so-called "Reset" or "Clean" button provided by Firefox itself. Use the script to solve!