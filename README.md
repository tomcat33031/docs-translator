# docs-translator

Python script that translates docs files using Amazon Translate service.

## Installation

```
$ virtualenv venv
$ source venv/bin/activate
$ pip install -r requirements.txt
```

## Usage

```
$ python powerpoint-translator.py --help
usage: Translates docs files from source language to target language using Amazon Translate service
       [-h] [--terminology TERMINOLOGY]
       source_language_code target_language_code input_file_path

positional arguments:
  source_language_code  The language code for the language of the source text.
                        Example: ja
  target_language_code  The language code requested for the language of the
                        target text. Example: en
  input_file_path       The path of the powerpoint file that should be translated

optional arguments:
  -h, --help            show this help message and exit
  --terminology TERMINOLOGY
                        The path of the terminology CSV file
```

## License

This library is licensed under the MIT-0 License. See the LICENSE file.
