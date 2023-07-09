# todo-py
A simple cli utility for managing tasks

Made for use alongside conky to display reminders on the desktop but can be used on its own or in your own adaptation

![alt text](https://cdn.discordapp.com/attachments/764607214102904904/1127702030551617667/todo-example.png)

### Installation
Clone the git repo and run ```chmod +x todo``` to make it executable.

Additionally, to allow the script to be run from anywhere add it to a folder in you PATH such as ```~/bin/``` and add
```
export PATH=$HOME/bin:$PATH
```
to the end of your .bashrc file.

### Usage
The script operates using 5 commands:
- ```show``` outputs the list to the terminal
- ```add <task>``` adds a task to the list
- ```complete <task-number>``` crosses out a completed task
- ```clear``` clears all completed tasks and reorders list
- ```clearall``` empties whole list

Optionally:

```-p / --path <path to file>``` can be used to define a path to a custom text file location (default is ~/.todo.txt)
