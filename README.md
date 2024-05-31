include <iostream>
include <time.h>
using namespace std;

int main()
{
	double start, stop;
	start=clock();
	for (int i=0;i<100;i++)
	{
		cout<<" The number is "<<i<<endl;
	}

{	stop =clock();
cout<<"It took "<<(double(stop-start)/CLOCKS_PER_SEC)<<" seconds for cout"<<endl;
cin.ignore();
}


