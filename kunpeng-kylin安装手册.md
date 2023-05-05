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

![1683180669383](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/1683180669383.png)

# 二： 开始安装

## 1. 进入IBMC

```
1.输入ibmc账号密码，点击登录
```

![1683180829770](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/1683180829770.png)



![1683181365004](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/1683181365004.png)

## 2.  创建虚拟机

### 2.1 选择 HTML5集成远程控制台(独占)

```
1.点击右下角的“启动虚拟控制台”，并选择“HTML5集成远程控制台(独占)”选项，可跳转到命令窗口
```

![1683181515824](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/1683181515824.png)

**跳转后如下图：**

![1683181539366](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/1683181539366.png)

### 2.2 挂载光驱（CD/DVD）

```
1.点击如下图标
```

![1683181701564](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/1683181701564.png)

```
2.点击“...”并选择iso镜像文件“ kunpengKylin-Server-V10-SP3-General-Release-2303-ARM64.iso ”
```

![1683181781182](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/1683181781182.png)

```
3.点击“连接”选项，成功后如图所示
```

![1683182178091](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/1683182178091.png)

### 2.3 重启虚拟机

![1683182057926](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/1683182057926.png)

**耐心等待一段时间后显示如下界面**

![1683182662106](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/1683182662106.png)

### 2.4 开始安装

```
1.直接按“Enter”键，等待一段时间后，进入kunpengKylin的安装界面，如下所示：
```

![1683182861901](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/1683182861901.png)

```
2.选择语言：
	这里我选择中文，	
	点击右下角的“继续”按钮
```

![1683184975369](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/1683184975369.png)

#### 2.4.1 安装目的地配置

**选择安装目的地（用以选择需要挂载的磁盘**
	**勾选本地标准磁盘，“存储配置”选择“自定义”，点击完成（进入到自定义磁盘分区页面**

![1683185394050](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/1683185394050.png)

**点击自动选择分区（也可以通过左下角的 ”+“，单个卷单个卷的创建，但是这样太过繁琐（除非有特殊的需求），建议直接点击 自动创建，之后在自动创建的基础之上，再根据具体需求去更改它）**

![image-20230505160826490](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/image-20230505160826490.png)

**按需求分区后点击“完成”**

![1683185469741](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/1683185469741.png)

**点击接受更改**

![1683185488878](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/1683185488878.png)

#### 2.4.2 软件选择

**进行“软件选择”：**
	**选择“最小安装”，并将右侧的环境附件软件都勾上，点击完成**

![1683185765804](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/1683185765804.png)

![1683185842138](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/1683185842138.png)

#### 2.4.3 网络配置

**点击“网络和主机名”，配置网络信息**

![1683186510042](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/1683186510042.png)



**显示有“被拔出”的以太网选项是没网的，应选择没有“被拔出”的以太网选项**

![1683186620788](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/1683186620788.png)

```
设置主机名为：www.troila.kunpengKylin
	点击 “应用”
```

![1683186743169](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/1683186743169.png)

**配置静态ip**

**点击配置**

![image-20230505161143037](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/image-20230505161143037.png)

**选择ipv4选项**

![1683186867320](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/1683186867320.png)

**“方法”选择“手动”**

![1683186919724](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/1683186919724.png)

**指定静态IP并设置114dns**

![1683187085178](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/1683187085178.png)

**点击保存，打开以太网，点击完成**

![1683187190319](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/1683187190319.png)

**安装界面的“网络和主机名”显示以下界面代表配置完成**

![1683187209667](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/1683187209667.png)

#### 2.4.4 用户设置

**用户设置：**
	**设置root用户密码，牢记！**
	**创建普通用户“ KPKylin ” ，并设置普通用户密码（牢记**

![1683185950536](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/1683185950536.png)

![1683185963372](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/1683185963372.png)

![1683186421080](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/1683186421080.png)

![1683186389168](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/1683186389168.png)



#### 2.4.5 开始安装

**点击“开始安装选项”，耐心等待安装完成**

![1683187672116](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/1683187672116.png)

**安装完成后点击“重启系统“”**

# 三： 系统配置

## 3.1 接受许可

**进入系统后显示如下界面：**

![1683189051782](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/1683189051782.png)

```
输入 1  按“ENter”后
```

