# polyptyque

create [polyptych](https://en.wikipedia.org/wiki/Polyptych) in command-line with a white border of 50 pixels

## Install

```
brew install boertel/tap/polyptyque
```

## Usage

```
Usage: polyptyque [--dry-run] [-b <border size>] [-c <border color>] [-l <layout>] [-o <output file>] -- [file...]
Options:
    -b, --border SIZE                   set border size. default: 50
    -c, --color COLOR                   set border color. default: white
    -l, --layout horizontal|vertical    set layout. default: horizontal
    -o, --output PATH                   set output file. default: ./polyptyque-<timestamp>.jpg

    --verbose                           display imagemagick underlying commands executed
    --dry-run                           doesn't execute commands
```

You can also use a blob instead of a list of files like: `*.jpg`
