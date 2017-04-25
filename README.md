# stree

> SourceTree control from your terminal (macOS only)

I don’t use [SourceTree](https://www.sourcetreeapp.com/) for anything other than its pretty awesome history log/graph.  However, when I need it, I want to summon SourceTree from the terminal.  This does just that.

Yes, you could just use `open -a SourceTree [directory]` (or `alias stree='open -a SourceTree'`), and that’s really all this currently does.  However, (if I ever get around to it) there are some other options I’d like to add you can’t really use from just calling `open`.  Plus, this keeps you from having to specify the directory _every time_.

## Usage

Show the repository in the current working directory in SourceTree:

```shell
stree
```

Show a specific repository in SourceTree:

```shell
stree /path/to/repository
```

Prompt to create a new repository in your current directory:

```shell
stree --create
```

## Install

1. Either [clone this repo](https://help.github.com/articles/cloning-a-repository/) or [download the zip file](https://github.com/blakek/stree/archive/master.zip)
2. Add `stree` to your $PATH

## License

MIT
