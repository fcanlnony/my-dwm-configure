![Screenshot](https://user-images.githubusercontent.com/76856769/124358355-7eefb600-dc52-11eb-8546-0c1109783bc6.png)
# my-dwm-configure                                                                                                       
安装dwm前你需要xorg，dmenu，以及一个终端                                                                                     
                                                                                                                         
安装                                                                                                                     
sudo make clean install                                                                                                 
                                                                                                                         
如果是使用xinit来登录桌面                                                                                                   
编辑.xinitrc并添加exec dwm                                                                                                 
                                                                                                                         
我使用的状态栏是                                                                                                           
slstatus ： https://github.com/LLluma/slstatus                                                                           
                                                                                                                         
默认的程序启动器                                                                                                           
dmenu                                                                                                                   
                                                                                                                         
所用到的插件及地址                                                                                                         
dwm-actualfullscreen ： https://dwm.suckless.org/patches/actualfullscreen/                                               
dwm-alpha-20201019-61bb8b2 : https://dwm.suckless.org/patches/alpha/                                                     
dwm-fixborders : https://dwm.suckless.org/patches/alpha/                                                                 
dwm-noborder-6.2 : https://dwm.suckless.org/patches/noborder/                                                           
dwm-activetagindicatorbar-6.2 : https://dwm.suckless.org/patches/activetagindicatorbar/                                 
dwm-attachdirection : https://dwm.suckless.org/patches/attachdirection/                                                 
                                                                                                                         
终端默认是st，如果需要修改默认终端请在config.def.h里面修改termcmd                                                               
                                                                                                                         
按键操作：                                                                                                                 
Alt+d打开程序启动器                                                                                                        
Alt+d打开终端                                                                                                             
Alt+b关闭上面的状态栏                                                                                                       
Alt+j/Alt+k切换窗口指定                                                                                                   
Alt+u/Alt+i修改窗口为横切或竖切                                                                                             
Alt+h/Alt+l增大或减小窗口                                                                                                  
Alt+Shift+Enter把当前窗口设置为主窗口                                                                                       
Alt+Tab查看窗口                                                                                                           
Alt+Shift+q关闭窗口                                                                                                       
Alt+Shift+w/s/e三种窗口模式                                                                                               
Alt+space（空格）切换为默认的窗口模式  
Alt+Shift+space（空格）切换当前窗口与主窗口位置                                                                 
Alt+g当前窗口全屏                                                                                                         
Alt+1/2/3/4/5/6/7/8/9切换1/2/3/4/5/6/7/8/9号工作区                                                                          
Alt+e离开dwm                                                                                                            
