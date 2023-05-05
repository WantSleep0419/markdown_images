# 一： 安装准备

## **1. IBMC**

```
什么是IBMC： 
		华为服务器智能管理系统
```



## **2. kunpeng-kylin 镜像文件**

**安装虚拟机所需的镜像文件，以 .iso 结尾**

```
该手册演示安装的麒麟iso文件为：	
	kunpengKylin-Server-V10-SP3-General-Release-2303-ARM64.iso
```

![1683180669383](C:\Users\TROILA\AppData\Roaming\Typora\typora-user-images\1683180669383.png)

# 二： 开始安装

## 1. 进入IBMC

```
1.输入ibmc账号密码，点击登录
```

![1683180829770](C:\Users\TROILA\AppData\Roaming\Typora\typora-user-images\1683180829770.png )



![1683181365004](C:\Users\TROILA\AppData\Roaming\Typora\typora-user-images\1683181365004.png)

## 2.  创建虚拟机

### 2.1 选择 HTML5集成远程控制台(独占)

```
1.点击右下角的“启动虚拟控制台”，并选择“HTML5集成远程控制台(独占)”选项，可跳转到命令窗口
```

![1683181515824](C:\Users\TROILA\AppData\Roaming\Typora\typora-user-images\1683181515824.png)

**跳转后如下图：**

![1683181539366](C:\Users\TROILA\AppData\Roaming\Typora\typora-user-images\1683181539366.png)

### 2.2 挂载光驱（CD/DVD）

```
1.点击如下图标
```

![1683181701564](C:\Users\TROILA\AppData\Roaming\Typora\typora-user-images\1683181701564.png)

```
2.点击“...”并选择iso镜像文件“ kunpengKylin-Server-V10-SP3-General-Release-2303-ARM64.iso ”
```

![1683181781182](C:\Users\TROILA\AppData\Roaming\Typora\typora-user-images\1683181781182.png)

```
3.点击“连接”选项，成功后如图所示
```

![1683182178091](C:\Users\TROILA\AppData\Roaming\Typora\typora-user-images\1683182178091.png)

### 2.3 重启虚拟机

![1683182057926](C:\Users\TROILA\AppData\Roaming\Typora\typora-user-images\1683182057926.png)

**耐心等待一段时间后显示如下界面**

![1683182662106](C:\Users\TROILA\AppData\Roaming\Typora\typora-user-images\1683182662106.png)

### 2.4 开始安装

```
1.直接按“Enter”键，等待一段时间后，进入kunpengKylin的安装界面，如下所示：
```

![1683182861901](C:\Users\TROILA\AppData\Roaming\Typora\typora-user-images\1683182861901.png)

```
2.选择语言：
	这里我选择中文，	
	点击右下角的“继续”按钮
```

![1683184975369](C:\Users\TROILA\AppData\Roaming\Typora\typora-user-images\1683184975369.png)

#### 2.4.1 安装目的地配置

**选择安装目的地（用以选择需要挂载的磁盘**
	**勾选本地标准磁盘，“存储配置”选择“自定义”，点击完成（进入到自定义磁盘分区页面**

![1683185394050](C:\Users\TROILA\AppData\Roaming\Typora\typora-user-images\1683185394050.png)

**按需求分区后点击“完成”**

![1683185469741](C:\Users\TROILA\AppData\Roaming\Typora\typora-user-images\1683185469741.png)

**点击接受更改**

![1683185488878](C:\Users\TROILA\AppData\Roaming\Typora\typora-user-images\1683185488878.png)

#### 2.4.2 软件选择

**进行“软件选择”：**
	**选择“最小安装”，并将右侧的环境附件软件都勾上，点击完成**

![1683185765804](C:\Users\TROILA\AppData\Roaming\Typora\typora-user-images\1683185765804.png)

![1683185842138](C:\Users\TROILA\AppData\Roaming\Typora\typora-user-images\1683185842138.png)

#### 2.4.3 网络配置

**点击“网络和主机名”，配置网络信息**

![1683186510042](C:\Users\TROILA\AppData\Roaming\Typora\typora-user-images\1683186510042.png)



**显示有“被拔出”的以太网选项是没网的，应选择没有“被拔出”的以太网选项**

