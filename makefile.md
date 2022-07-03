根据文件依赖关系

![image-20220429173537159](C:\Users\10921\AppData\Roaming\Typora\typora-user-images\image-20220429173537159.png)

可以用shell语法

$(CC)等于gcc        $(RM)等于rm

![image-20220429175443110](C:\Users\10921\AppData\Roaming\Typora\typora-user-images\image-20220429175443110.png)



$^表示上一层被依赖的东西

$@表示目标文件

![image-20220429180230925](C:\Users\10921\AppData\Roaming\Typora\typora-user-images\image-20220429180230925.png)



继续简化

![image-20220429180546742](C:\Users\10921\AppData\Roaming\Typora\typora-user-images\image-20220429180546742.png)