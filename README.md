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

# (3) move to personal 'stakiran'
After: https://github.com/stakiran/test_transfer/

Test: Access to https://github.com/stakiran-org/test_transfer/ -> Redirected.

Test: git clone https://github.com/stakiran/test_transfer -> Same as (2)

Test: push -> :o: and warning shown.

```terminal
Counting objects: 3, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 359 bytes | 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
remote: This repository moved. Please use the new location:
remote:   https://github.com/stakiran/test_transfer.git
To https://github.com/stakiran-org/test_transfer
   636cc46..fd84bd8  master -> master
```
