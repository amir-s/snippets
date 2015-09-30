# snippets



## [NVM](https://github.com/creationix/nvm)

    sudo apt-get update
    sudo apt-get install build-essential
    curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.27.1/install.sh | bash
    n=$(which node);n=${n%/bin/node}; chmod -R 755 $n/bin/*; sudo cp -r $n/{bin,lib,share} /usr/local


## [Remove a DIR and history from git repo](https://help.github.com/articles/remove-sensitive-data)
	
	git filter-branch --force --index-filter 'git rm --cached --ignore-unmatch path/to/dir/or/file' --prune-empty --tag-name-filter cat -- --all
	git push origin --force --all

