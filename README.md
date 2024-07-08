#include<stdio.h>
#include<stdbool.h>
#include<math.h>
// 10-masala 
 void  ten (int n, int m){
 	
  int i,j,a;
  
  printf("n ni kirgizing:\nn= ");
  scanf("%d",&n);
  
  printf("m ni kirgizing:\nm= ");
  scanf("%d",&m);
  
  a=1;

  for(i=1; i<=n; i++){
  	
    for(j=1; j<=m; j++){
    	
        if(i>1 && i<n && i==j || j+i==m+1 && j>1 && j<m ||i>1 && j>i && j>1 && j<m || j>1 && i>1 && i<n && i>j ){
        	
        printf("0\t");
        
        }
        
        else{
        	
        printf("%d\t",a);
        a+=1;
        
        }
    }
    
    printf("\n");
  }

 }
 
//9-masala 

void  nine(int n, int m){
  int i,j,a,b;
  
  printf("n ni kirgizing:\nn= ");
  scanf("%d",&n);
  
  printf("m ni kirgizing:\nm= ");
  scanf("%d",&m);
  
  a=1;
  b=2;

  for(i=1; i<=n; i++){
  	
    for(j=1; j<=m; j++){
    	
        if(i==j){
        	
        printf("%d\t",a);
        a+=2;
        
        }
        
        else if(i+j==m+1 && i>j || i+j==m+1 && j>i){
        printf("%d\t",b);
        b+=2;
        
        }
        
        else{
        	
        printf("\t");
        
        }
        
    }
    printf("\n");
  }

 }
 
// 8-masala 

 void  eight(int n,int m){
 	
  int i,j,a,b;
  
  printf("n ni kirgizing:\nn= ");
  scanf("%d",&n);
  
  printf("m ni kirgizing:\nm= ");
  scanf("%d",&m);
  
  a=1;
  b=2;

  for(i=1; i<=n; i++){
  	
    for(j=1; j<=m; j++){
    	
        if(i==j || j>i){
        printf("%d\t",a);
        
        a+=2;
        }
        
        else{
        	
        printf("%d\t",b);
        b+=2;
        
        }
    }
    printf("\n");
  }
 
 }

