#include<stdio.h>
#include<string.h>
int times(char s[],char w[])
{
   int i=0,times=0;
   while(s[i])
   {
     j=0;
     while(w[j])
     {
       if(w[j]!=5[i+j])
           break;
           j++;
      }
      if(!w[j])
      {
      times++;
      i+=j-1；
      }
      i++；
      }
      return times;
     }
     int main()
     {
     char s[1000]='''';
     printf("\n");
     gets(s);
     char  w[10]='''';
     printf("\n");
     get(w);
     printf("%d\n",times(strlwr(s)));
     return 0;
     }
