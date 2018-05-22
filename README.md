# tips-n-tricks


## Bash history search, partial + up-arrow
From https://askubuntu.com/questions/59846/bash-history-search-partial-up-arrow

Add following to .inputrc
```bash
  ## arrow up
"\e[A":history-search-backward
## arrow down
"\e[B":history-search-forward
```
