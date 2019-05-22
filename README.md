# ch934x-linux-driver
# Description
Linux driver for usb to multi serial ports chip ch9342, ch9344, etc.  
When ch934x usb device plug in, you will see tty device named "ttyWCHUSBx(x means tty index)" in /dev directory.

# Features
 Multi device support.  
 Support device hot plug.  
 Dynamic tty port number manager.  
 
## 1. BUILDING
 $ sudo make

## 2. LOAD
 $ sudo make load  
 or you can use  
 $ sudo insmod ch934x.ko
 
## 3. UNLOAD
 $ sudo make unload  
 or you can use  
 $ sudo rmmod ch934x.ko
 
## 4. AUTOLOAD SINCE BOOT
  $ sudo make install
  
## 5. CANCEL AUTOLOAD SINCE BOOT
  $ sudo make uninstall
  
## Note
  Any question, you can send feedback to mail: tech@wch.cn

