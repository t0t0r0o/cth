# Mảng trong C

- Định nghĩa: Mảng trong C là tập hợp của các biến có cùng kiểu dữ liệu



- Khai báo mảng trong C: <Kiểu dữ liệu>  <Tên mảng>[Số lượng phần tử tối đa của mảng] = {các phần tử trong mảng}

VD:

```c

// Khai báo mảng tĩnh
int a[4];
int a[4] = {5,2,7,4};  



//Khai báo mảng động

int n;
printf("Nhap vao so luong phan tu: ");
scanf("%d",&n);


for(int i = 0;i<n;i++ ) {

    printf("Nhap vao gia tri cua a[%d]", i);
    scanf("%d",a[i]);
}


for(int i = 0;i<n;i++ ) {
    printf(" gia tri cua a[%d] la: %d\n",i, a[i]);
}



```


# Thao thác trên mảng

- Nhập giá trị cho mảng

VD: nhập vào các giá trị của mảng


```c


int a[10];

for(int i = 0;i<10;i++ ) {

    printf("Nhap vao gia tri cua a[%d]", i);
    scanf("%d",a[i]);
}

```

- Duyệt mảng

```c


int a[4]={5,6,2,1};

for(int i = 0;i<4;i++ ) {
    printf(" gia tri cua a[%d] la: %d\n",i, a[i]);
}

```

- Thay đổi giá trị của mảng
VD: thay đổi biến a[2] = 5;

```c

int a[4]={5,6,4,1};


//cách 1
a[2] =5;


// cách 2

for(int i = 0;i<4;i++ ) {
    
    if (i == 2) {
        a[i] = 5;
    }

}



```



# Chuỗi trong C



- Định nghĩa chuỗi: tập hợp các biến có kiểu dữ liệu là char.
- Note : Khi thao tác với chuỗi, nhớ khai báo: #include <string.h>

- Khai báo chuỗi:

```c

//cách 1
char c[] ='abcde';


//khai báo chuỗi 
char c[] = {'a','b','c','d'};

```


# Thao thác trên chuỗi

- Nhập chuỗi 

```c


// Cách 1
#include <stdio.h>
#include <string.h>

int main(){
    char c[1000];
    printf("Nhap xau ky tu : ");
    scanf("%s", c); // &c cũng được
    printf("Xau ky tu vua nhap : %s\n", c);
    return 0;
}



// Cách 2 dùng hàm gets


#include <stdio.h>
#include <string.h>

int main(){
    char c[1000];
    printf("Nhap xau ky tu : ");
    gets(c);
    printf("Xau ky tu vua nhap : %s\n", c);
    return 0;
}



```



- Thao tác duyệt chuỗi

```c

#include <stdio.h>
#include <string.h>

int main(){

    //hàm strlen() là hàm lấy ra độ dài của chuỗi

    char c[] = "abcskskdffskjafjdflajdlfajdjalsdfa";
    printf("Do dai cua chuoi la : %d\n", strlen(c));

    for(int i = 0; i < strlen(c); i++){
        printf("c[%d] = %c\n", i, c[i]);
    }

    return 0;
}



```