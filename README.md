# Microcms Hugo
A very small serverless based CMS

## Prerequisites
* [Docker-for-Windows](https://hub.docker.com/editions/community/docker-ce-desktop-windows)

## How to run
Run the following in Powershell:
    ```powershell
    .\run.ps1 "cd microcms && hugo server --bind=0.0.0.0"
    ```
    
* Now open [http://localhost:1313](http://localhost:1313)


## How to get an interactive shell
Run the following in Powershell:
    ```powershell
    .\run.ps1 "/bin/sh"
    ```

## Create new src content from scratch
Run the following in Powershell:
    ```powershell
    .\run.ps1 "hugo new site microcms"
    ```

# Authors
- Sebastiaan Raven