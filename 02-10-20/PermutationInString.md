# Permutation in a String

Given a string and a pattern, find out if the string **contains any permutation of the pattern**.

**Permutation** is defined as the re-arranging of the characters of the string. For example, “abc” has the following six permutations:

abc
acb
bac
bca
cab
cba

If a string has ‘n’ distinct characters it will have _n!_ permutations.

#### Example 1

```
Input: String="oidbcaf", Pattern="abc"
Output: true
Explanation: The string contains "bca" which is a permutation of the given pattern.
```

#### Example 2

```
Input: String="odicf", Pattern="dc"
Output: false
Explanation: No permutation of the pattern is present in the given string as a substring.
```

#### Example 3

```
Input: String="bcdxabcdy", Pattern="bcdyabcdx"
Output: true
Explanation: Both the string and the pattern are a permutation of each other.
```

#### Example 4

```
Input: String="aaacb", Pattern="abc"
Output: true
Explanation: The string contains "acb" which is a permutation of the given pattern.
```

### Try solving the problem by contibuting your answers in a different file using one of the following languages

#### Java

```java
class StringPermutation {
  public static boolean findPermutation(String str, String pattern) {
    // TODO: Write your code here
    return false;
  }
}
```
#### Python

```python
def find_permutation(str, pattern):
  # TODO: Write your code here
  return False
```

#### Javascript

```js
const find_permutation = function(str, pattern) {
  // TODO: Write your code here
  return false;
};
```

#### C++

```c++
class StringPermutation {
 public:
  static bool findPermutation(const string &str, const string &pattern) {
    // TODO: Write your code here
    return false;
  }
};
```

#### Explanation

Explain in details the steps of your solution

```
1. First we iterate through the string ...
2. ... etc.
```

#### Time Complexity

```
The time complexity of the above algorithm will be ...
```

#### Space Complexity

```
The space complexity of the above algorithm will be ...
```


 
