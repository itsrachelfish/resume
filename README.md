# resume
It's my resume

# how to generate a pdf version
```
DEBUG=electronpdf* electron-pdf https://wetfish.net/resume/ final.pdf --pageSize='{"width":242000,"height":525000}'
pdftk final.pdf cat 1 output final-edited.pdf
```
