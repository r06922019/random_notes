# random_notes

## random sleep

### gnu bash

```
$ sleep $(echo "${RANDOM}" | cut -b 1)s
```

```
brew install coreutils
alias date=gdate
alias cut=gcut
```

## time strings

### bash
``` bash
date "+%Y%m%d_%H%M%S"
```

### python 
``` python
time.strftime("%Y%m%d_%H%M%S") -> '20201116_113252'
```
