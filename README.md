# ubuntu-ssh-enabled

NOTE: THIS IMAGE IS TO BE USED FOR TEST AND DEV PURPOSES ONLY! NOT TO BE USED IN A PRODUCTION ENVIRONMENT!

SSH Enabled Ubuntu Image for Test and Dev purposes ONLY!

## Use:
Build the image:
```docker build .```

 list the images:
 ```docker image ls```

 tag your image 
 ```docker tage <image_id> <image_name>```
Run the container:

```docker run it -d <image_name>```

Identify the Internal IP

```docker inspect <container-id-name>```

SSH

```ssh <container-ip>```

**Username:** root

**Password:** Password

Based on : https://docs.docker.com/engine/examples/running_ssh_service/