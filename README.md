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


