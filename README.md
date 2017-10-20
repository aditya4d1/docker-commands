# docker-commands
Scratchpad for Docker Commands

##Commands
```
sudo docker images
sudo docker build -t ubuntu-1404 .
sudo docker run -it ubuntu:latest
sudo docker run -it --device="/dev/kfd" adityaatluri/rocm-terminal:v1
sudo docker rmi -f rocm-kfd-only
sudo docker rmi -f 0b4876953557
sudo docker tag <tag-id> adityaatluri/rocm-kfd-only:v1
sudo docker push adityaatluri/rocm-kfd-only
sudo docker commit -m "Test 2" -a "Aditya Atluri" 87130bf8b241 rocm-kfd-only
sudo docker ps -a
sudo docker pull adityaatluri/rocm-terminal
sudo docker run -it --user aditya --device="/dev/kfd" rocm-trusty-base:user
sudo docker exec -it 3b39b196aa97
```
