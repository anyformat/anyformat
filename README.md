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

## Rules

- Submitting files
	1. Each repository must respect the category according to the repository name.
	1. Each repository must have a `README.md` file with a picture or the file content example about what is going to be converted.
	1. Each repository must have script to convert a file into all different extensions written in **Shell Script** programming language.
	1. Each repository must mention the required tools to convert the files.

- The main file formats are:

|Categories	|Main extension file	|Converter tools
|---		|---					|---
|Audio		|`.wav`					|FFMpeg
|Binary		|`.jar`					|GraalVM
|Code		|`.java`				|**Manual**
|Compression|**NONE**				|**Manual**
|Data		|`.sqlite`				|**UNKNOWN**
|Document	|`.md`					|PanDOC
|Font		|`.woff`				|**UNKNOWN**
|Form		|**UNKNOWN**			|**UNKNOWN**
|Image		|`.bmp`					|ImageMagick
|Setting	|`.json`				|jQ, tQ, xQ and yQ
|Spreadsheet|`.ods`					|PanDoc
|Video		|`.avi`					|FFMpeg

- Notes
	1. A gif file is going to be considered as a video file.
