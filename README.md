# OpenValidator

This is a proof of concept script to check the sanity of your Define-XML(CDISC Standard), with lightweight script languages.

## Usage

1. Place your Define.xml in the same folder of this script.
1. Run the script
```
$ ruby OpenValidator.rb
```

## Output

OpenValidator generates a comma-separated-value text file named `${DATE}_definecheck.csv`.
In this table, you will find the value of elements or attributes to be carefully checked when your submission.

## Limitation

Currently, this script just extracts important elements with values and the description of the reason why that should be checked. This script does not automatically omit the elements that will pass the check.
