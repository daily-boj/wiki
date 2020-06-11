# 순열과 조합

## 순열

**순열**(permutation)은 서로 다른 $n$개의 원소에서,
$r (\le n)$개를 뽑아 한 줄로 세우는 경우의 수이다.

### next_permutation

C++ 표준의 \<algorithm\> 헤더에는 [std::next_permutation](https://en.cppreference.com/w/cpp/algorithm/next_permutation) 함수가 있다.
이 함수를 활용하면 순열을 쉽게 순회할 수 있다.

## 조합

**조합**(combination)은 서로 다른 $n$개의 원소에서,
$r (\le n)$개를 순서에 상관 없이 뽑는 경우의 수이다.
