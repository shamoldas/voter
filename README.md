#include<stdio.h>
main()
{
    int i,j,k,l,vot[4]={0};
    j=1;k=2;l=3;
    printf(" press 1 to 3 & 0 press to stop");
    while(i!=0){
          scanf("%d",&i);
          if(i==1){
             vot[1]++;
             i=j;

}
else if(i==2){
    vot[2]++;
k=i;
}
else if(i==3){
    vot[3]++;
    l=i;

}
}
printf("candidet 1 has got %d vot\n",vot[j]);
printf("candidet 2 has got %d vot\n",vot[k]);
printf("candidet 3 has got %d vot\n",vot[l]);
if(vot[j]>vot[k]&&vot[j]>vot[l])
    printf(" candinate 1 is win");
    else if (vot[k]>vot[j]&&vot[k]>vot[l])
    printf("winner cantinate 2");
else if(vot[l]>vot[k]&&vot[l]>vot[j])
    printf(" winer 3");
else if(vot[j]==vot[k]&&vot[k]==vot[l])
    printf("1 , 2,3 candidet draw");
else if(vot[k]==vot[l])
    printf("2&3 candidet draw");
else if(vot[l]==vot[j])
    printf("1 &3 candidet draw");
else if(vot[j]==vot[k])
    printf("1,2 candidet are draw");
}





