#include <iostream>
using namespace std;

void findDuplicate(int nums[],int n){
        for(int i=0;i<5;i++){
      
            for(int j=i+1;j<5;j++){
               
                if(nums[j]==nums[i]){
                    cout<<"The duplicate element is: ";
                    cout<<nums[j];
                    break;
                }
            }
            cout<<endl;
    }
}

int main(){
    int n;
    cout<<"Enter the number of elements "<<endl;
    cin>>n;
    int nums[n];
    cout<<"Enter the elements "<<endl;
    for(int i=0;i<n;i++){
        cin>>nums[i];
    }
    findDuplicate(nums,n);
    return 0;
}
