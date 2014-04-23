##generate-gitignore

Generate gitignore files intelligently based off of the directory contents.

```
usage: generate-gitignore [-h] [-v] [-l LOG_FILE] [-u] [-V] [-d DIRECTORY] [-f]

Options:
  -h, --help            Show this help message and exit.
  -v, --verbose         Writes all messages to console.
  -l LOG_FILE, --log-file LOG_FILE
  -u, --update          Checks server for an update, replaces the current
                        version if there is a newer version available.
  -V, --version         show program's version number and exit

Generate Options:
  -d DIRECTORY, --directory DIRECTORY
                        The directory to search and save the gitignore file
                        into.
  -f, --force           Overwrite a previous gitignore if it exists.

```

#### Installation Instructions

Run the following command:
```
SDIR=/usr/local/bin/; wget https://raw.github.com/gesquive/generate-gitignore/master/generate-gitignore.py -O ${SDIR}/generate-gitignore && chmod +x ${SDIR}/generate-gitignore
```

Change the value of `SDIR` to change the destination directory.