![1683186620788](C:\Users\TROILA\AppData\Roaming\Typora\typora-user-images\1683186620788.png)

```
设置主机名为：www.troila.kunpengKylin
	点击 “应用”
```

![1683186743169](C:\Users\TROILA\AppData\Roaming\Typora\typora-user-images\1683186743169.png)

**配置静态ip**

**点击配置**

![1683186831598](C:\Users\TROILA\AppData\Roaming\Typora\typora-user-images\1683186831598.png)

**选择ipv4选项**

![1683186867320](C:\Users\TROILA\AppData\Roaming\Typora\typora-user-images\1683186867320.png)

**“方法”选择“手动”**

![1683186919724](C:\Users\TROILA\AppData\Roaming\Typora\typora-user-images\1683186919724.png)

**指定静态IP并设置114dns**

![1683187085178](C:\Users\TROILA\AppData\Roaming\Typora\typora-user-images\1683187085178.png)

**点击保存，打开以太网，点击完成**

![1683187190319](C:\Users\TROILA\AppData\Roaming\Typora\typora-user-images\1683187190319.png)

![1683187209667](C:\Users\TROILA\AppData\Roaming\Typora\typora-user-images\1683187209667.png)

#### 2.4.4 用户设置

**用户设置：**
	**设置root用户密码，牢记！**
	**创建普通用户“ KPKylin ” ，并设置普通用户密码（牢记**

![1683185950536](C:\Users\TROILA\AppData\Roaming\Typora\typora-user-images\1683185950536.png)

![1683185963372](C:\Users\TROILA\AppData\Roaming\Typora\typora-user-images\1683185963372.png)

![1683186421080](C:\Users\TROILA\AppData\Roaming\Typora\typora-user-images\1683186421080.png)

![1683186389168](C:\Users\TROILA\AppData\Roaming\Typora\typora-user-images\1683186389168.png)



#### 2.4.5 开始安装

**点击“开始安装选项”，耐心等待安装完成**

![1683187672116](C:\Users\TROILA\AppData\Roaming\Typora\typora-user-images\1683187672116.png)

**安装完成后点击“重启系统“”**

# 三： 系统配置

## 3.1 接受许可

**进入系统后显示如下界面：**

![1683189051782](C:\Users\TROILA\AppData\Roaming\Typora\typora-user-images\1683189051782.png)

```
输入 1  按“ENter”后
```

![1683189094991](C:\Users\TROILA\AppData\Roaming\Typora\typora-user-images\1683189094991.png)

```
输入 2 ，按“ENter”后，接受许可
```

![1683189275857](C:\Users\TROILA\AppData\Roaming\Typora\typora-user-images\1683189275857.png)

```
输入 c ，按“ENter”返回到上一级，若显示如下信息，则表示已接受许可
```

![1683189327514](C:\Users\TROILA\AppData\Roaming\Typora\typora-user-images\1683189327514.png)

## 3.2 选择网络（可选）

```
输入 2  按“ENter”后 
输入 5  按“ENter”后 
输入 8  按“ENter”后 
```

![1683189327514](C:\Users\TROILA\AppData\Roaming\Typora\typora-user-images\1683189327514.png)

**显示 Network connect 表示网络配置成功**

## 3.3 用ssh远程连接

```
ssh 默认连接端口为22，为了提高安全性，现我们改变连接端口号为（11223）

防火墙开放开启11223端口号
# firewall-cmd --permanent --add-port=11223/tcp

查看11223是否开启，开启为yes
# firewall-cmd --query-port=11223/tcp
yes

修改sshd端口号为11223
# vim /etc/ssh/sshd_config
```

![1683192060854](C:\Users\TROILA\AppData\Roaming\Typora\typora-user-images\1683192060854.png)

```
重启sshd
systemctl restart sshd.service
```



# 四： 注意事项

## 4.1 安装时找不到磁盘

**创建物理盘时记得一定也要创建一个逻辑盘**

![1683192220642](C:\Users\TROILA\AppData\Roaming\Typora\typora-user-images\1683192220642.png)

**显示如上信息时，该问题可解决**









![image-20230505094213097](C:/Users/TROILA/AppData/Roaming/Typora/typora-user-images/image-20230505094213097.png)