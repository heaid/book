---
description: 编写中
---

# Switch 游戏机

{% hint style="info" %}
使用网关模式，可以达到类似路由器的效果，让整个网关下的所有设备都能够使用节点网络

前提是设备在他同一个WIFI网络下。
{% endhint %}

### 以下距离4个平台的软件设置方法，其他软件也大同小异

以下操作基于软件已经正常联网使用的情况下。

{% tabs %}
{% tab title="Clash for Windows" %}
### 打开允许局域网连接。记住端口为7890

![](.gitbook/assets/image%20%2844%29.png)

### 查询路由分配给你电脑本机的IP地址

![](.gitbook/assets/image%20%2843%29.png)

### 那么就知道了地址是192.168.0.135端口7890
{% endtab %}

{% tab title="Clash for Android" %}

{% endtab %}

{% tab title="Clash X" %}

{% endtab %}

{% tab title="Shadowrocket" %}

{% endtab %}
{% endtabs %}

### 打开switch或者其他需要联网的设备，找到WIFI，点击进入详情，找到HTTP代理，选择手动，然后将上述的服务器地址和端口填入，连接WIFI后就可以了

