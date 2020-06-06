# gitsync

## Description
syncs (pull or push) all github repos from a certain directory

## Install
~~~~shell
wget https://raw.githubusercontent.com/kkristof200/gitsync/master/gitsync -O /usr/local/bin/gitsync && chmod u+x /usr/local/bin/gitsync
# or
curl https://raw.githubusercontent.com/kkristof200/gitsync/master/gitsync > /usr/local/bin/gitsync && chmod u+x /usr/local/bin/gitsync
~~~~

## Usage
~~~~shell
gitsync [path_to_folder_where_the_repo_folders_are]
# path defaults to ~/github
~~~~

## Dependency
[push](https://github.com/kkristof200/push)
