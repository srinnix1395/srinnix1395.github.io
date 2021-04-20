---
title: "[Android] Dagger 2 - Phần IV: A new horizon"
date: 2021-04-20 14:42:05 +0700
categories: [Programming]
tags: [android, dependency injection, dagger]
published: false
---

Bài viết là phần cuối của series bài học vỡ lòng về *Dagger 2*. Nếu bạn chưa đọc phần trước, bạn có thể ghi danh vào lớp học [tại đây](https://kipalog.com/posts/Android--Dagger-2---Phan-I--Basic-principles)

# Các bài học để lên lớp

1. [[Android] Dagger 2 - Phần I: Basic principles](https://srinnix1395.github.io/posts/Android-Dagger2-Ph%E1%BA%A7n-I/)
2. [[Android] Dagger 2 - Phần II: Into the Dagger 2](https://srinnix1395.github.io/posts/Android-Dagger2-Ph%E1%BA%A7n-II/)
3. [[Android] Dagger 2 - Phần III - 1: The time of our dependencies](https://srinnix1395.github.io/posts/Android-Dagger-2-Ph%E1%BA%A7n-III-1/)
4. [[Android] Dagger 2 - Phần III - 2: The time of our dependencies](https://srinnix1395.github.io/posts/Android-Dagger-2-Ph%E1%BA%A7n-III-2/)
5. [Android] Dagger 2 - Phần IV: A new horizon

# Trong bài học trước...







Chúng ta đã nói một chút về việc khởi tạo và quản lý dependency. Tiếp đó, chúng ta ngờ ngợ ra những vấn đề khi ứng dụng được scale up lên. Cuối cùng, chúng ta được giác ngộ với những design principle và design pattern có thể giải quyết giả thiết của bài toán ban đầu.

# Đi vào bài học hôm nay...

Chúng ta sẽ tìm hiểu sâu hơn về *Dagger 2*: trước là lý thuyết và sau là từng bước implement một chương trình đơn giản.

<p align="center">
  <img src="https://s3-ap-southeast-1.amazonaws.com/kipalog.com/y1bh782i5k_fredrik-ohlander-MU2pWu95UqA-unsplash.jpg">
  Photo by <a href="https://unsplash.com/@fredrikohlander?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Fredrik Öhlander</a> on <a href="https://unsplash.com/?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
</p>
