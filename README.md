# AnyFormat

## Description

AnyFormat is a main project about amounting as many different extensions as possible from the files collections. The same operations and contents are included for each different syntax and file extension, respecting their own rules. Test features that support file extensions or utilize them as a template with **AnyFormat** repositories that are categorized by topics.

## Automation source script

- Clone all repositories at once

```bash
#!/usr/bin/sh

#BRANCH_NAME="main"
BRANCH_NAME="development"

#git clone https://github.com/anyformat/anyformat --branch "$BRANCH_NAME"
git clone https://github.com/anyformat/audio --branch "$BRANCH_NAME"
git clone https://github.com/anyformat/binary --branch "$BRANCH_NAME"
git clone https://github.com/anyformat/code --branch "$BRANCH_NAME"
git clone https://github.com/anyformat/compression --branch "$BRANCH_NAME"
git clone https://github.com/anyformat/data --branch "$BRANCH_NAME"
git clone https://github.com/anyformat/document --branch "$BRANCH_NAME"
git clone https://github.com/anyformat/font --branch "$BRANCH_NAME"
git clone https://github.com/anyformat/form --branch "$BRANCH_NAME"
git clone https://github.com/anyformat/image --branch "$BRANCH_NAME"
git clone https://github.com/anyformat/setting --branch "$BRANCH_NAME"
git clone https://github.com/anyformat/spreadsheet --branch "$BRANCH_NAME"
git clone https://github.com/anyformat/video --branch "$BRANCH_NAME"
```
