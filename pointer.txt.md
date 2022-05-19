working on the rifehnjmska
wsetrdyughjnlmk

#include<iostream>
using namespace std;
class patient{
	public:
		int srno;
		int fees;
		void fun(int x,int y){
			x=srno;
			
			y=fees;
			
		}
	
	
};
class doctor{
	public:		
		int srno,salary;
		void fun(int x,int y){
			x=srno;
			y=salary;
			cout<<x<<y;
		}
};

int main(){
	patient obj;
	int x,y,z,m,n;
	cin>>x>>y;
	
	obj.fun(x,y);
	doctor obj1;
	cin>>m>>n;
	obj1.fun(m,n);
	cout<<m<<n;
	
}