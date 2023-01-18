# Commiteee
git status -s but prettier and with more features

## Requirements
>Requires notify-send functionality [notification server in unix systems e.g dunst]

## Installation
```console
$ git clone https://github.com/Tontuu/commiteee.git
$ cd commiteee
$ pip install -r requirements.txt
$ # ADD TO YOUR PREFERRED PATH
$ sudo ln -s /path/to/commiteee/script /usr/local/bin
```

## Usage
```console
commiteee [OPTIONS...]
```

### Examples
```sh
# Help message
commiteee --help

# Print with colors
commiteee --colors

# Notify to desktop environment
commiteee --notify
```
