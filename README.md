# safe-erase
KSH script for deleting files and directories in a safe way, with a trash can.

## Usage

* __Show action__.
With the `-S` flag, the erase program will display the content of the trash can. This option produces a list of all files that are stored in the can.
```bash
  erase -S
```

* __Delete action__.
With the `-D` flag, the erase program deletes the files temporaly stored in the trash can. Before to proceed, the program asks for the user to be sure to empty the trash can.
```bash
  erase -D
```

* __Inquire action__.
With the `-I` flag, the program inquires, for each file in the trash can, if the user actually wants to delete the file.
```bash
  erase -I
```

* __Move action__.
With the `-M` flag, the erase program moves the file received as a parameter to the trash can. 
```bash
  erase -M /foo/bar.txt
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
