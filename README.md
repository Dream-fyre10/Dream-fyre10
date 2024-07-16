#include<bits/stdc++.h>
using namespace std;

class Club
{
    public:
    string name;
    int est;
    int trophy;
    int win;

    void clubinfo()
    {
        cout << " " << endl;
        cout << "Name: "  << name  << endl;
        cout << " " << endl;
        cout << "Est " << est  << endl;
        cout << "Trophies " << trophy << endl;
        cout << "Victories " << win<< endl;
    }

};


int main ()
{
    Club FCB;
    FCB.name= "Barcelona";
    FCB.est = 1899;
    FCB.trophy = 77;
    FCB.win = 1000;

    FCB.clubinfo();


    return 0;
}
