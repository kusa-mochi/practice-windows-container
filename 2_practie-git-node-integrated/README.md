# How to build docker image

1. Download MinGit file from [here](https://github.com/git-for-windows/git/releases).
    
    A file name is like MinGit-2.35.3-64-bit.zip
    
1. Rename the file to "MinGit.zip"
1. Download Node.js ZIP archive from [here](https://nodejs.org/download/release/v14.15.3/node-v14.15.3-win-x64.zip).
1. Put the files (MinGit.zip, node-*-win-x64.zip) on this directory.
1. Run following command on the console.
    
    ```
    docker build -t <tag name> .
    ```