## Task1-a ScreenShot##






## Task1-a Text File##





## Task1-b ScreenShot##



![Task1-b-(day6)](https://user-images.githubusercontent.com/68742521/120475309-d0dcbc00-c3c6-11eb-8bba-87329b89bbed.png)



## Task1-b Text File##


```
mkdir welcome
ls
sudo groupadd lnb
sudo chgrp lnb welcome/
ls -l
```


## Task1-c ScreenShot##



![Task1-c-(day6)](https://user-images.githubusercontent.com/68742521/120475346-ddf9ab00-c3c6-11eb-9c11-49a04a6cc28f.png)



## Task1 -c Text File##


```
sudo useradd u1
sudo useradd u2
sudo useradd u3
sudo usermod -a -G lnb u1
sudo usermod -a -G lnb u2
sudo usermod -a -G lnb u3
getent group lnb 
```


## Task1-d ScreenShot##



![Task1-d-(day6)](https://user-images.githubusercontent.com/68742521/120475389-eeaa2100-c3c6-11eb-9404-769ae69b6cd2.png)



## Task1-d Text File##


```
ls
ls -la welcome/
chmod g+rwx welcome/
chmod o-wx welcome/
ls -la welcome/
```


## Task2 Text File##


```
sudo apt-get remove package_name
```




