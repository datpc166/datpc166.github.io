---
title: Sắp xếp chọn - Selection Sort
layout: post
summary: Thuật toán sắp xếp chọn là thuật toán dựa trên việc so sánh tại chỗ, sắp xếp bằng cách liên tục tìm phần tử nhỏ nhất (giả sử sắp xếp tăng dần) từ phần chưa được sắp xếp và đẩy chúng lên đầu.
author: dylan
color: "background-color: firebrick"
date: '2022-02-23 20:35:23 +07:00'
category: ['study','algorithms']
type: "Blog học thuật"
thumbnail: "/assets/img/posts/2022-02-23-selection-sort/thumbnail.png"
keywords: sorting, searching, algorithms, selection sort
usemathjax: true
permalink: "/blog/selection-sort/"
---

Hôm nay chúng ta sẽ nghiên cứu về **Selection Sort Algorithm**. Đây là thuật toán đầu tiên trong series [Cấu trúc dữ liệu và Giải thuật](/blog/categories/algorithms/), nó thuộc trong các thuật toán sắp xếp và tìm kiếm. Bài viết này sẽ giúp các bạn hiểu được giải thuật và cách triển khai code như thế nào nhé :D

# **Nội dung bài viết:**
1. [Sắp xếp chọn là gì?](#sắp-xếp-chọn-là-gì)
2. [Ý tưởng thuật toán sắp xếp chọn](#ý-tưởng-thuật-toán-sắp-xếp-chọn)
3. [Ví dụ minh hoạ](#ví-dụ-minh-hoạ)
4. [Mã giả (Psuedo Code)](#mã-giả-psuedo-code)
5. [Cài đặt thuật toán](#cài-đặt-thuật-toán)
6. [Đánh giá thuật toán sắp xếp chọn](#đánh-giá-thuật-toán-sắp-xếp-chọn)

## **Sắp xếp chọn là gì?**
**_Thuật toán sắp xếp chọn_** là thuật toán dựa trên việc **so sánh tại chỗ**, sắp xếp bằng cách liên tục tìm phần tử nhỏ nhất (giả sử sắp xếp tăng dần) từ phần chưa được sắp xếp và đẩy chúng lên đầu. Thuật toán sẽ chia mảng thành 2 mảng con, trong đó:
* Phần được sắp xếp ở bên trái
* Phần chưa được sắp xếp ở bên phải
<br/>

**_Thuật toán sắp xếp chọn_** sẽ chọn phần tử nhỏ nhất từ **Phần chưa được sắp xếp** và đẩy vào **Phần được sắp xếp**

## **Ý tưởng thuật toán sắp xếp chọn**

{% include gif-responsive.html link='https://s9.gifyu.com/images/selection_sort.gif' %}

#### Giả sử, ta có mảng **a[n]**{: style="color: #ff6200"} có **n**{: style="color: #ff6200"} phần tử, mảng chưa được sắp xếp.
 _**Lưu ý**: Trong bài viết này mình minh hoạ thuật toán sắp xếp tăng dần, trong trường hợp giảm dần thì tương tự._{: style="color: #7f838a"}

- *Bước 1*: Đặt **min**{: style="color: #ff6200"} là chỉ số của phần tử `a[0]`{: style="color: #ff6200"} đem ra xem xét.
- *Bước 2*: Tìm kiếm phần tử `a[j]`{: style="color: #ff6200"} từ phần tử _kế tiếp_ đến phần tử cuối cùng `a[n-1]`{: style="color: #ff6200"}, nếu tìm thấy phần tử `a[j]`{: style="color: #ff6200"} nhỏ hơn `a[min]`{: style="color: #ff6200"} đang xét thì gán **min**{: style="color: #ff6200"} = `j`{: style="color: #ff6200"}.
- *Bước 3*: Đổi chỗ 2 phần tử `a[min]`{: style="color: #ff6200"} và `a[i]`{: style="color: #ff6200"} (chú ý `i`{: style="color: #ff6200"} là chỉ số ban đầu đem ra xem xét trước khi đem so sánh giá trị với các phần tử phía sau, trong vòng lặp 1: `i`{: style="color: #ff6200"} = 0 ,...).
- *Bước 4*: Gán **min**{: style="color: #ff6200"} bằng chỉ số của phần tử kế tiếp để tiếp tục xem xét.
- *Bước 5*: Lặp lại từ _`Bước 2`_ cho đến khi mảng `a`{: style="color: #ff6200"} được sắp xếp hoàn toàn.

_**Note**: Thuật toán thực hiện `n - 1` vòng lặp_.


## **Ví dụ minh hoạ**

Cho mảng *a[] = {12, 45, 22, 8, 30}* cần được sắp xếp *tăng dần*
>
> **`Bước 1`**: Đặt **min**{: style="color: #ff6200"} = `0`(chỉ số của phần tử `12`{: style="color: #e3471b"}).
>
|:-|-|-|-|-:|   
|`[12]`{: style="color: #db1818"}|45|22|8|30|

> **`Bước 2`**: Duyệt các phần tử a[i] = a[1...4], tìm kiếm phần tử nhỏ hơn `a[min]`{: style="color: #ff6200"}
>
|:-|-|-|-|-:|   
|`[12]`{: style="color: #db1818"}|`[45]`{: style="color: green"}|22|8|30|
>
|:-|-|-|-|-:|   
|`[12]`{: style="color: #db1818"}|45|`[22]`{: style="color: green"}|8|30|
>
|:-|-|-|-|-:|   
|`[12]`{: style="color: #db1818"}|45|22|`[8]`{: style="color: #db1818"}|30|
>
> Đến đây ta tìm thấy `[8]`{: style="color: #db1818"} nhỏ hơn `a[min]`{: style="color: #ff6200"}, lúc này ta gán **min**{: style="color: #ff6200"} = `3` (chỉ số của `8`{: style="color: #ff6200"})
>
|:-|-|-|-|-:|   
|`[12]`{: style="color: #db1818"}|45|22|`[8]`{: style="color: #db1818"}|`[30]`{: style="color: green"}|

> **`Bước 3`**: Ta đổi chỗ `[8]`{: style="color: #db1818"} và `[12]`{: style="color: #db1818"}.
>
|:-|-|-|-|-:|   
|`[8]`{: style="color: #db1818"}|45|22|`[12]`{: style="color: #db1818"}|30|

> **`Bước 4`**: Ta gán chỉ số của phần tử tiếp theo `a[1] = 45`{: style="color: #ff6200"} cho **min**{: style="color: #ff6200"}.
>
|:-|-|-|-|-:|   
|8|`[45]`{: style="color: #db1818"}|22|12|30|

> **`Bước 5`**: Lặp lại liên tục từ **`Bước 2`** cho đến khi mảng được sắp xếp hoàn toàn (khi **min**{: style="color: #ff6200"} = `n - 1`).
 

## **Mã giả (Psuedo Code)**

```bash
for i = 1 to A.length - 1
	min_index = i
	// Tìm số nhỏ nhất trong dãy con A[i + 1 ... n].
	for j = i + 1 to A.length
		if A[j] < A[min_index]
			min_index = j
	// Hoán đổi vị trí của giá trị nhỏ nhất và giá trị hiện tại của mảng chưa sắp xếp.
	key = A[i]
	A[i] = A[min_index]
	A[min_index] = key
```

## **Cài đặt thuật toán**

```cpp
// Code by Nguyen Quoc Dat

#include "bits/stdc++.h"
using namespace std;
#define fastIO 	ios_base::sync_with_stdio(0); cin.tie(0); 

void swap(int &a, int &b){
	int tmp = a;
	a = b;
	b = tmp;
}

void selection_sort(int arr[], int n){
	for(int i=0; i < n-1; i++){
		int min = i; /*gán min cho chỉ số của phần tử đang xét*/
		for(int j=i+1; j<n; j++){ 
			/*thực hiện tìm kiếm phần tử a[j] nhỏ hơn a[min]*/
			if(arr[j] < arr[min]){ 
				min = j; 
			}
		}
		swap(arr[i], arr[min]);/*đổi chỗ a[min] với phần tử ban đầu đem ra xét.*/
	}
}

void print(int arr[], int n){ //in ra màn hình
	for(int i = 0; i < n; i++){
		cout<<arr[i]<<" ";	
	}
	cout<<"\n";
}

int main(){
	fastIO;
	int arr[] = {12,45,22,8,30};
	int n = sizeof(arr)/sizeof(arr[0]);
	//Before Sorting
	cout<<"Before Sorting:\n";
	print(arr,n);

	selection_sort(arr,n);
	// After Sorting
	cout<<"After Sorting:\n";
	print(arr,n);
	return 0;
}
```
#### Output:
```
Before Sorting:
12 45 22 8 30
After Sorting: 
8 12 22 30 45
```
## **Đánh giá thuật toán sắp xếp chọn**

**Selection Sort** không khó để phân tích so với các thuật toán sắp xếp khác, cũng bởi không có vòng lặp nào phụ thuộc vào dữ liệu trong mảng. Việc chọn phần tử nhỏ nhất cần duyệt **n** phần tử (tức **`n - 1`** lần so sánh) sau đó đổi chỗ với phần tử đầu tiên đang xem xét. Tìm kiếm các phần tử nhỏ nhất tiếp theo yêu cầu duyệt **`n-1`** phần tử , ... Vì vậy, tổng số lần cần so sánh là: 

$$ (n - 1) + (n - 2) +...+ 1 = \sum_{i=1}^{n-1} i $$

Theo Cấp Số Cộng: 

$$ \sum_{i=1}^{n-1} i = \frac{(n-1) + 1}{2}(n-1) = \frac{1}{2}n(n - 1) = \frac{1}{2}(n^2 - n) $$

Vì vậy, độ phức tạp của thuật toán Selection Sort là $ O(n^2) $ về số lượng phép so sánh. Mỗi lần duyệt yêu cầu hoán đổi cho `n - 1` phần tử (phần tử cuối đã đứng đúng chỗ mà nó thuộc về). 

## **Bonus**
 _Xem thêm video minh hoạ cho ngấm nha các bạn:D_

{% include video-responsive.html link='https://www.youtube.com/embed/xWBP4lzkoyM' %}
<figcaption style="text-align: center; padding: 10px"><i>Nguồn tham khảo Geeksforgeeks</i></figcaption>
<br/>

Nếu có bất kỳ thắc mắc nào, hãy để bình luận phía dưới để cùng nhau trao đổi nhé.




