# bash-i18n

Helper scripts to add and update gettext translations to ArchRoyal modules.

## i18n

### Requirements

- `gettext`

To use i18n, gettext must be installed. On most linux distros this is a given. On OSX it is recommended to install gettext with homebrew:

```sh
$ brew install gettext
```

### Quickstart

> Add a language to a module:

```sh
$ ./i18n --module=<module> --lang=fr
```

> Extract the messages from a module (update the translation files)

```sh
$ ./i18n --module=<module>
```
