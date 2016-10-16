#include <iostream>
using namespace std;

int main()
{
	char ASCII[9] = {1, 22, 2,
					 25, 16, 23,
					 3, 21, 4};
	
	for(int i=0;i<9;++i)
	{
		cout << ASCII[i];
		
		if(ASCII[i] == 2 ||
		   ASCII[i] == 23 ||
		   ASCII[i] == 4)
		{
			cout << endl;
		}
	}
	
	system("pause");
	
	return 0;
}
