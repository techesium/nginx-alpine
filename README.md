# Custom nginx docker image
This is a custom docker image based on the latest official nginx alpine image. Image contains changed UID and GID for nginx user and group: these changes lets you share volumes data between nginx and php-fpm without possible permission issues.
## Usage
Pull the image from docker hub:
```
docker pull hitmanx/nginx-alpine
```
