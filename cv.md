# Margarita Lin
**Contact Me:**

[LinkedIn](https://www.linkedin.com/in/margarita-torosian/)  
[Email](mailto:xxl_century@yahoo.com)  
[GitHub](https://github.com/mareedez/)  

**About Me**

Working towards my Computer Science degree while attending additional practice-based courses.
Looking for the oportunity to get an Internship or Trainee position in Web Development.

:page_with_curl: **Technologies Used**

- HTML / CSS
- Javascript
- Python
- React
- SQL-databases
- Git / GitHub / GitLab
- Linux CLI
- BEM methodology

**Some Leetcode**

*Two Sum*

```sh
class Solution:
    def twoSum(self, nums: List[int], target: int) -> List[int]:
        been_there = {}
        for i, x in enumerate(nums):
            difference = target - x
            if difference in been_there:
                return [i, been_there[difference]]
            been_there[x] = i
```
*First Unique Character*
```sh
class Solution:
    def firstUniqChar(self, s: str) -> int:
        for letter in s:
            if s.index(letter) == s.rindex(letter):
                return s.index(letter)
        return -1
```
**Education**
- **UOPeople** <br />Computer Science <br />(*2020-2024*)

- **Smolensk State Medical University** <br />MBBS <br />(*2010-2016*)

:orange_book: **Courses**
- **Innopolis University** <br />Frontend Development Basics

- **Hexlet** <br />Python Developer

**Project**

[React Blog](https://github.com/mareedez/blog)

Created responsive SPA using HTML/CSS/React/Redux

**Languages I Speak**
- **Russian** <br />Level: Native

- **English** <br />Level: C1<br />American English College, Los Angeles<br />(*2019-2020*)
