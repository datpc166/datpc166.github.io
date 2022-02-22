---
title: Thuật toán Sắp Xếp & Tìm Kiếm là gì?
layout: post
summary: Giới thiệu thuật toán sắp xếp, tìm kiếm
author: dylan
color: "background-color: firebrick"
date: '2022-02-22 14:35:23 +0530'
category: ['study','algorithms']
type: "Blog học thuật"
thumbnail: "/assets/img/posts/2022-02-22-what-are-sorting-searching/thumbnail.jpg"
keywords: sorting, searching, algorithms
usemathjax: true
permalink: "/blog/what-are-sorting-and-searching-algorithms/"
---

Hi mọi người, mình Đạt đây. Bài viết này là bài viết mở đầu các thuật toán sắp xếp và tìm kiếm trong series [Cấu Trúc Dữ Liệu và Giải Thuật](/blog/categories/algorithms/). Chúng ta cùng bắt đầu tìm hiểu nhé!

## **Sắp xếp và tìm kiếm là gì?**
Sắp xếp , tìm kiếm ? Ngay cái tên đã nói lên tất cả phải không nào. Hai thuật ngữ này không xa lạ gì với chúng ta, hơn nữa chúng còn được nhắc đến và sử dụng rất nhiều trong cuộc sống đó! Nhớ hồi xưa chúng ta còn học lớp 1, cô giáo dạy chúng ta so sánh rồi sắp xếp một dãy số tăng dần hoặc giảm dần, tìm số lớn nhất, nhỏ nhất ... đó cũng là những bài toán sắp xếp, tìm kiếm nhưng ở khía cạnh khác.

Giờ chúng ta bắt đầu đi vào chi tiết khái niệm sắp xếp, tìm kiếm nhé.

## **Thuật toán sắp xếp là gì?**
Sắp xếp là quá trình bố trí lại các phần tử trong một tập hợp theo một trình tự nào đó nhằm mục đích giúp quản lý và tìm kiếm các phần tử dễ dàng và nhanh chóng hơn. Điển hình nhất trong thực tế là các ứng dụng quản lý danh bạ điện thoại thì có sắp xếp theo số, theo tên. Quản lý học sinh thì có sắp xếp theo điểm, theo lớp, theo trường, ... Như vậy có rất nhiều mục đích cần phải sắp xếp các phần tử theo một trình tự. Điển hình nhất lúc bạn học lập trình đó là sắp xếp dãy số tăng dần, giảm dần bởi các kỹ thuật sắp xếp được nghiên cứu và phân tích kỹ lưỡng.

Trong khoa học máy tính và trong toán học, thuật toán sắp xếp là một thuật toán sắp xếp các phần tử của một danh sách (hoặc một mảng) theo thứ tự (tăng hoặc giảm). Và để dễ dàng cho việc nghiên cứu và học tập thì người ta thường gán các phần tử được sắp xếp là các chữ số.

Các thuật toán sắp xếp **cơ bản**:

- [Sắp xếp chọn (Selection Sort)](#)
- [Sắp xếp nổi bọt (Bubble Sort)](#)
- [Sắp xếp đổi chỗ trực tiếp (Interchange Sort)](#)
- [Sắp xếp chèn (Insertion Sort)](#)
- [Sắp xếp nhanh (Quick Sort)](#)
- [Sắp xếp đếm (Counting Sort)](#)
- [Sắp xếp trộn (Merge Sort)](#)

## **Thuật toán tìm kiếm là gì?**

**Tìm kiếm** là quá trình tìm một phần tử nằm trong một tập hợp nhiều phần tử dựa vào một đặc điểm nào đó. Ví dụ bạn cần tìm 1 tờ 20k trong một xấp tiền có giá trị từ 10k đến 500k thì quá trình đó gọi là tìm kiếm.

Tìm kiếm sẽ nhanh hơn nếu một tập hợp đã được **sắp xếp**. Ở ví dụ trên, Chúng ta có thể tìm tờ 20k nhanh hơn nếu một xấp tiền kia đã được sắp xếp tăng dần từ 10k đến 500k. Nhưng nếu đó là một mớ tiền lộn xộn thì bạn có thể mất nhiều thời gian với chúng, đặc biệt trong trường hợp tìm kiếm nhiều tờ 20k :D

Chúng ta thường sử dụng **hai thuật toán tìm kiếm**, đó là **tìm kiếm tuyến tính** và **tìm kiếm nhị phân**

**Thuật toán tìm kiếm tuyến tính** là quá trình tìm kiếm trong một tập hợp chưa sắp xếp, giống với đống tiền chưa được sắp xếp ở ví dụ trên. Còn **thuật toán tìm kiếm nhị phân** là quá trình tìm kiếm trong một dãy đã được sắp xếp. Cả hai thuật toán đều có những ưu và nhược điểm khác nhau. Ngoài ra chúng ta sẽ tìm hiểu thêm **thuật toán tìm kiếm nội suy**, nó là một cải tiến của thuật toán tìm kiếm nhị phân.

## **Lời Kết** 

Tổng kết lại, chúng ta sẽ học 7 thuật toán sắp xếp cơ bản và 3 thuật toán tìm kiếm. Đây là một chương rất quan trọng trong học phần Cấu trúc dữ liệu & giải thuật của các trường đại học khoa công nghệ thông tin. Đây mới chỉ bài học giới thiệu sơ lược hai thuật toán sắp xếp và tìm kiếm thôi, chông gai còn ở phía trước nữa :D. Đùa thôi :), những điều "hấp dẫn" sẽ chờ các bạn ở các bài viết tiếp theo, cùng đón chờ nhé.



