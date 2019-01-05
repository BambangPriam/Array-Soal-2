# Array-Soal-2
    #include<stdio.h>
    #include<conio.h>


    void tukar(int nilai[5]){
    int t= nilai[0];
    nilai[0]=nilai[4];
    nilai[4]=t;

    int t1=nilai[1];
    nilai[1]=nilai[3];
    nilai[3]=t1;

    }

    void main(){
    int nilai[5]={5,10,6,0,4}, i;

    printf("Array A : \n");
    for(i=0;i<5;i++){
        printf("Elemen ke-%i : %d \n", i, nilai[i]);
    }
    printf("\n");

    printf("Array B : \n");
    tukar(nilai);
    for(i=0;i<5;i++){
        printf("Elemen ke-%i : %d \n", i, nilai[i]);
    }
    }
   ![img](https://raw.githubusercontent.com/BambangPriam/Array-Soal-2/master/Soal%202.png)
