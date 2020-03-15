# How to login and push

## Tag image

`docker tag 69c97d8fd674 softwrdev/python-cuda:10.2-py37-buster`

## Login to Docker hub

After this you will be prompted for a password:

`docker login --username=softwrdev`

## Push image

`docker push softwrdev/python-cuda:10.2-py37-buster`
