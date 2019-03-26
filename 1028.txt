#include <bits/stdc++.h>
#include <string>
#include <algorithm>
using namespace std;
int main()
{
    int c;

    cin>>c;
    for(int i=0;i<c;i++)
    {
        int a, b, c;
        int m=0;
        cin>>a>>b;
       c= max(a,b);
        for(int j=1;j<=c/2;j++)
        {
            if(a%b==0 || b%a==0)
        {
            cout<<min(a,b)<<endl;
        }


         else if ((a%j ==0) &&(b%j==0) )
         {
             if(m<j)
             {
                 m=j;

             }
         }


            }




    }


  return 0;
}
