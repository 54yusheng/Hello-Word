# Hello-Word
To Learn and To Learn
#include<iostream>
 
using namespace std;  //把"std"当中的所有符号，导入当前的名字空间，但是不赞成这种做法，在大工程中容易出现难以预料的Bug
 
using std::cout;
using std::endl;  //宜采用这种方式，用到哪个拿哪个！
 
 
int main()  //输出“Hello Word！”
{
	cout << "Hello Word！" << endl;  //endl=end line
 
	cin.get();  //等待获得用户的输入，这个的主要作用是避免小黑窗一闪而过的情况
				//但好像我这个在VS2019上运行的程序就算没有第9行语句，也能看到小黑窗
 
	return 0;  //函数前面的int要求我们返回值为整型
}
