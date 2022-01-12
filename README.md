# Ninjas-Pattern


Pattern 1====>

#include <iostream>

using namespace std;

int main()
{
    //Write a code to print a square box of side 4 which is filled with astericks
/*    int n;
    cout<<"What shall be the side length of the square?"<<endl;
    cin>>n;
    int i=1;
    while(i<=n){
        int j=1;
        while(j<=n){
            cout<<"*";
            j++;
        }
        cout<<endl;
        i++;

    }    */

    //Write the above pattern but now the digit 1 2 3 4 shall be in the respective rows
/*     int n;
    cout<<"What shall be the side length of the square?"<<endl;
    cin>>n;
    int i=1;
    while(i<=n){
        int j=1;
        while(j<=n){
            cout<<i;
            j++;
        }
        cout<<endl;
        i++;
    }       */

    //Write the above pattern but now the numbers should be in ap of common difference 1 starting from the first term 1
/*     int n;
    cout<<"What shall be the side length of the square?"<<endl;
    cin>>n;
    int i=1;
    int val=1;
    while(i<=n){
        int j=1;
        while(j<=n){
            cout<<val;
            val++;
            j++;
        }
        cout<<endl;
        i++;
    }       */

    //Write the above pattern with 1234 in every row

/*    int n;
    cout<<"What shall be the side length of the square?"<<endl;
    cin>>n;
    int i=1;
    while(i<=n){
        int j=1;
        while(j<=n){
            cout<<j;
            j++;
        }
        cout<<endl;
        i++;
    }               */

    //Write the above pattern but every row should have 4321 in it
 /*     int n;
    cout<<"What shall be the side length of the square?"<<endl;
    cin>>n;
    int i=1;
    while(i<=n){
        int j=4;
        while(j>=1){
            cout<<j;
            j--;
        }
        cout<<endl;
        i++;
    }                   */

    //Write a program to generate a left triangular pattern where in every row count starts from 1
/*      int n;
    cout<<"What shall be the number of stairs in triangle?"<<endl;
    cin>>n;
    int i=1;
    while(i<=n){
        int j=1;
        while(j<=i){
            cout<<j;
            j++;
        }
        cout<<endl;
        i++;
    }           */

    //Print the following given pattern writing a cpp program
  //  1
  //  23
   // 456
   // 78910
/*     int n;
    cout<<"What shall be the number of stairs in triangle?"<<endl;
    cin>>n;
    int i=1;
    int val=1;
    while(i<=n){
        int j=1;
        while(j<=i){
            cout<<val;
            val++;
            j++;
        }
        cout<<endl;
        i++;
    }               */
    //Print the following patten by writing a cpp program for it:
   // 1
   // 23
   // 345
   // 4567
 /*    int n;
    cout<<"What shall be the number of stairs in triangle?"<<endl;
    cin>>n;
    int i=1;
    while(i<=n){
        int j=1;
        while(j<=i){
            cout<<i+j-1;
            j++;
        }
        cout<<endl;
        i++;
    }           */


    //Write the following pattern using cpp program
    //ABCD
    //ABCD
    //ABCD
    //ABCD
/*    int n;
    cout<<"What shall be the number of stairs in triangle?"<<endl;
    cin>>n;
    int i=1;
    while(i<=n){
        int j= 1;
        while(j<=n){
            cout<<char('A' + j -1);
            j++;
        }
        cout<<endl;
        i++;
    }           */

    //Write the following pattern using cpp program
    //ABCD
    //BCDE
    //CDEF
    //DEFG
/*    int n;
    cout<<"What shall be the number of stairs in triangle?"<<endl;
    cin>>n;
    int i=1;
    while(i<=n){
        int j=1;
        while(j<=n){
            cout<<char('A' +i+j-2);
            j++;
        }
        cout<<endl;
        i++;
    }           */


    //Write a cpp program to print the following pattern
   // A
   // BB
   // CCC
   // DDDD
/*   int n;
    cout<<"What shall be the number of stairs in triangle?"<<endl;
    cin>>n;
    int i=1;
    while(i<=n){
        int j=1;
        while(j<=i){
            cout<<char('A' + i-1);
            j++;
        }
        cout<<endl;
        i++;
    }               */

    //Write the cpp program to print the following pattern:
    //E
    //DE
    //CDE
    //BCDE
    //ABCDE
    int n;
    cout<<"What shall be the number of stairs in triangle?"<<endl;
    cin>>n;
    int i=n;
    while(i>=1){
        int j=i;
        while(j<=n){
            cout<<char('A' + j-1);
            j++;
        }
        cout<<endl;
        i--;}
  
                   return 0;
}

      
                   
                   
                   
                   
                   Pattern-2 =====>
  
  #include <iostream>

