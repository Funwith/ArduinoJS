Fist of all, you run commnad to install ino with pip: $ `sudo pip install ino` or `easy_install ino`.

Command: $ ino build

If message response: Board description file (boards.txt) not found.

Solve: Check location file 'boards.txt' from path '/usr/local/share/arduino/hardware/arduino'
or '/usr/share/arduino/hardware/arduino'

Path location is not found:
+ Check arduino install tool

```bash
sudo apt-get install arduino
```

Example:

$ `ino init -t blink`

$ `ino build`

$ `ino upload` 


Happy coding!!
