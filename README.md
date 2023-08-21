# FormatHub

## Description

**FormatHub** is a main project about amounting as many different extensions as possible from the files collections. The same operations and contents are included for each different syntax and file extension, respecting their own rules. Test features that support file extensions or utilize them as a template with **FormatHub** repositories that are categorized by topics.

## Automation source script

- Clone all repositories at once

```bash
#!/usr/bin/sh

#BRANCH_NAME="main"
BRANCH_NAME="development"

#git clone https://github.com/formathub/formathub --branch "$BRANCH_NAME"
git clone https://github.com/formathub/audio --branch "$BRANCH_NAME"
git clone https://github.com/formathub/binary --branch "$BRANCH_NAME"
git clone https://github.com/formathub/code --branch "$BRANCH_NAME"
git clone https://github.com/formathub/compression --branch "$BRANCH_NAME"
git clone https://github.com/formathub/data --branch "$BRANCH_NAME"
git clone https://github.com/formathub/document --branch "$BRANCH_NAME"
git clone https://github.com/formathub/font --branch "$BRANCH_NAME"
git clone https://github.com/formathub/form --branch "$BRANCH_NAME"
git clone https://github.com/formathub/image --branch "$BRANCH_NAME"
git clone https://github.com/formathub/setting --branch "$BRANCH_NAME"
git clone https://github.com/formathub/spreadsheet --branch "$BRANCH_NAME"
git clone https://github.com/formathub/video --branch "$BRANCH_NAME"
```

## Rules

- Submitting files
	1. Each repository must respect the category according to the repository name.
	1. Each repository must have a `README.md` file with a picture or the file content example about what is going to be converted.
	1. Each repository must have script to convert a file into all different extensions written in **Cotowali** or **Shell Script** programming languages.
	1. Each repository must mention the required tools to convert the files.
	1. The main extension file format for each repository must be a uncompressed, data less compression file or the simplest one to be converted with no problems.

- Repositories structures
	1. `./dist/` directory
		1. Contains the generated files after the conversion from the main extension file format.
		1. Contains a copy of the main extension file format.

  	1. `./src/` directory
		1. Contains the main extension file format.
	 	1. Contains the `converter.sh` converter script tool.

	1. `./README.md` file
		1. Contains a description about the required conversion tools.
		1. Contains a picture or the file content example about what is going to be converted.

- Main extension file formats table

|Categories		|Main extension file	|Converter tools
|---			|---					|---
|Audio			|`.wav`					|[FFMpeg]()
|Binary			|`.jar`					|[GraalVM]()
|Code			|`.java`				|**Manual**
|Compression	|**NONE**				|**Manual**
|Data			|`.sqlite`				|**UNKNOWN**
|Document		|`.md`					|[PanDOC]()
|Font			|`.woff`				|**UNKNOWN**
|Form			|**UNKNOWN**			|**UNKNOWN**
|Image			|`.bmp`					|[ImageMagick]()
|Setting		|`.json`				|[jQ](), [tQ](), [xQ]() and [yQ]()
|Spreadsheet	|`.ods`					|[PanDoc]()
|Video			|`.avi`					|[FFMpeg]()

- Notes
	1. A gif file is going to be considered as a video file.
