4A - Watermelon
#include<stdio.h>
int main()
{
    int w;
 
    scanf("%d",&w);
    if(w%2==0 && w>2)
        printf("Yes\n");
    else printf("No\n");
}


281A - Word Capitalization

#include <bits/stdc++.h>
using namespace std;
int main()
{
 
	string s;
	cin >> s;
	if(s[0]>=97) s[0]-=32;
	// for (int i = 1; i < s.size(); ++i)
	// {
	// 	if(s[i]<97)s[i]+=32;
	// }
	cout << s << endl;
	return 0;
}

50A - Domino piling

#include<bits/stdc++.h>
using namespace std;

int main()
{
    int m,n;
    cin>>m>>n;
    cout<<(m*n)/2<<endl;
}







