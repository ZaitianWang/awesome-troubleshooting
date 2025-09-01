# Problem

用outlook邮箱登录新的Windows电脑后，系统会自动用邮箱前五个字母注册本机用户名，很烦。

# Solution

## Step 1 注册第二个账号

设置中点击 改用本地账户登录，设置本地账户，用户名输入想要的完整名称，完成后重启，用本地账户登录。

## Step 2 注册第三个账号

在设置中再注册另一个本地账户，设为管理员。

## Step 3 修改用户名

用第三个账户登录，~~命令行中输入`ren C:\Users\Alice Alice123`，然后~~在文件夹里给用户目录改名字, `regedit`打开注册表，在`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\ProfileList`中修改用户名。

## Step 4 登录outlook账户

切回第二个账户，再登录outlook邮箱，应该就ok了。