![1683189094991](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/1683189094991.png)

```
输入 2 ，按“ENter”后，接受许可
```

![1683189275857](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/1683189275857.png)

```
输入 c ，按“ENter”返回到上一级，若显示如下信息，则表示已接受许可
```

![1683189327514](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/1683189327514.png)

## 3.2 选择网络

```
输入 2  按“ENter”后 ，准备选择前面图形界面时的“以太网配置”
```

![image-20230505140505170](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/image-20230505140505170.png)

**在 2.4.3 中 我们选择了 名为“enp125s0f3” 的以太网，所以我们在这一步也要选择对应名称的以太网即可**
![image-20230505141037704](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/image-20230505141037704.png)

```
输入 5  按“ENter”后 
```

![image-20230505141254888](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/image-20230505141254888.png)

**“connect automatically after reboot” 为 “重启后自动连接配置(自动的配置是我们在 2.4.3 配置的ip地址与网关等)”**

**“apply configuration in installer” 为 “在安装程序中应用配置（需再次手动配置，强烈不推荐）”**

**这里我们选择7，应用前面图形界面时的配置，不选择自动**

```
输入 7  按“ENter”后 ，会变成如下图所示的状态（打上 ” x “ 就算选择成功）
```

![image-20230505171523974](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/image-20230505171523974.png)

```
输入 c 按“ENter”后，再次输入 c 按“ENter”后，进入如下界面
```

![image-20230505171757845](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/image-20230505171757845.png)

**会发现这里并没有打上” x “，不用着急 ，我们重启一次**

```
输入 q ，按Enter后，输入 yes 确认重启
```

![image-20230505171939826](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/image-20230505171939826.png)

**静静等待重启完成后显示如下界面：**

![image-20230505172018092](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/image-20230505172018092.png)

**显示  connected 表示网络配置成功**

==当然，如果要是先配置的 接受许可 ，当配置网络重启步骤后是看不到这个界面的，它会直接进入登录界面==

![image-20230505172248921](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/image-20230505172248921.png)

**此时输入 管理员账户密码后，可进行  ping 操作验证 网络配置是否可行**

```
ping www.baidu.com
```

![image-20230505172506012](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/image-20230505172506012.png)

**网络配置成功！**

## 3.3 用ssh远程连接

```
ssh 默认连接端口为22，为了提高安全性，现我们改变连接端口号为（11223）

防火墙开放开启11223端口号
# firewall-cmd --permanent --add-port=11223/tcp

重启防火墙服务
# systemctl restart firewalld

查看11223是否开启，开启为yes
# firewall-cmd --query-port=11223/tcp
yes

修改sshd端口号为11223
# vim /etc/ssh/sshd_config
```

![1683192060854](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/1683192060854.png)

```
重启sshd
systemctl restart sshd.service
```



# 四： 注意事项

## 4.1 安装时找不到磁盘

**创建物理盘时记得一定也要创建一个逻辑盘（强烈建议准备安装时检查该部分）**

```
在首页页面点击”储存“选项
```

![image-20230505152749420](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/image-20230505152749420.png)

```
进入到如下界面后，点击”添加“，目的是为了添加一个逻辑盘用以储存虚拟机 （逻辑盘：将PC机中真实存在的硬盘(物理硬盘)划分为若干个逻辑硬盘。逻辑硬盘并不是真实存在的，它是创建分区之后代表各个分区的逻辑盘符）
```

![image-20230505152937557](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/image-20230505152937557.png)

```
1.初始化类型：quick init（快速初始化，会将逻辑盘中的数据擦除）
2.RAID级别：选0（再RAID级别中具有最高的存储性能（磁盘容量不浪费，读写很快），因无任何冗余，任何一块硬盘发生故障，整个RAID上的数据将不可恢复）
	选1，5，10等（需要多块硬盘，主要用于备份，恢复数据）
	我这里只有一块硬盘，所以只能选0
3.勾选物理盘（Disk0） （物理盘：该服务器实际拥有的储存盘）
```



![image-20230505153144096](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/image-20230505153144096.png)

```
保存后回到首页
```

**显示如下信息时，该问题可解决**

![image-20230505153946509](https://markdown-images0419.oss-cn-beijing.aliyuncs.com/images/image-20230505153946509.png)
