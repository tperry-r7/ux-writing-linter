vale.ini example

```
# This goes in a file named either `.vale.ini` or `_vale.ini`.
StylesPath = .github
MinAlertLevel = suggestion # suggestion, warning or error

# Only Markdown and .txt files; change to whatever you're using.
[*.{md,txt}]
# List of styles to load. Loading our styles from .github/valeStyles
BasedOnStyles = valeStyles
```