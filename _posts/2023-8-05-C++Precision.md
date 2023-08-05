# C++ Precision

---

#include<iostream>  
#include<iomanip>//必要头文件   
using namespace std;  
int main()  
{  
	double sum;  
	sum=4.56789;  
	cout<<"方法一：保留两位小数"<<endl;  
	//第一种方法也是最常用的方法   
}  

*
这里的fixed是指"write floating-point values in fixed-point notation",用定点表示法表示浮点数!!  
是为了用来消除科学计数法的。其实只要出现fixed，则后面都是以fixed输出。  
fixed与setprecision(n)连用控制小数点后的位数，运用的只是定点数记数法。  
*

