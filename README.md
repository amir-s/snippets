# snippets



## [NVM](https://github.com/creationix/nvm)

    sudo apt-get update
    sudo apt-get install build-essential
    curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.27.1/install.sh | bash
    n=$(which node);n=${n%/bin/node}; chmod -R 755 $n/bin/*; sudo cp -r $n/{bin,lib,share} /usr/local


