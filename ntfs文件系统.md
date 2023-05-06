### NTFS系统的总体结构

![image-20230420184842652](D:\Program Files\notes\tx-notes\ntfs文件系统.assets\image-20230420184842652.png)

![image-20230420184910417](D:\Program Files\notes\tx-notes\ntfs文件系统.assets\image-20230420184910417.png)

### 簇流运行的数据结构

- 簇流是存放数据的区域

- 簇流运行：是记录簇流的具体在文件系统的哪个位置的代码

  点击MFT，转到MFT的第一个扇区。  80下方是簇流运行的结构，

  - 40表示簇流的大小是64个簇
  - 00000C 表示簇流的起始处是786432
  - 786432 + 64 = 786496是结束簇

  ![image-20230505205936854](D:\Program Files\notes\tx-notes\ntfs文件系统.assets\image-20230505205936854.png)

  ![image-20230505210133635](D:\Program Files\notes\tx-notes\ntfs文件系统.assets\image-20230505210133635.png)

![image-20230505204402706](D:\Program Files\notes\tx-notes\ntfs文件系统.assets\image-20230505204402706.png)

 

![image-20230505210650419](D:\Program Files\notes\tx-notes\ntfs文件系统.assets\image-20230505210650419.png)
