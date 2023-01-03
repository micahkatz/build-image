# build-image
This is a bash script that serves as a shorthand for building docker images with versions. 
- Simply do `build-image <version>` to build.

## Setup
- Clone this repo
- Symbolically link this script to your path
`ln -s <input-file> <new-symbolic-link>`
  - e.g. `ln -s build-image /usr/local/bin/build-image`
- Now you should be able to run the script anywhere

## How it works
- This script will take your current directory name and use that as the docker image name
- It will then tag the image with your version
- It will use any Dockerfile that is located in your current directory
