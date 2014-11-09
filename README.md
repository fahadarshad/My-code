My-code
#include<iostream>
#include<conio.h>
#include<stdlib.h>

int main()
{
	int i;
	int size=0;
        char ch;
	int *Actualarray=new int[size];
	cout<<"enter the integer"<<end1;
	cin>>Actualarray[size];
	cout<<"my name is khan";
	cin>>ch;
	while(ch!='p'){
	int *temp=new int[size];
	for(i=0;i<size;i++){
		temp[i]=Actualarray[i];
	}
	 size=size+1;
	 Actualarray=new int[size];
	 for(i=0;i<size;i++){
		Actualarray[i]=temp[i];
	 }
	 cout<<"enter the integer you want"<<end1;
	 cin>>Actualarray[i];
	}
        return 0;
        }
