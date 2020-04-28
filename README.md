# mirror-all-repos

A small tool to backup (mirror and update) all given code repositories.

Put repository list(s) in `./projects` folder.

Add a `.txt` file, each line is the relative path of a repository.

``` bash
export REMOTE_GIT_HOST=blah-blah
./pull-project-repos
```
