sphia(1) -- Command line utility for sophia databases
=================================

## SYNOPSIS

`sphia` <command> [--key <key>] [--value <value>] [--path <path>]
                [--version] [--help]

## OPTIONS

  -V, --version
      output program version

  -h, --help
      output help information

  --verbose
      enable verbose output

  -p, --path <path>
      set the path

  -k, --key <name>
      key to get

  -v, --value <name>
      value to set


## COMMANDS
  `init`
      initialize a new database

  `get`
      get a value by key

  `set`
      set a value by key

  `rm|remove`
      remove a value by key

  `ls|list`
      list all keys and values

  `clear`
      clears database of all keys

  `purge`
      purge database of all corrupt and incomplete data

## AUTHOR

  - Joseph Werle <joseph.werle@gmail.com>

## REPORTING BUGS

  - <https://github.com/jwerle/sphia/issues>

## SEE ALSO

  - <https://github.com/jwerle/sphia>
  - <http://sphia.org>

## LICENSE

MIT