using namespace std;

int main()
{
    //Write a cpp program to print the mirror image of star (*) stairs
/*    int n;
    cout<<"Tell the number of stairs in your triangle"<<endl;
    cin>>n;
    int i=1;
    //Ith row==> (n-i) spaces
    while(i<=n){
        int k=1;
        while(k<=(n-i)){
            cout<<" ";
            k++;
        }
        int j=1;
        while(j<=i){
            cout<<"*";
            j++;
        }
        cout<<endl;
        i++;
    }               */



    //In the above pattern consider numbers in place of * and each row starting from 1
/*     int n;
    cout<<"Tell the number of stairs in your triangle"<<endl;
    cin>>n;
    int i=1;
    //Ith row==> (n-i) spaces
    while(i<=n){
        int k=1;
        while(k<=(n-i)){
            cout<<" ";
            k++;
        }
        int j=1;
        while(j<=i){
            cout<<j;
            j++;
        }
        cout<<endl;
        i++;
    }           */

    //Write a program to generate an inverted triangle (orientation==> normal) containing *
/*     int n;
    cout<<"Tell the number of stairs in your triangle"<<endl;
    cin>>n;
    int i=1;
    //Ith row==> (n-i) spaces
    while(i<=n){
        int j=1;
        while(j<=n-i+1){
            cout<<"*";
            j++;
        }
        cout<<endl;
        i++;
    }               */

    //In the above pattern only replace * with respective row number
/*    int n;
    cout<<"Tell the number of stairs in your triangle"<<endl;
    cin>>n;
    int i=1;
    //Ith row==> (n-i) spaces
    while(i<=n){
        int j=1;
        while(j<=n-i+1){
            cout<<i;
            j++;
        }
        cout<<endl;
        i++;
    }       */

    //Write a code for isosceles triangle
 /*    int n;
    cout<<"Tell the number of stairs in your triangle"<<endl;
    cin>>n;
    int i=1;
    //Ith row==> (n-i) spaces
    while(i<=n){
        int k=1;
        while(k<=(n-i)){
            cout<<" ";
            k++;
        }
        int j=1;
        while(j<=i){
            cout<<j;
            j++;
        }
        int m=i-1;
        while(m>=1){        //Condition: This loop will only run till/when j>=1
            cout<<m;
            m--;
        }

        cout<<endl;
        i++;
    }               */

    //Write a program for isosceles triangle filled with star *
 /*     int n;
    cout<<"Tell the number of stairs in your triangle"<<endl;
    cin>>n;
    int i=1;
    //Ith row==> (n-i) spaces
    while(i<=n){
        int k=1;
        while(k<=(n-i)){
            cout<<" ";
            k++;
        }
        int j=1;
        while(j<=i){
            cout<<"*";
            j++;
        }
        int m=i-1;
        while(m>=1){        //Condition: This loop will only run till/when j>=1
            cout<<"*";
            m--;
        }

        cout<<endl;
        i++;
    }       */

    //Write a program now for a diamond filled with stars *
     int n;
    cout<<"Tell the number of stairs in your triangle"<<endl;
    cin>>n;
    int i=1;
    //Ith row==> (n-i) spaces
    while(i<=n){
        int k=1;
        while(k<=(n-i)){
            cout<<" ";
            k++;
        }
        int j=1;
        while(j<=i){
            cout<<"*";
            j++;
        }
        int m=i-1;
        while(m>=1){        //Condition: This loop will only run till/when j>=1
            cout<<"*";
            m--;
        }

        cout<<endl;
        int k=0;
        while(k>=(n-i)){
            cout<<" ";
            k++;
        }


        i++;

    }








    return 0;
}

                   
                   
                   
           
