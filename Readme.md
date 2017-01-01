[![NPM](https://nodei.co/npm/randomuser-cli.png)](https://nodei.co/npm/randomuser-cli/)

# Get Random User
A Command Line Interface for https://randomuser.me/

## Installation

```bash
$ npm install -g getrandomuser
```

## Usage

To get a single random user:

```bash
$ getrandomuser
```

For help use:

```bash
$ getrandomuser -h
```

Which returns:

```
Usage: getprofiles [options]

  Options:

    -h, --help               output usage information
    -V, --version            output the version number
    -r, --results <n>        number of users to fetch, max 5000
    -g, --gender <gender>    gender
    -n, --nat <nat>          nationality
    -p, --password <string>  control how passwords are generated
    -s, --seed <string>      allows you to always generate the same set of users
    -o, --output <file>      output to a file
    -q, --quite              suppress outputting to stdout
    -d, --dowloadimages      download images

```

## Credits

The Get Random User CLI was written by Adam Griffiths. For the Random User API see https://randomuser.me/copyright.


## Licence

MIT, see [Licence.md](Licence.md).
