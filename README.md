#include <iostream>
#include <locale.h>
using namespace std;

int main()
{ 
    float n1,n2,n3,mp;
    cout<<"informe a nota do laboratório";
    cin>>n1;
    cout<<"informe a nota da avaliação semestral";
    cin>>n2;
    cout<<"informe a nota do exame final";
    cin>>n3;
    mp=((n1*2+n2*3+n3*5)/(2+3+5));
        if((mp>8) && (mp<10))
            {cout<<"Seu conceito é A, sua média é:"<<mp;
                }else if ((mp>=7) && (mp<8))
                    {cout<<"Seu conceito é B, sua média é:"<<mp;
                        }else if ((mp>=6) && (mp<7))
                            {cout<<"Seu conceito é C, sua média é:"<<mp;
                            }else if ((mp>=5) && (mp<6))
                                {cout<<"Seu conceito é D, sua média é:"<<mp;
                                    }else if (mp<5)
                                    {cout<<"Seu conceito é E, sua média é:"<<mp;
                                    }
                                }
