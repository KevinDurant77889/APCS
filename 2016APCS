#include <iostream>
#include <vector>
using namespace std;

int main()
{
	 vector<int> myv;
	 int student;
	 int point;
	 int best_sroce = 0;
	 int worst_sroce = 0;
	 cout << "請輸入學生人數 : ";
	 cin >> student;
	 for (int i = 0; i < student; i++)
	 {
		  cin >> point;
		  myv.push_back(point);
	 }
	 
	 for (int i = 0; i < student; i++)
	 {
		  if ( myv[i] > 59 )
		  {
			   if (best_sroce < myv[i])
			   {
			    best_sroce = myv[i];
			   }
		  }
		  else
		  {
			   if (worst_sroce < myv[i])
			   {
			    worst_sroce = myv[i];
			   }
		  }
	 }
	 for (int i = 0; i < student; i++)
	 {
	 	 cout << myv[i] ;
		  if (i != student - 1)
		  {
		   cout << " ";
		  }
	 }
	 
	 cout << endl;
	 
	 if (worst_sroce == 0){
	  cout << "best case" << endl;
	 }
	 else {
	  cout << worst_sroce << endl;
	 }
	 
	 if (best_sroce == 0){
	  cout << "worst case" << endl;
	 }
	 else {
	  cout << best_sroce;
	 }
	 system("pause");

}
