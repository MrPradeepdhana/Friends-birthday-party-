#include <iostream>

using namespace std;

int main() {
	int num;
	cin >> num;
	while(num--)
	{
	 int friends, choc; cin>>friends>>choc;
	 if(choc%friends==0) cout<<"Yes\n";
	 else cout<<"No\n";
	}
}
