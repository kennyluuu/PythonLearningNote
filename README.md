# PythonLearningNote
the first time to use github.
TEST

### 随手记录以便日后查阅
1.shape=()与shape=[]的区别  
答：定义a=np.array((1))时候输出一个shape为()的整数1  
    定义a=np.array((1,))时候输出一个shape为(1,)的一维数组[1]  
    定义a=np.array([1])和（[1,]）输出结果一样  
结论：在定义array或者tensor的shape=时，最好用[]，尤其是rank=0的一维数组时用(1,)，而不是(1)后者会被识别为带有小括号的整数1
