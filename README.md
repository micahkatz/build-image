# build-img

This is a bash script that serves as a shorthand for building docker images with versions.

-   Simply do `build-img <version>` to build.
-   Or `npx build-img <version>`

## How it works

-   This script will take your current directory name and use that as the docker image name
-   It will then tag the image with your version
-   It will use any Dockerfile that is located in your current directory
