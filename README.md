# Sourcer

A python script for sourcing libraries into a project. This project is currently in very earlier stages and only provides basic support for git repositories.

## sourcer.json

This file is used to inform the sourcer program how to obtain your libraries.

Here is an example:

```json
{
  "sourcer-version": 0.1,
  "target": "lib/",
  "libraries": {
    "Snooze": {
      "type": "git",
      "url": "https://github.com/duff2013/Snooze",
      "branch": "v5.5"
    },
    "i2c": {
      "type": "git",
      "url": "https://github.com/nox771/i2c_t3",
      "branch": "v8.0"
    }
  }
}
```
