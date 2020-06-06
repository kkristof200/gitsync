# syncall

## Description
syncs (pull or push) all github repos from a certain directory

## Install
~~~~shell
wget https://raw.githubusercontent.com/kkristof200/syncall/master/syncall -O /usr/local/bin/syncall && chmod u+x /usr/local/bin/syncall
# or
curl https://raw.githubusercontent.com/kkristof200/syncall/master/syncall > /usr/local/bin/syncall && chmod u+x /usr/local/bin/syncall
~~~~

## Usage
~~~~shell
syncall [path_to_folder_where_the_repo_folders_are]
# path defaults to ~/github
~~~~

## Dependency
[push](https://github.com/kkristof200/push)
