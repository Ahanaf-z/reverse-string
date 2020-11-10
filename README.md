#include<stdio.h>
#include<string.h>

int main()
{
    int i,j,len,temp;
    
    int n,p,l,m;
    char str[100];
    scanf("%s",str);
    len=strlen(str);
    for(i=0;i<len;i++){
     if(str=='0'-'9'){
        n=n+1;}
        else if(n=='0'-'9' && n!='0'-'9'){
        p=n;
        }
        
    j=len-1;
    for(l=n;l<=p;l++){
    
    temp=str[i];
    str[i]=str[j];
    str[j]=temp;
    j--;}}
  // str[i]=str[j];
    //printf("i %d j %d\n",i,j);}
  printf("Reverse string %s ",str);
       
    return 0;}
