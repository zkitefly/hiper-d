如果安装虚拟显卡过多，会造成如下图问题

![](https://gitcode.net/chearlai/ff/-/raw/main/14.png)

目前尚未有人报告虚拟网卡过多的问题

若你有强迫症，或者其他问题，你可以用以下方法删除过多虚拟网卡

首先在任务栏上的搜索框中，输入 `设备管理器`，然后选择“设备管理器”。

![](https://gitcode.net/chearlai/ff/-/raw/main/16.png)

展开“网络适配器”，就可以看到这些 `TAP-Windows Adapter V9` 为 Hiper 虚拟网卡，

选中 `TAP-Windows Adapter V9` 名称带有 `# 数字` 的网卡，点击上方的“×”卸载按钮，不要勾选“制除此设备的驱动程序软件。”，确定即可。

重复卸载无用的网卡即可！