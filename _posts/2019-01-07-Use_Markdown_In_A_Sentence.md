---
layout: post
title:  "Use Markdown In A Sentence"
date:   2019-01-07 16:09:20 +0700
categories: [others]
---



> 1. 헤더(Header)



헤더 크기는 1에서 6까지 지원한다.

```
# This is H1        
## This is H2
### This is H3
#### This is H4
##### This is H5
###### This is H6
```

# This is H1

## This is H2

### This is H3

#### This is H4

##### This is H5

###### This is H6





> 2. 인용구



인용구는 '>'를 이용한다. 인용구 안에서 다른 마크업 요소를 섞어서 사용할 수 있다.

```
> 안녕
> > 안녕
> > * 안녕
> > > * 안녕
```

> 안녕
>
> > 안녕
> >
> > * 안녕
> >
> > > * 안녕





> 3. 목록



* 순서가 있는 목록

```
  1. 일번
  2. 이번
  3. 삼번
```

1. 일번

2. 이번

3. 삼번


* 순서가 없는 목록

```
* 일번
  * 이번
    * 삼번
+ 일번
  + 이번
    + 삼번
- 일번
  - 이번
    - 삼번
```

- 일번
  - 이번
    - 삼번
- 일번
  - 이번
    - 삼번
- 일번
  - 이번
    - 삼번





> 4. 코드



'<pre> <code>'에 감싸서 사용한다.

```
<code>Github</code>
```

<code>Github</code>



```
  <pre><code>
  for i in range(1,2):
    print(i)
  </code></pre>
```

```
for i in range(1,2):
  print(i)
```



ps. [Rouge](http://rouge.jneen.net/) 하이라이터가 적용 되었다. 

```python
for i in range(1,2):
  print(i)
```





> 5. 수평선



```
------
************
```





> 6. 링크



* 인라인 링크

```
 [Google](http://google.com)
```

 [Google](http://google.com)



* 자동 연결 링크

```
<http://google.com>
```

<http://google.com>





> 8. 강조



진하게, 기울기, 취소선이 있다. 밑줄은 지원하지 않는다.

```
*single asterisks*
_single underscores_
**double asterisks**
__double underscores__
~~cancelline~~
```

*single asterisks*
_single underscores_
**double asterisks**
__double underscores__
~~cancelline~~



> 9. 이미지



```
![이미지 이름](이미지 url)로 이미지를 넣을 수 있다.
![Image name](https://user-images.githubusercontent.com/20412850/34468412-ba059536-ef4b-11e7-90d4-3313e9fed8f9.png)
```

![이미지 이름](이미지 url)로 이미지를 넣을 수 있다.
![Image name](https://user-images.githubusercontent.com/20412850/34468412-ba059536-ef4b-11e7-90d4-3313e9fed8f9.png)



ps. 사이즈 조정

```
<img src="이미지 url" width="원하는 크기">
<img src="https://user-images.githubusercontent.com/20412850/34468412-ba059536-ef4b-11e7-90d4-3313e9fed8f9.png" width="60%">
```

<img src="이미지 url" width="원하는 크기">
<img src="https://user-images.githubusercontent.com/20412850/34468412-ba059536-ef4b-11e7-90d4-3313e9fed8f9.png" width="60%">





> 10. 표그리기



표는 마크다운 표를 generate 해주는 사이트가 있다. 

원하는 양식에 맞춰서 만들고 가져다가 쓰면 편하다.

* 표 generate 사이트 : <https://www.tablesgenerator.com/markdown_tables>

```
First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell
```

| First Header | Second Header |
| ------------ | ------------- |
| Content Cell | Content Cell  |
| Content Cell | Content Cell  |



내용 정렬은 아래와 같이 한다.

```
First Header  | Second Header | Third Header
:------------ | :-----------: | -----------:
Left          | Center        | Right
```

| First Header | Second Header | Third Header |
| :----------- | :-----------: | -----------: |
| Left         |    Center     |        Right |







> 11. 수식(테마에서 지원 여부에 따라 사용)



```
$$ f(x) = \int \frac{2x^2+4x+6}{x-2} $$
```

$$ f(x) = \int \frac{2x^2+4x+6}{x-2} $$

