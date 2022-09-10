# lrun
Runs a bash script given the name in the closest parent folder

## Usage
```
lrun <file name> <search depth>
```

`<file name>` is the name of the file to run
`<search depth>`` is defualted to 5 and defines how many parent folders to search
    (Ex. search depth of 2 would search up to `./..` and search depth of 4 would search up to `./../../../`
