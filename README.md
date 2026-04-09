![PyPI - Version](https://img.shields.io/pypi/v/pycogat) ![Static Badge](https://img.shields.io/badge/python-3.10-blue) 

# pycogat
Python package that splits district level CogAT score reports into student level files.

## Free Version vs Enterprise Version

### Free Version (PyPi)
- Limited single CogAT Narrative splitting, up to 25 students.

### Enterprise Version
- Unlimited single CogAT score report splitting.
- Unlimited batch CogAT score report splitting.
- Directory and subfolder creation.
- Zip Archive creation

📩 Contact: info@gw-datasolutions.com

## Installation
~~~ python
pip install pycogat
~~~

### Usage
~~~ python
import pycogat
from pycogat.cogat import cogat_split

cogat_split('C:\Documents\Reports\cogat_score_report.pdf',6)
~~~
The output will be *x* number of exported PDFs with the output label being the ID from the CogAT Score Report

### Documentation
|Input|Data Type|Documentation|
|---|---|---|
|pdf_object|string|The file path of the CogAT Score Report|
|id_char|int|The number of characters in the local id of the student|
