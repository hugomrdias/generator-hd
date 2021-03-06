# generator-hd 

> Scaffold out a generic JS project

Optionally with a [CLI](http://en.wikipedia.org/wiki/Command-line_interface).

This is what I use for [my own modules](https://www.npmjs.com/~hugomrdias).


## Install

```
$ npm install --global yo generator-hd
```


## Usage

With [yo](https://github.com/yeoman/yo):

```
$ yo hd
```

There are multiple command-line options available:

```
$ yo hd --help

  Usage:
    yo hd [options]

  Options:
    --help          # Print the generator's options and usage
    --skip-cache    # Do not remember prompt answers                      Default: false
    --skip-install  # Do not automatically install dependencies           Default: false
    --org           # Publish to a GitHub organization account
    --cli           # Add a CLI
    --coverage      # Add code coverage with nyc
    --codecov       # Upload coverage to codecov.io (implies --coverage)
```

The `--org` option takes a string value (i.e. `--org=avajs`). All others are boolean flags and can be negated with the `no` prefix (i.e. `--no-codecov`). You will be prompted for any options not passed on the command-line.


## License

MIT © [Hugo Dias](http://hugodias.me)