//7- masala

 void seven( int n,int m){
 	
  int i,j,k,a,s;
  
  printf("n ni kirgizing:\nn= ");
  scanf("%d",&n);
  printf("m ni kirgizing:\nm= ");
  scanf("%d",&m);
  
  a=2;
  

  for(i=1; i<=n; i++){
  	
    for(j=1; j<=m; j++){

    bir:
    	
    s=0;
    
     for(k=1; k<=a; k++){
     	
      if(a%k==0){
      	
      s+=1;
      
      }
      
     }
      if(s==2){
      	
      printf("%d\t",a);
      
      a+=1;
      }
      
      else{
      	
      a+=1;
      
      goto bir;
      
      }

    }
    printf("\n");

  }

 }
 //6-masala
 
	void six(int n,int m){
  int i,j,k;
  
  printf("n ni kirgizing:\nn= ");
  scanf("%d",&n);
  
  printf("m ni kirgizing:\nm= ");
  scanf("%d",&m);
  
  k=0;

  for(i=1; i<=n; i++){
  	
    for(j=1; j<=m; j++){
    	
        if(i%2!=0){
        	
        k+=1;
        
        printf("%d\t",k);
        }
        else{
        	
        printf("%d\t",k);
        k-=1;
        }
    }
    
    printf("\n");
    
    k+=3;
    
  }
 }
 //5- masala
 
	void five(int n, int m){
	   
	   printf("n= "); scanf("%d",&n);
	   printf("m= "); scanf("%d",&m);
	   
	   	 	int i,j,k=2,s=0;
	   	 	
		   for(i=1;i<=n;i++)	{
			 
			 
			 for(j=1;j<=m; j++){
			 	
			 	if(i+j==n+1){
			 		
			 		printf("%d\t",k);
			 			s=s+k;
			 		k=k+2;
			 	
			 	}
			 	
			 	else printf("0\t");
	
				 
}
					printf("\n");

}
 						printf("%d \n",s);
}
//4-masala

	void four(int n,int m){
	   
	   printf("n= "); scanf("%d",&n);
	   printf("m= "); scanf("%d",&m);
	   
	   	 	int i,j,k=1,s=0;
	   	 	
		   for(i=1;i<=n;i++)	{
			 
			 
			 for(j=1;j<=m; j++){
			 	
			 	if(i==j){
			 		
			 		printf("%d\t",k);
			 			s=s+k;
			 		k=k+2;
			 	
			 	}
			 	
			 	else printf("0\t");
	
				 
}
					printf("\n");

}
 						printf("%d \n",s);
}
//3-masala

	void three(int n ,int m ){
	   
	    printf("n= "); scanf("%d",&n);
	    printf("m= "); scanf("%d",&m);
	   
	   	 	int i,j,k=1;
	   	 	
		   for(i=1;i<=n;i++)	{
			
			 for(j=1;j<=m; j++){
			 
			 printf("%d\t",k);
			 	k+=5;
			 	 }	
printf("\n");
				  }
				k++;


}
// 1-masala
	void  one(int n, int m){
		int k=1;
	    printf("n= "); 	   	scanf("%d",&n);
		printf("m= ");  	scanf("%d",&m);
	   	 	int i,j,s=0;
	   	 	
		   for(i=1;i<=n;i++){
			 
			 s=0;
			 
			 for(j=1;j<=m; j++){
			 	if (j==n){
			 				 	printf("%d  ",k);	 
			 				 	
			 	}
	             else {
	             		printf(" %d + ",k);
	             }
	             s+=k;
	             	k+=1;
			 	 }	
			
				  printf("= %d \n",s);

}
            
}
// 2-masala
	void two(int n,int m){
 	
 	 int i,j,s,a,b;
  
       printf("n ni kiriting\nn= ");  scanf("%d",&n);
       printf("m ni kiriting\nm= ");  scanf("%d",&m);
       
  			a=1;
  			b=2;
  			
  for(i=1; i<=n; i++){
        s=0;
    if(i%2!=0){
    for(j=1; j<m; j++){

         printf("%d + ",a);
         s+=a;
         a+=2;
        } 
		
		s+=a;

    printf("%d = %d\n",a,s);
         
		 a+=2;
    }
    else{
    	
    for(j=1; j<m; j++){

        printf("%d + ",b);
        
        s+=b;
        b+=2;
        
        } s+=b;

    printf("%d = %d\n",b,s);
    
    b+=2;
    } 
  }
 }
 //Darsdagi masalalar funksiyasi
	void salom(int a,int b){
		printf("a= %d\n",a);
		printf("a= %d\n",b);
	}
	int sum(int a,int b){
		int c=a+b;
		return c;
	}
	int n_sum(int n){
		int i,s=0;
		for (i=1; i<=n; i++){
			s+=i;
		}
		return s;	
	}
		void aniqlash(int a){
		
		if(a%2==0){
		printf("Juft");
		}
		else{
			printf("Toq");
		} 	
		
	}
	void tub(int a,int i ){
	
	printf("a = %d",a);

	for (i=2; i<a; i++){
	
	
	if(a%i==0){
		
	printf ("\nTub emas ");
		i=a;
	}
		else {	
	printf("\nTub");
	i=a;
    }

}

}

bool tub_son(int n){
	int i=2;
	while (i<n){
		if(n%i==0){
			break;
		}
		i++;
	}
	if(i>=n){
		return 1;
	}
	else return 0;
	
}
#include<stdio.h>
#include<stdbool.h>
#include<stdlib.h>
#include<math.h>
#include<time.h>

// Massiv elementlarini random orqali qiymat berish va chop etish funksiyasi

void  mas_ran(int A[],int n ){
	srand(time(NULL));
	int i=0;
	for (i=0; i<n; i++){
		A[i]=rand()%(100)-50;
	}
}

void mas_out(int A[],int n){
	int i=0;
	for (i=0;i<n; i++){
		printf("%d   ",A[i]);
	}
	
}

// Massiv elementlarini toqlarini aniqlovchi funksiya

void  mas_toq(int A[],int n ){
	srand(time(NULL));
	int i=0;
	for (i=0; i<n; i++){
		A[i]=rand()%(100)-50;
		if (A[i]%2!=0){
			printf("%d   ",A[i]);
		}
	}
}
// Massivni toq elementlari sonini va  yig'indisini aniqlovchi va chop etuvchi funksiya

void  mas_toq_ys(int A[],int n ){
	srand(time(NULL));
	int i=0,s=0,t=0;
	for (i=0; i<n; i++){
		A[i]=rand()%(100)-50;
		if (A[i]%2!=0){
			s+=1;
			t+=A[i];
		}
	}
	
		printf("\nMassivni toq elementlar soni : %d ta ",s);
		printf("\nMassivni toq elementlar yig'indisi : %d ta ",t);
}

