# *문서작성시 참고하면서 작성합시다.*  
# **이탈릭체는 사이에 글자넣으세요
-----

#  마크다운예제 *# h1*
##  마크다운예제 *## h28*
###  마크다운예제 *### h3*
####  마크다운예제 *####h4*
##### 마크다운예제 *##### h*

------

> ##### 인용글입니다.   * > 인용글입니다.*
> ##### 인용글2번째줄. *> 인용글2번째줄.*

------
### 리스트 구현하기
* 고구마    **고구마*
* 감자       **감자*
* 옥수수    {tab}  
**옥수수를 이어지게 작성하고싶다  
작성하고싶다.
{tab}탭을 누르면 밑으로 간다  {tab}   
알았지*

----
1. 고구마     *1.고구마*
3. 고구마     *3.고구마*
2. 고구마     *2.고구마*

---
### 리스트가아니라 문자열 숫자로 표기하고싶을때 !

1\. 감자   *역슬래쉬.감자*    {tab}  
3\. 고구마
2\. 옥수수

-------------------
### html표기법을 사용하고싶다면 '  ``<table>` ` ' 물결표시에 있는거 역방향 강세기호( )

`<table><tr><td></td></tr></table>`

--------
### 링크를 걸고싶다면
#### 1. `[네이버](http://naver.com)`
#### 2. `[간지나냐][http://naver.com]`
#### 3. `<http://daum.net>`

[네이버](http://naver.com)   
[간지나냐][http://naver.com]  
<http://daum.net>

----------
### 글자표현
#### 1.`*이텔릭체*`  or `_이텔릭체_`
#### 2.`**볼드체**`  or ' __볼드체'

*이탤릭체1* _이탤릭체2_   
**볼드체** __볼드체__


---

### 이미지 삽입
#### `![사진이름](사진경로)` 사진경로는 http://로 시작해도되요.

![문채원](C:\Users\MIN\Pictures\Saved Pictures\캡처.PNG)

-------
### 문법을 문자열로 취급하고싶다면 `\ 를사용하자 ex) \*뭘까\*`
\* 뭘까   
\*뭘까\*
