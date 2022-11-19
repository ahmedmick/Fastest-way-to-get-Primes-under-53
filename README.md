# Fastest-way-to-get-Primes-under-53

#include <bits/stdc++.h>
using namespace std;

int main() {
    int t=53;
    while(t--){
        int x = 60-t;
        if (((1ull << (x-1)) & 4579536062977110))
        {
            cout<<x<<" is Prime"<<endl;
        }
        else{
            cout<<x<<" is not Prime"<<endl;
        }
    }
    return 0;
}
