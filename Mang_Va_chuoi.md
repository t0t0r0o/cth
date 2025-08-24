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
