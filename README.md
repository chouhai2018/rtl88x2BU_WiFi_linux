# rtl88x2BU_WiFi_linux

# rtl88x2BU无线网卡ubuntu驱动（装好5G杠杠滴）

![无线信号](https://user-images.githubusercontent.com/39079284/90975485-4168c980-e567-11ea-9d05-e8d6b68ecee5.png)

#安装准备</br>

sudo apt install build-essential cmake

#安装</br>
git clone https://github.com/chouhai2018/rtl88x2BU_WiFi_linux.git

cd rtl88x2BU_WiFi_linux

sudo make

sudo make install

重启系统，插上usb网卡就可以使用了

#系统支持
ubuntu 20.10

ubuntu 20.04

ubuntu 19.10

ubuntu 19.04

相应ubuntu派生版本同支持

树梅派支持同ubuntu core版本

修改自官方驱动