#include <stdio.h>
#include <string.h>
int main(){
    char text[500];
    printf("Enter the text: ");
    scanf("%s", text);
    int key;
    printf("Enter the key: ");
    scanf("%d", &key);
    for(int i=0;i<=strlen(text);i++){
        if(key>=0){
            printf("%c", text[i]+key);
        }
        else{
            printf("%c", text[i]-key);
        }
    }
    return 0;
}
