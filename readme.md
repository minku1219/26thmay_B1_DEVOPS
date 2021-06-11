## Task1 ScreenShot ##



![Task1 (day12)](https://user-images.githubusercontent.com/68742521/121677061-04a89780-cad3-11eb-995e-a74fadb94b9c.png)
![Task1(day12)](https://user-images.githubusercontent.com/68742521/121677066-070af180-cad3-11eb-98ef-5f898f52208f.png)



## Task1 TextFile ##



```
EC2 > EBS > Volume > Create Volume > Actions > Attach Volume
mount /dev/xvdf1 /root/welcome
df -hT
```



## Task2 ScreenShot ##



![Task2 (day12)](https://user-images.githubusercontent.com/68742521/121677070-08d4b500-cad3-11eb-8398-b93097670e16.png)



## Task2 TextFile ##



```
cd welcome/
vim index.html
cat index.html
```



## Task3 ScreenShot ##



![Task3 (day12)](https://user-images.githubusercontent.com/68742521/121677575-afb95100-cad3-11eb-8564-5e3a3dc1b700.png)

![Task3(day12)](https://user-images.githubusercontent.com/68742521/121677085-0b370f00-cad3-11eb-9120-0611fd85f39f.png)



## Task3 TextFile ##



```
EC2 > EBS > Volume > Create Volume > Actions > Detach Volume > Attach Volume
cd /etc/apache2/sites-availabile
ls
sudo vim 000-default.conf
   --- Change Document root to /root/new/
   --- :wq
systemctl restart apache2
```


