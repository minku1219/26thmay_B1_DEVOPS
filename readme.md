## Task1 ScreenShot ##



![Task1(day11)](https://user-images.githubusercontent.com/68742521/121641562-f5165800-caac-11eb-9073-ae52d5256fcd.png)




## Task1 TextFile ##



```
cd /mnt
sudo mkdir new
ls
```



## Task2 ScreenShot ##



![Task2(day11)](https://user-images.githubusercontent.com/68742521/121641016-48d47180-caac-11eb-85ad-bde04ff2346c.png)



## Task2 TextFile ##



```
EC2 > EBS > Volume > Create Volume > Actions > Attach Volume
```



## Task3 ScreenShot ##



![Task3(day11)](https://user-images.githubusercontent.com/68742521/121641026-4bcf6200-caac-11eb-808e-a6ca20bc9c47.png)
![Task3 (day11)](https://user-images.githubusercontent.com/68742521/121641023-4a9e3500-caac-11eb-835c-7bbcd67e4279.png)



## Task3 TextFile ##



```
sudo fdisk /dev/xvdf
n ---- Create New Partition
Enter ---- Use Default as Primary Partiton
Enter ---- Use Default as 1 as Partition Number
Enter ---- Use Default as 2048 as First Sector
+1G ---- As Last Sector
p ---- Print Created Partition
w ---- Save Partition
sudo mkfs.xfs /dev/xvdf1
sudo mount /dev/xvdf1 /mnt/new/
df -hT
```



## Task4 ScreenShot ##



![Task4(day11)](https://user-images.githubusercontent.com/68742521/121641033-4d008f00-caac-11eb-8b9c-37f1eeab64ee.png)
![Task4 (day11)](https://user-images.githubusercontent.com/68742521/121641029-4c67f880-caac-11eb-94a6-b072122e89f0.png)



## Task4 TextFile ##



```
sudo apt install apache2
systemctl status apache2
```



## Task5 ScreenShot ##



![Task5(day11)](https://user-images.githubusercontent.com/68742521/121641036-4e31bc00-caac-11eb-8e4c-9d076f031403.png)



## Task5 TextFile ##



```
cd /etc/apache2/sites-availabile
ls
sudo vim 000-default.conf
   --- Change Document root to /mnt/new/
   --- :wq
systemctl restart apache2
```



