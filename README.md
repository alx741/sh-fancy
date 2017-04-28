# Fancy message display for SH scripts

Tiny little library for fancy `info`, `warning`, `error` and `success` message
printing for Shell (bash, zsh, etc.) scripts.

## Usage

Download the `fancy.sh` file, and put it into the same directory where your
shell script lives.

Then, at the top of your script, include the library with:

```sh
source "$(dirname "$0")/fancy.sh"
```

Display messages by invoking each function by its name, followed by the message.
For example:

```sh
displayInfo "This is a info message"
```

## Functions

* displayInfo
* displaySuccess
* displayWarning
* displayError
