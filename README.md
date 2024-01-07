#include<iostream>
using namespace std;

//int p_non_p(int n,int i){
//	if(n==0){
//	cout<<"\"0 is neither prime nor non-prime number\"";
//	return 0;}
//	
//	if(i>=n){
//	cout<<"\""<<n<<" is a prime number\"\n";
//	return 0;}
//	
//	if(n%i==0){
//		cout<<"\""<<n<<" is a non-prime number\"\n";
//		return 0;
//	}
//	
//	return p_non_p(n,i+1);
//}
//
////	------------------------end of p_non_p function ---------------------------
//
//int reverse_n(int n){
//	
//	if(n<9){
//	cout<<n;
//	return 0;}
//	
//	
//	int rem = n % 10;
//	cout<< rem;
//	
//	return reverse_n(n / 10);
//	
//}
//
////	------------------------end of reverse_(n)umber function ---------------------------	
//	
//int power(int n,int m,int o=1){
//	
//	if(m==0){
//	cout<<n<<" raised to the power "<<m<<" is: ";
//	return 1;}
//	
//	if(o==m){
//	cout<<n<<" raised to the power "<<m<<" is: ";
//	return n;}
//	
//	return n * power(n,m,o+1);
//}
//
////	------------------------end of power function ---------------------------	
//



//
//bool palindrome(char arr[],int n,int m){
//    
//    if(m>=n)
//    return true;
//    
//    if(arr[m]!=arr[n])
//    return false;
//    
//    return palindrome(arr,n-1,m+1);
//    
//}

//	------------------------end of palindrome function ---------------------------	

void print_sum(int arr[],int size){
	for(int i=0; i<size; i++){
		cout<<arr[i]<<" + ";
		if(i<size)
		cout<<arr[i];
	}
}

int sum_sum(int arr[],int size,int i = 0){
	
	if(i==size){
		return 0;
	}
	
	return arr[i] + sum_sum(arr,size,i+1);
}


//	------------------------M A I N  F U N C T I O N---------------------------


int main(){
	
	
	
//	cout<<"Please enter a number to check wether it is prime or non-prime: ";
//	int n;
//	cin>>n;
//	p_non_p(n,2);
//	
////	------------------------end of question no.1 ---------------------------
//	
//	cout<<"\n\n\"This program reverses the entered number\"\n";
//	cout<<"Please enter a number: ";
//	int m;
//	cin>>m;
//	reverse_n(m);
//	
////	------------------------end of question no.2 ---------------------------	
//
//	cout<<"\n\n\"This program evaluates the base to the exponential power of a given number\"";
//    cout<<"\nPlease enter a base: ";
//    int o,p;
//    cin>>o;
//    cout<<"Please enter an exponent: ";
//    cin>>p;
//    cout<< power(o,p);
    
////	------------------------end of question no.3 ---------------------------	    
    
    cout<<"\n\n\"This program sorts the entered marks of ten students using pointers\"\nNOTE: each student has 10 scores, each out of 20\n";
    cout<<"\nenter the scores of 10 students respectively:\n";
    int arr[10][10];
    for(int i=0; i<10; i++){
    	for(int j=0; j<10; j++){
    		cout<<"Enter student #"<<i+1<<"'s score #"<<j+1<<": ";
    		cin>>arr[i][j];
		}
	}
	
	for(int i=0; i<10; i++){
    	for(int j=0; j<10; j++){
    		cout<<arr[i][j]<<" ";
    		
		}
		cout<<endl;
	}
    
//	------------------------end of question no.4 ---------------------------	    
    
    
//	------------------------end of question no.3 ---------------------------    
//	cout<<"\n\n\"This program checks if the entered word is a palindrome or not \"";
//	cout<<"\nPlease enter the length of the word you need to enter: ";
//	int size,sz = 0,result = 0 ;
//	cin>>size;
//	char arr[size+1];
//	
//	cout<<"\nEnter the word: ";
//	for(int i=0; i<size; i++){
//	    cin>>arr[i];
//	}
//	
//	if(palindrome(arr,size-1,sz)){
//		cout<<arr<<" is a palindrome";
//	}else{
//		cout<<arr<<" is not a palindrome";
//	}	
	
//	------------------------end of question no.5 ---------------------------    	

//	cout<<"\n\n\"This program sums the numbers entered by the user\"";
//    cout<<"\nPlease enter how many numbers you need to enter: ";
//    int size;
//    cin>>size;
//	int sum[size];
//	
//	
//	for(int i=0; i<size; i++){
//    		cout<<"enter number#"<<i+1<<": ";
//    		cin>>sum[i];
//		}
//		
//	cout<<"the sum of the numbers(  ";
//	for(int j =0; j<size; j++){
//		cout<<sum[j]<<"  ";
//	}
//	
//	  cout<<") is: ";
//	cout<< sum_sum(sum,size);
	
//	------------------------end of question no.6 ---------------------------    		
}

