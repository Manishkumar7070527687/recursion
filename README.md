// recursion
int fibonacci(int n){                          /*fibonacci */
    if(n==0 || n==1){
        return n;

    }
    return fibonacci(n-1) + (n-2);
}
int main (){
    int n;
    printf("Enter a number: ");
    scanf("%d",&n);

    printf("Thr value of %d at fibonacci series is %d\n",n,fibonacci(n));
    return 0;
}
