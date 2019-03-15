# YouTube for Franz

An unofficial Franz recipe for [YouTube](https://youtube.com/).

    "serviceURL": "https://www.youtube.com"

## Installing

### Windows

With git and PowerShell:

```sh
mkdir $env:APPDATA\Franz\recipes\dev\
git clone git@github.com:m-wells/franz-youtube.git $env:APPDATA\Franz\recipes\dev\franz-youtube
```

With Explorer:

1. Download the `franz-youtube.zip` from github.  Extract it to its own folder (`franz-youtube`).
2. Open `%appdata%/Franz/recipes/dev/`.  The `dev` folder may not exist, so go ahead and create it.
3. Copy the `franz-youtube` folder into the plugins directory.
4. Reload Franz.

### Mac

```sh
mkdir ~/Library/Application\ Support/Franz/recipes/dev/
git clone git@github.com:m-wells/franz-youtube.git ~/Library/Application\ Support/Franz/recipes/dev/franz-youtube
```

### Linux

```sh
mkdir ~/.config/Franz/recipes/dev
git clone git@github.com:m-wells/franz-youtube.git ~/.config/Franz/recipes/dev/franz-youtube
```
