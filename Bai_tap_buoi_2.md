
## 1. So sánh 3 số

Nhập 3 số nguyên a, b, c. In ra số lớn nhất và số nhỏ nhất.  

**Gợi ý:** Sử dụng biến max, min và các câu lệnh if để so sánh từng cặp số.

**Input:**
```

5 2 9

```
**Output:**
```

max=9 min=2

```

---


## 2. Phân loại tam giác

Nhập 3 cạnh dương a, b, c. Kiểm tra có lập thành tam giác không, nếu có hãy phân loại.  

**Gợi ý:** Kiểm tra điều kiện tam giác (tổng 2 cạnh lớn hơn cạnh còn lại)

**Input:**
```

3 4 5

```
**Output:**
```

RIGHT

```

---



## 3. Vẽ hình chữ nhật 

Nhập số n tương ứng với cạnh dài của hình chữ nhật

**Gợi ý:** Sử dụng vòng lặp for để in từng dòng. Dòng đầu và cuối in toàn dấu *, các dòng giữa in * ở hai đầu.

**Input:**
```

5

```
**Output:**
```

***
* *
* *
* *
* *
***

```

---



## 4. Vẽ hình chữ nhật ngang

Nhập số n tương ứng với cạnh dài của hình chữ nhật

**Gợi ý:** Dùng vòng lặp for để in dòng đầu và cuối toàn dấu *. Dòng giữa in * ở hai đầu, giữa là khoảng trắng.

**Input:**
```

10

```
**Output:**
```

**********
*        *
**********

```

---


## 5. Bảng cửu chương của N

Nhập số nguyên N, in ra bảng cửu chương từ 1 đến 10.  

**Gợi ý:** Dùng vòng lặp for từ 1 đến 10, mỗi lần in N nhân với chỉ số vòng lặp.

**Input:**
```

5

```
**Output:**
```

5 x 1 = 5
5 x 2 = 10
5 x 3 = 15
5 x 4 = 20
5 x 5 = 25
5 x 6 = 30
5 x 7 = 35
5 x 8 = 40
5 x 9 = 45
5 x 10 = 50

```

---



## 6. Tính tổng dãy số

Nhập vào một số nguyên n, tính tổng dãy số từ 1 đến n

**Gợi ý:** Dùng biến sum, vòng lặp for hoặc while để cộng dồn từ 1 đến n.

**Input:**
```

5

```
**Output:**
```

15
(Giải thích: 1+2+3+4+5=15)

```

---



## 7. Tổng chữ số

Nhập một số nguyên N, tính tổng các chữ số của N.  

**Gợi ý:** Dùng vòng lặp while, mỗi lần lấy chữ số cuối (N % 10), cộng vào tổng, sau đó chia N cho 10.

**Input:**
```

12345

```
**Output:**
```

sum=15

```

---



## 8. Giải phương trình bậc 2

Giải phương trình: ax² + bx + c = 0.  

**Gợi ý:** Tính delta = b*b - 4*a*c. Nếu delta < 0 thì vô nghiệm, delta = 0 thì nghiệm kép, delta > 0 thì có 2 nghiệm phân biệt.

**Input:**
```

1 -3 2

```
**Output:**
```

x1=1.0 x2=2.0

```

---





## 9. Đảo ngược số

Nhập một số nguyên N, in ra số đảo ngược của N.  

**Gợi ý:** Dùng vòng lặp while, mỗi lần lấy chữ số cuối (N % 10), in ra hoặc ghép vào số mới, sau đó chia N cho 10.

**Input:**
```

1234

```
**Output:**
```

4321

```

---



## 10. Ước số & số nguyên tố

Nhập số nguyên dương N. Đếm số lượng ước và kiểm tra nguyên tố.  

**Gợi ý:** Dùng vòng lặp for để đếm số ước của N. Nếu số ước là 2 thì N là số nguyên tố.

**Input:**
```

7

```
**Output:**
```

div\_count=2
PRIME

```

---

## 11. UCLN & BCNN

Nhập hai số nguyên a, b. Tính UCLN và BCNN.  

**Gợi ý:** Dùng thuật toán Euclid để tìm UCLN (gcd), sau đó BCNN = (a*b)/UCLN.

**Input:**
```

12 18

```
**Output:**
```

gcd=6 lcm=36

```

---

