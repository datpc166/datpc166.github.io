---
title: Sắp xếp nổi bọt - Bubble Sort
layout: post
author: dylan
summary: Sắp xếp nổi bọt là một thuật toán sắp xếp đơn giản, với thao tác cơ bản là so sánh hai phần tử kề nhau, nếu chúng chưa đứng đúng thứ tự thì đổi chỗ. Có thể tiến hành từ trên xuống hoặc từ dưới lên.
color: "background-color: firebrick"
date: '2022-02-27 21:00:00 +07:00'
type: "Blog học thuật"
category: ['study','algorithms']
thumbnail: "/assets/img/posts/2022-02-27-bubble-sort/thumbnail.png"
keywords: sorting, searching, algorithms, bubble sort
usemathjax: true
permalink: "/blog/bubble-sort/"
---

Xin chào các bạn, hôm nay chúng ta tiếp tục nghiên cứu thuật toán sắp xếp tiếp theo, đó là **thuật toán Sắp Xếp Nổi Bọt (Bubble Sort)** trong series [Cấu trúc dữ liệu và Giải thuật](/blog/categories/algorithms/), chuyên đề [Các thuật toán sắp xếp và tìm kiếm](#).

# **Nội dung bài viết**

1. [Sắp xếp nổi bọt là gì?](#sắp-xếp-nổi-bọt-là-gì)
2. [Ý tưởng của thuật toán Bubble Sort](#ý-tưởng-của-thuật-toán-bubble-sort)
3. [Ví dụ minh hoạ](#ví-dụ-minh-hoạ)
4. [Mã giả (Pseudo Code)](#mã-giả-pseudo-code)
5. [Cài đặt thuật toán](#cài-đặt-thuật-toán)
6. [Đánh giá thuật toán sắp xếp nổi bọt](#đánh-giá-thuật-toán-sắp-xếp-nổi-bọt)


## **Sắp Xếp Nổi Bọt Là Gì**?

**Sắp xếp nổi bọt** (tiếng Anh: **Bubble Sort**) là một thuật toán sắp xếp đơn giản, với thao tác cơ bản là so sánh 2 phần tử *kề nhau*, nếu chưa đúng thứ tự thì đổi chỗ cho nhau (swap). Có thể tiến hành từ trên xuống (bên trái sang) hoặc từ dưới lên (bên phải sang). Nó sử dụng phép _so sánh_ các phần tử nên là một **giải thuật sắp xếp kiểu so sánh**

## **Ý tưởng của thuật toán Bubble Sort**

{% include gif-responsive.html link='https://s9.gifyu.com/images/bubble-sort.gif' %}

<figcaption style="text-align: center; padding: 10px"><i>Minh họa thuật toán sắp xếp bubble sort</i></figcaption>


Bắt đầu từ vị trí đầu tiên của danh sách (bên trái), so sánh các cặp số với nhau, nếu không đúng thứ tự nhỏ-lớn thì đảo vị trí. Sau khi chạy tới cuối danh sách, tiếp tục chạy lại từ vị trí đầu danh sách cho đến khi hoàn thành so sánh và đảo vị trí.

## **Ví dụ minh hoạ**

**Giả sử, chúng ta cần sắp xếp mảng A = [5, 1, 4, 2, 8, 9] tăng dần**


#### _**Vòng lặp 1**_

> Swap vì 5>1 
>
|:-|-|-|-|-|-:|   
|**5**{: style="color: red"}|**1**{: style="color: red"}|4|2|8|9|	
>
>|**1**{: style="color: green"}|**5**{: style="color: green"}|4|2|8|9|	

***
> Swap
>
|:-|-|-|-|-|-:|   
|1|**5**{: style="color: red"}|**4**{: style="color: red"}|2|8|9|	
>
>|1|**4**{: style="color: green"}|**5**{: style="color: green"}|2|8|9|

***
> Swap
> 
|:-|-|-|-|-|-:|    
|1|4|**5**{: style="color: red"}|**2**{: style="color: red"}|8|9|
>
>|1|4|**2**{: style="color: green"}|**5**{: style="color: green"}|8|9|

***
> No change vì chúng đã in right order (5<8)
> 
|:-|-|-|-|-|-:|     
|1|4|2|**5**{: style="color: red"}|**8**{: style="color: red"}|9|
>
>|1|4|2|**5**{: style="color: green"}|**8**{: style="color: green"}|9|

***
> No change 
>
|:-|-|-|-|-|-:|     
|1|4|2|5|**8**{: style="color: red"}|**9**{: style="color: red"}|
>
>|1|4|2|5|**8**{: style="color: green"}|**9**{: style="color: green"}|
>

#### _**Vòng lặp 2**_
> No change
> 
|:-|-|-|-|-|-:|    
|**1**{: style="color: red"}|**4**{: style="color: red"}|2|5|8|9|
>
>
>|**1**{: style="color: green"}|**4**{: style="color: green"}|2|5|8|9|
>

***
> Swap
>
|:-|-|-|-|-|-:|    
|1|**4**{: style="color: red"}|**2**{: style="color: red"}|2|8|9|
>
>|1|**2**{: style="color: green"}|**4**{: style="color: green"}|5|8|9|

***
> No change
> 
|:-|-|-|-|-|-:|    
|1|2|**4**{: style="color: red"}|**5**{: style="color: red"}|8|9|
>
>|1|2|**4**{: style="color: green"}|**5**{: style="color: green"}|8|9|

***
> No change
> 
|:-|-|-|-|-|-:|    
|1|2|4|**5**{: style="color: red"}|**8**{: style="color: red"}|9|	
>
>|1|2|4|**5**{: style="color: green"}|**8**{: style="color: green"}|9|

***
> No change 
>
|:-|-|-|-|-|-:|     
|1|2|4|5|**8**{: style="color: red"}|**9**{: style="color: red"}|
>
>|1|2|4|5|**8**{: style="color: green"}|**9**{: style="color: green"}|
>


#### _**Vòng lặp 3**_
> No change
>
|:-|-|-|-|-|-:|     
|**1**{: style="color: red"}|**4**{: style="color: red"}|2|5|8|9|
>
>|**1**{: style="color: green"}|**4**{: style="color: green"}|2|5|8|9|

***
> No change
>
|:-|-|-|-|-|-:|     
|1|**2**{: style="color: red"}|**4**{: style="color: red"}|5|8|9|
>
>|1|**2**{: style="color: green"}|**4**{: style="color: green"}|5|8|9|

***
> No change
> 
|:-|-|-|-|-|-:|    
|1|2|**4**{: style="color: red"}|**5**{: style="color: red"}|8|9|
>
>|1|2|**4**{: style="color: green"}|**5**{: style="color: green"}|8|9|


***
> No chagne
> 
|:-|-|-|-|-|-:|    
|1|2|4|**5**{: style="color: red"}|**8**{: style="color: red"}|9|
>
>|1|2|4|**5**{: style="color: green"}|**8**{: style="color: green"}|9|

***
> No change 
>
|:-|-|-|-|-|-:|     
|1|2|4|5|**8**{: style="color: red"}|**9**{: style="color: red"}|
>
>|1|2|4|5|**8**{: style="color: green"}|**9**{: style="color: green"}|
>

**Vòng lặp mà không swap lần nào thì tức là dãy đó đã đứng đúng thứ tự**
<br/>
**==> Ta thu được mảng đã được sắp xếp [1, 2, 4, 5, 8, 9]**


{% include video-responsive.html link='https://www.youtube.com/embed/nmhjrI-aW5o' %}
<figcaption style="text-align: center; padding: 10px"><i>Nguồn tham khảo: Geeksforgeeks</i></figcaption>

## **Mã giả (Pseudo Code)**

#### Sắp xếp từ trên xuống
```bash
procedure bubble_sort1(list L, number n) // n=listsize
  For number i from  n downto 2 
    for number j from 1 to (i - 1)
      if L[j] > L[j + 1] // nếu chúng không đúng thứ tự
        swap(L[j], L[j + 1]) //đổi chỗ chúng cho nhau
      endif
    endfor
   endfor
endprocedure
```
#### Sắp xếp từ dưới lên
```bash
procedure bubble_sort2(list L, number n) // n=listsize
  For number i from 1 to n-1 
    for number j from n-1 downto i
      if L[j] > L[j + 1] // nếu chúng không đúng thứ tự
        swap(L[j], L[j + 1]) //đổi chỗ chúng cho nhau
      endif
    endfor
   endfor
endprocedure
```


## **Cài đặt thuật toán**
> C++

```cpp 
// Code by Nguyen Quoc Dat

#include <iostream>
using namespace std;

void swap(int &a, int &b){
	int tmp = a;
	a = b; 
	b = tmp;
}

void bubble_sort(int arr[], int n){
	bool done;
	for(int i=0;i<n-1;i++){ // phần tử cuối cùng đã được sắp xếp
		done = false;
		for(int j=0; j<n-i-1; j++){
			if(arr[j] > arr[j+1]){ 
				// nếu phần tử đứng sau < phần tử đứng trước thì swap
				swap(arr[j], arr[j+1]);
				done = true; // kiểm tra xem vòng lặp này có swap không
			}
		}
		if(done == false){ 
			break;
			// Không thực hiện swap lần nào => dừng vòng lặp, mảng đã được sắp xếp
		}
	}
}

void print(int arr[], int n){
	for(int i=0;i<n;++i){
		cout<<arr[i]<<" ";
	}
	cout<<"\n";
}

int main(){
	int arr[]={6, 5, 3, 1, 8, 7, 2, 4};
	int n = sizeof(arr)/sizeof(arr[0]); 

	/*Before Swap*/
	cout << "Before Swap:\n";
	print(arr,n);

	bubble_sort(arr,n);

	/*After Swap*/
	cout << "After Swap:\n";
	print(arr,n);
	return 0;
}
```
#### Output:
```
Before Sorting:
6 5 3 1 8 7 2 4
After Sorting:
1 2 3 4 5 6 7 8
```

## **Đánh giá thuật toán sắp xếp nổi bọt**

Với mỗi _i_ = 1, 2, ..., n-1 Ta cần _i_ phép so sánh. Do đó số nhiều nhất các lần so sánh và đổi chỗ trong giải thuật là:

$$ (n - 1) + (n - 2) +...+ 2 + 1 = \frac{(n-1)n}{2} $$

Độ phức tạp thuật toán cỡ $$O(n^2)$$

<br/> 

Nếu có bất kỳ thắc mắc nào, hãy để bình luận phía dưới để cùng nhau trao đổi nhé.