// Massiv elementlarini toqlarini aniqlovchi funksiya

void  mas_juft(int A[],int n ){
	srand(time(NULL));
	int i=0;
	for (i=0; i<n; i++){
		A[i]=rand()%(100)-50;
		if (A[i]%2==0){
			printf("%d   ",A[i]);
		}
	}
}
// Massivni juft  elementlari sonini va  yig'indisini aniqlovchi va chop etuvchi funksiya

void  mas_juft_ys(int A[],int n ){
	srand(time(NULL));
	int i=0,s=0,t=0;
	for (i=0; i<n; i++){
		A[i]=rand()%(100)-50;
		if (A[i]%2==0){
			s+=1;
			t+=A[i];
		}
	}
	
		printf("\nMassivni juft elementlar soni : %d ta ",s);
		printf("\nMassivni juft elementlar yig'indisi : %d ta ",t);
}


// Massivni manfiy elementlarini  aniqlovchi funksiya

void  mas_manfiy(int A[],int n ){
	srand(time(NULL));
	int i=0;
	for (i=0; i<n; i++){
		A[i]=rand()%(100)-50;
		if (A[i]<0){
			printf("%d   ",A[i]);
		}
	}
}

// Massivni manfiy  elementlari sonini va  yig'indisini aniqlovchi va chop etuvchi funksiya

void  mas_manfiy_ys(int A[],int n ){
	srand(time(NULL));
	int i=0,s=0,t=0;
	for (i=0; i<n; i++){
		A[i]=rand()%(100)-50;
		if (A[i]<0){
			s+=1;
			t+=A[i];
		}
	}
	
		printf("\nMassivni manfiy elementlar soni : %d ta ",s);
		printf("\nMassivni manfiy elementlar yig'indisi : %d ta ",t);
}

// Massivni musbat elementlarini  aniqlovchi funksiya

void  mas_musbat(int A[],int n ){
	srand(time(NULL));
	int i=0;
	for (i=0; i<n; i++){
		A[i]=rand()%(100)-50;
		if (A[i]>0){
			printf("%d   ",A[i]);
		}
	}
}

// Massivni musbat  elementlari sonini va  yig'indisini aniqlovchi va chop etuvchi funksiya

void  mas_musbat_ys(int A[],int n ){
	srand(time(NULL));
	int i=0,s=0,t=0;
	for (i=0; i<n; i++){
		A[i]=rand()%(100)-50;
		if (A[i]>0){
			s+=1;
			t+=A[i];
		}
	}
	
		printf("\nMassivni musbat elementlar soni : %d ta ",s);
		printf("\nMassivni musbat elementlar yig'indisi : %d ta ",t);
}

// Massivni tub  elementlarini chop etuvchi funksiya

bool n_tub(int n){

	if(n%2==0) return false;
	if(n==2) return true;
	
	int i;
	for(i=3;i<=sqrt(n); i+=1){
		if(n%i==0){
			return false;
		}
	}
	return true;
}
void  mas_tub(int A[],int n){
	int i=0;
	for (i=0;i<n; i++){
		if(n_tub(A[i])){
		printf("%d   ",A[i]);
	
		}
	}	
}

// Massivni  tub elementlari sonini va  yig'indisini aniqlovchi va chop etuvchi funksiya

void  mas_tub_ys(int A[],int n){
	int i=0,s=0,t=0;
	for (i=0;i<n; i++){
		if(n_tub(A[i])){
		s+=1;
		t+=A[i];
		}
	}
	printf("\nMassivni tub elementlar soni: %d",s);
	printf("\nMassivni tub elementlar yig'indisi: %d",t);	
}

//Massiv elementlari haqida ma'lumot beruvchi funksiya

	void massiv_malumot(int A[],int n){

				printf("Massiv elementlari: ");
		mas_ran(A,n);
		mas_out(A,n);
				printf("\n\nMassivni toq elementlari: ");
		mas_toq(A,n);
		mas_toq_ys(A,n);
				printf("\n\nMassivni juft elementlari: ");
		mas_juft(A,n);
		mas_juft_ys(A,n);
				printf("\n\nMassivni manfiy elementlari: ");
		mas_manfiy(A,n);
		mas_manfiy_ys(A,n);
				printf("\n\nMassivni musbat elementlari: ");
		mas_musbat(A,n);
		mas_musbat_ys(A,n);
				printf("\n\nMassivni tub elementlari: ");
		mas_tub(A,n);
		mas_tub_ys(A,n);
	}


 
