    #include <stdio.h> 
    #include <stdlib.h>

    int main() {
    
    int cap;
    float hacim;
    float pi= 3.1419;

    printf("Capi giriniz(cm): ");
    scanf("%d", &cap);

    int yaricap= (cap/2);

    printf("Girdi degerleri: yaricap %d\n", yaricap);

    hacim= ((4*pi)/3)*yaricap*yaricap*yaricap;

    printf("Kurenin hacmi: %f cm kuptur.", hacim);

    return 0; }
