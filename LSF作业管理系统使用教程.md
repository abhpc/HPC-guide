#### 1.提交作业

    $ bsub < xxx.lsf

#### 2.查看作业

    $ bjobs

通过此命令可以获得作业的信息如ID和运行状态等。

#### 3.中断作业

    $ bkill [作业ID]

有时节点硬件故障引起作业中断，但LSF无法自动取消时，可以使用强制kill命令：

    $ bkill -r [作业ID]

中断全部作业：

    $ bkill 0
