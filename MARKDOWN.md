# 문단 나누기
### Markdown
> `enter` 2번 입력해     
>
> 문단을 나눌수 있습니다.
> - 단, `enter`를 많이 입력해도 여러번 문단이 나뉘지 않습니다.
### HTML
> `<p></p>`을 사용해 <p>나눌수도 있습니다.</p>
>> p : paragraph, 문단

<br><br>

# 개행
### Markdown
> 문장의 마지막에 `space bar`  
> 2번 입력해 개행합니다.  
> - 단, `space bar`를 많이 입력해도 여러번 개행되지는 않습니다.
### HTML
> `<br>`을 사용해 <br>개행합니다.
>> br : break, 개행

<br><br>

# 제목
### Markdown
> - `#`을 이용해 제목을 입력합니다. #은 6개까지 사용가능합니다.  
>     # 제목은 `# 제목`  
>     ## 제목은 `## 제목`  
>     ### 제목은 `### 제목`  
>     #### 제목은 `#### 제목`
>     ##### 제목은 `##### 제목` 
>     ###### 제목은 `###### 제목`

<br><br>

# 표현
## 강조
### Markdown
> - `*` 또는 `_` 를 사용합니다. 둘 다 3개까지 사용가능합니다.  
> 1개 사용시 *기울림(이탤릭체)*, 2개 사용시 **굵게(볼드체)**, 3개 사용시 ***굵게 기울림*** 입니다.
>
>
>   `*q*` 는 *q*  
>   `**w**` 는 **w**  
>   `***e***` 는 ***e***  
>
>   `_q_` 는 _q_  
>   `__w__` 는 __w__  
>   `___e___` 는 ___e___ 
> - \`블록\`은 `블록` 처리 됩니다. Inline Block Code 라고도 합니다.
> - Markdown 문법을 표현하려 할 때 `\`를 이용합니다.
>   `\*q*` 는 \*q*


### HTML
> - `<strong></strong>`을 사용해 <strong>굵게 처리</strong>.  
> - `<i></i>` 또는 `<em></em>`을 사용해 <i>기울림</i><em>처리</em> 
> - 둘다 사용하는 경우 <strong><i>굵게 기울림</strong></i>  
>> i : italic, 기울림 / em : emphasize, 강조하다

## 선
### Markdown
> - `~`을 사용하여 취소선 처리합니다.  
>   `~~취소선~~` 은 ~~취소선~~

## 표
### Markdown
> - `|(바)`와 `-(하이픈)`을 사용합니다.
```
제목1 | 제목2
------|-------
내용1|내용2
내용3|내용4
```
> 이는 다음과 같이 표현됩니다.  

제목1 | 제목2  
------|-------  
내용1|내용2  
내용3|내용4  

<br><br>

# 링크
## 웹
### Markdown
> - `[]`와 `()`을 사용합니다.
>   `[Google](http://www.google.co.kr)` 은 [Google](http://www.google.co.kr)
>
> - 또는 링크 자체를 삽입하여 사용합니다.
> http://www.google.co.kr
### HTML
> - `<a href></a>`를 사용합니다.
>   `<a href="http://naver.com">네이버</a>` 는 <a href="http://naver.com">네이버</a>
>> a : anchor, 닻 / href : hypertext reference

## 그림
### Markdown
> - `[]`와 `()`을 사용하되 맨앞에 !을 붙여 사용합니다.  
```
![밥](http://www.bibigo.com/img/kr/img_bap1.jpg)  
```

>  이는 다음과 같이 표현됩니다.  
>    ![밥](http://www.bibigo.com/img/kr/img_bap1.jpg)
### HTML
> - `<img></img>`를 사용합니다.
>   `width`와 `height`를 사용해 크기를 조절할 수 있습니다.  
```
<img src="http://www.bibigo.com/img/kr/img_bap1.jpg" width="300px" height="300px">
```

>   이는 다음과 같이 표현됩니다.  
>   <img src="http://www.bibigo.com/img/kr/img_bap1.jpg" width="300px" height="300px">  
>> img : image, 이미지 / src : source, 출처

<br><br>

# 목차
### Markdown
>> `-`나 `+`나 `*`를 사용합니다.
>
> - 목차1은 `- 목차1`  
> - 목차2는 `- 목차2`  
> - 목차3은 `- 목차3`  
>
> + 목차4은 `+ 목차4`  
> + 목차5는 `+ 목차5`  
> + 목차6은 `+ 목차6`  
>
> * 목차7은 `* 목차7`  
> * 목차8는 `* 목차8`  
> * 목차9은 `* 목차9`  

>> `tab`으로 들여쓰기 하여 사용할수도 있습니다.<br>  
```
- 목차1
    - 목차2
        - 목차3
```
>
> 이는 다음과 같이 표현됩니다.
> - 목차1
>   - 목차2 
>     - 목차3

>> 숫자를 사용할수도 있습니다.<br>  
```
1. 목차1
1. 목차2
1. 목차3
```

>
> 이는 다음과 같이 표현됩니다.
> 1. 목차1
> 1. 목차2
> 1. 목차3
<br><br>

# 코드 표현
### Markdown
>- ` 을 코드 맨앞과 맨뒤에 3번 사용합니다. 코드의 언어를 입력하면 이에 맞게 *highlighting* 됩니다.<br>  
>
>\```python  
>def sum(a, b):  
>return a+b  
>\```  
```python
def sum(a, b):  
return a+b  
```

>\```c  
>void f(){  
>   printf(%s,"Hello world!");  
>}  
>\```  
```c
void f(){
    printf(%s,"Hello world!");
}
```
<br><br>
# 단락
## 인용
### Markdown
> - `>` 로 시작합니다.<br>  
> 
```
>인용1  
>>인용2  
>>>인용3
```
<br>  

이는 다음과 같이 표현됩니다.<br>  
> 인용1
>> 인용2
>>> 인용3  

## 분류
### Markdown
> - `*` 또는 `-`를 3개 사용합니다. 3개 이상 사용해도 되나 결과는 같습니다.  
> `***` 또는 `---` 는 다음과 같이 표현됩니다.  
***
---
