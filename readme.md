
## Task1 ScreenShot ##



![Task1(day17)](https://user-images.githubusercontent.com/68742521/122908399-b1a3cf80-d371-11eb-81dd-733203b500e5.png)



## Task1 TextFile ##



```
sudo apt-get remove docker docker-engine docker.io containerd runc
sudo apt-get update
sudo apt-get install \
    apt-transport-https \
    ca-certificates \
    curl \
    gnupg \
    lsb-release
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /usr/share/keyrings/docker-archive-keyring.gpg
echo \
  "deb [arch=amd64 signed-by=/usr/share/keyrings/docker-archive-keyring.gpg] https://download.docker.com/linux/ubuntu \
  $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
sudo apt-get update
sudo apt-get install docker-ce docker-ce-cli containerd.io
```
Give user Sudo Permissions to Access Docker
```
sudo usermod -aG docker $USER
newgrp docker 
```



## Task2 ScreenShot ##



![Task2(day17)](https://user-images.githubusercontent.com/68742521/122908434-bc5e6480-d371-11eb-96c2-9fa54464eff0.png)



## Task2 TextFile ##



```
docker pull ubuntu:20.04
```



## Task3 ScreenShot ##



![Task3 (day17)](https://user-images.githubusercontent.com/68742521/122908477-c97b5380-d371-11eb-8a78-d1cb6c08e0b8.png)
![Task3(day17)](https://user-images.githubusercontent.com/68742521/122908482-ca13ea00-d371-11eb-94e9-31be8b895091.png)
![Task3 (day17)](https://user-images.githubusercontent.com/68742521/122908472-c84a2680-d371-11eb-9746-f795f16ef798.png)



## Task3 TextFile ##



Start Process
```
docker run -it ubuntu:20.04 sleep 400
```
Pause Process
```
docker pause docker_name
```
Stop Process
```
docker stop docker_name
```



## Task4 ScreenShot ##



![Task4(day17)](https://user-images.githubusercontent.com/68742521/122908550-def07d80-d371-11eb-8cf1-ea6f0c374056.png)



## Task4 TextFile ##



```
docker run -it ubuntu:20.04 bash
```



