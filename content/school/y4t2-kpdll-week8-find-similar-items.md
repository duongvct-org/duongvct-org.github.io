---
title: Mining of massive datasets - Finding similar items - Locality sensitive hashing
keywords: [big-data, locality-sensitive-hashing, find-similar-items]
date: 2026-03-16
theme: big-data
description:
  Year 4 Term 2 - Mining of massive datasets - Finding similar items: Locality sensitive hashing
---
Mining of massive datasets - Finding similar items: Locality sensitive hashing


# Y4T2-KPDLL-WEEK8 Finding similar items - locality sensitive hashing

## A-Priori:
Quan sát rằng để tìm được 1 cặp a-b xuất hiện n lần thì cả a và b đều phải xuất hiện n lần

Các bước:

- đếm số lần xuất hiện của từng item
- Lọc những item mà số lần xuất hiện $\gt \lambda$  -> lấy k items ( k <<<< n)
- duyệt và đếm số cặp trong K item(O($K^2$))

Điểm yếu của thuật toán: do giả định nếu i và j xuất hiện nhiều lần thì i và j sẽ cùng nhau xuất hiện nhiều lần -> không hoàn toàn đúng trong thực tế

Cải thiện -> PCY

## PCY

# References

- https://medium.com/weekly-data-science/the-pcy-algorithm-and-its-friends-ecba67216190
- http://infolab.stanford.edu/~ullman/cs345notes/cs345-7.pdf

![Finding Similar Items Lecture Notes](http://infolab.stanford.edu/~ullman/cs345notes/cs345-7.pdf){height=800px}

