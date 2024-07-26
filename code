#include<bits/stdc++.h>
using namespace std;

string generatePassword(int length) {
    const string characters = 
        "0123456789"
        "abcdefghijklmnopqrstuvwxyz"
        "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
        "!@#$%^&*()_+-=[]{}|;':,./<>?";
        
    string password;
    for(int i=0;i<length;i++){
        password+=characters[rand()%characters.length()];
    }
    return password;
}

signed main() {
    int length;
    cin>>length;
    string password=generatePassword(length);
    cout<<"Generated password: "<<password<<"\n";
}
