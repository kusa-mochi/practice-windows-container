# How to build docker image

1. Download MinGit file from [here](https://github.com/git-for-windows/git/releases).
    
    A file name is like MinGit-2.35.3-64-bit.zip

1. Rename the file to "MinGit.zip"
1. Put the file on this directory.
1. Run following command on the console.
    
    ```
    docker build -t <tag name> .
    ```