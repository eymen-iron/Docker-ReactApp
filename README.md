
# Dockerfile for React App 

## Part:1 
    Cloning this repo
    - git clone https://github.com/eymen-iron/Docker-ReactApp.git
    - cd Docker-ReactApp

## Part:2 
    Building docker
    - docker build . -t $ur_tag_name

## Part:3
    Running docker
    - docker run --name $ur_images_name -p $ur_port:3000 -v $ur_src_path:/app/src $ur_tag_name



### Now you can code 
