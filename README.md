# test_transfer
personal repo -> org repo -> personal repo.

# (1) personal repo
https://github.com/stakiran/test_transfer/

# (2) move to org 'stakiran-org'
After: https://github.com/stakiran-org/test_transfer/

Test: Access to https://github.com/stakiran/test_transfer -> Redirected.

Test: git clone https://github.com/stakiran/test_transfer

```gitconfig
[remote "origin"]
	url = https://github.com/stakiran/test_transfer
```

Test: push -> :o:, and warning shown.

```terminal
remote: This repository moved. Please use the new location:
remote:   https://github.com/stakiran-org/test_transfer.git
To https://github.com/stakiran/test_transfer
   4c28cb6..7904550  master -> master
```
