# C++-program-learning
programme
#include<iostream>
using namespace std;
int main()
{
  double r,girth,area;
  const double PI=3.1415;
  cout<<"please input radius:\n";
  cin>>r;
  girth=2*PI*r;
  area=PI*r*r;
  cout<<"radius="<<r<<endl;
  cout<<"girth="<<girth<<endl;
  cout<<"area="<<area<<endl;
}

#include<iostream>
using namespace std;
int main()
{
  int a=451;
  cout<<a<<endl;
  cout<<(&a)<<endl;
  cout<<*(&a)<<endl;
}

#include<iostream>
using namespace std;
int main()
{
  long int a=10;b=20;t;
  long int *p1=&a;*p2=&b;,*pt;
  cout<<p1<<'\t'<<p2<<endl;
  cout<<*p1<<'\t'<<*p2<<endl;
  t=*p1;*p1=*p2;*p2=t;
  cout<<*p1<<'\t'<<*p2<<endl;
  pt=p1;p1=p2;p2=pt;
  cout<<p1<<'\t'<<p2<<endl;
  cout<<*p1<<'\t'<<*p2<<endl;
  cout<<a<<'\t'<<b<<endl;

}

Void 指针的强制类型转换
#include<iostream>
using namespace std;
int main()
{
  int a=65;
  int *ip;
  void *vp=&a;
  cout<<*(int*)vp<<endl;
  cout<<*(char*)vp<<endl;
  ip=(int*)vp;
  cout<<(*ip)<<endl;
}
引用测试
#include<iostream>
using namespace std;
int main()
{
  int a=2345;
  int *pa;
  int &ra=a;
  pa=&a;
  cout<<a<<'\t'<<ra<<'\t'<<*pa<<endl;
  cout<<(&a)<<'\t'<<(&ra)<<'\t'<<pa<<endl;
  cout<<(&pa)<<endl;
}
表达式：算术表达式、逻辑表达式、赋值表达式、条件表达式和逗号表达式
#include<iostream>
using namespace std;
int main()
{
  int a;
  char c;
  double x;
  a=2.0/4;
  x=2.0/4;
  cout<<a<<'\t'<<x<<endl;
  a=3+'A';
  c=3+'A';
  cout<<a<<'\t'<<c<<endl;
  cout<<3+'A'<<endl;
}
(a=b)=10
#include<iostream>
using namespace std;
int main()
{
 int a,b,c;
 cin>>a>>b>>c;
 max=a>b?a>c?a:c:b>c?b:c;
 cout<<"max="<<max<<endl;
}

x=a=3,5*6  x=3

cout<<"Hello!\nWorld.\n";
cout<<"Hello!"<<'\n'<<"World."<<'\n';
cout<<"Hello!"<<endl<<"World."<<endl;

#include<iostream>
#include<iomanip>
using namespace std;
int main()
{ int a,b,s;
  cout.setf(ios::showbase);
  a=01137;b=023362,s=a+b;
  cout<<"八进制数";
  cout<<oct<<a<<"+"<<b<<"="<<s<<endl;
  a=239;b=5618;s=a+b;
  cout<<"十进制数";
  cout<<dec<<a<<"+"<<b<<"="<<s<<endl;
  a=0x1a3e;b=0x4bf;s=a+b;
  cout<<"十六进制数";
  cout<<hex<<a<<"+"<<b<<"="<<s<<endl;
}
s=0;i=1;
loop:
  if(i<=100)
  { s+=i;
    i++;
    goto loop;
  }

s=0;i=1;
white(i<=100)
{ s+=i;
  i++;
}
s=0;i=1;
do 
{s+=1;
 i++;
}  while(i<=100)

for(s=0,i=1;i<=100;i++)
{ s+=1;
  i++;
}

s=0;i=1;
for(;;)
{ if(i<=100)break;
  s+=1;
  i++;
}














