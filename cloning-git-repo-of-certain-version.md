Hey folks, 

I just learn something interesting about cloning git repository.

When we do `git clone repoUrl`  it will clone whole history of that repo . But if we want only recent version of that repo we can use `--depth` flag 

`git clone --depth=1 url` give 1 recent commit
