# CMPS 2200 Recitation 01
## Answers

**Name:**__Srikanya Balaji Garuda_
**Name:**_________________________


Place all written answers from `recitation-01.md` here for easier grading.

- **4)** Describe the worst case input value of `key` for `linear_search`? for `binary_search`? 

The worst case input value of key for linear search is a value not present or the last value in the list. The worst case input value for binary search is a value not present, the first value, or the last value in the list.

- **5)** Describe the best case input value of `key` for `linear_search`? for `binary_search`? 

The best case input value of key for linear search is the first value in the list. The best case input value for binary search is the middle value in the list.

- **8)** Call `print_results(compare_search())` and paste the results here:

|        n |   linear |   binary |
|----------|----------|----------|
|       10 |    0.005 |    0.016 |
|      100 |    0.013 |    0.003 |
|     1000 |    0.862 |    0.006 |
|    10000 |    0.763 |    0.005 |
|   100000 |    8.011 |    0.015 |
|  1000000 |   81.870 |    0.032 |
| 10000000 |  869.059 |    0.028 |

- **9)** Do the theoretical running times match your empirical results?

The theoretical run times do match my empirical results since as n increases, linear search becomes increasingly longer matching with it's run time of $O(n)$, whereas binary research remains fast as input size increases, matching with it's run time of $O(\log_2(n))$

- **10a)** What is worst-case complexity of searching a list of $n$ elements $k$ times using linear search? 

$O(nk)$

- **10b)** For binary search? 

$O(\log_2(n)*k)$

- **10c)** For what values of $k$ is it more efficient to first sort and then use binary search versus just using linear search without sorting? You may assume that your sorting algorithm runs in $O(n \lg n)$ time.
$k > \frac{nlog_2(n)}{n-log_2(n)}$

   