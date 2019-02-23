# Webkit style checker

Separate Webkit style checker. Extacted from WebKit code base with removed dependencies.

Extracted from snapshot of the WebKit source tree taken from http://webkit.org/getting-the-code (19 Feb 2019)

Original location: `Tools/Scripts`

## Usage

Detailed help: `<tool-path>/check-webkit-style -h`

Sample usage: `<tool-path>/check-webkit-style check-webkit-style ./src ./test`

## Changed

- removed dependencis on WebKit scripts not related to style checking.
- tuned rule which requied config.h to be the first header: requirement removed.

## Changed files

- `./webkitpy/port/__init__.py`
- `./webkitpy/style/main.py`
- `./webkitpy/style/checker.py`
- `./webkitpy/style/checkers/cpp.py`