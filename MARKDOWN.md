# 문단 나누기
### Markdown
> `enter` 2번 입력해     
>
> 문단을 나눌수 있습니다.         
### HTML
> `<p></p>`을 사용해 <p>나눌수도 있습니다.</p>
<br>

# 개행
### Markdown
> 문장의 마지막에 `space bar`  
> 2번 입력해 개행합니다.  
### HTML
> `<br>`을 사용해 <br>개행합니다.
<br>

# 제목
### Markdown
> - `#`을 이용해 제목을 입력합니다. #은 6개까지 사용가능합니다.  
>     # 제목은 `# 제목`  
>     ## 제목은 `## 제목`  
>     ### 제목은 `### 제목`  
>     #### 제목은 `#### 제목`
>     ##### 제목은 `##### 제목` 
>     ###### 제목은 `###### 제목` 
<br>

# 글씨 표현
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
> - ``(홑따옴표) 안에 글씨를 입력하면 `블록` 처리 됩니다. Inline Block Code 라고도 합니다.
### HTML
> - `<strong></strong>`을 사용해 <strong>굵게 처리</strong>.  
> - `<i></i>` 또는 `<em></em>`을 사용해 <i>기울림</i><em>처리</em> 
> - 둘다 사용하는 경우 <strong><i>굵게 기울림</strong></i>
<br>

## 선
### Markdown
> - `~`을 사용하여 취소선 처리합니다.  
>   `~~취소선~~` 은 ~~취소선~~  
~~### HTML
> `<u><\u>` 를 이용하여 <u>밑줄</u>을 표현합니다.~~  

# 링크
## 웹
### Markdown
> - `[]`와 `()`을 사용합니다.
>   `[Google](http://www.google.co.kr)` 은 [Google](http://www.google.co.kr)
>
> - 또는 링크 자체를 삽입하여 사용합니다.
> http://www.google.com
## 그림
### Markdown
> - `[]`와 `()`을 사용하되 맨앞에 !을 붙여 사용합니다.  
>   `![밥](http://www.bibigo.com/img/kr/img_bap1.jpg)` 은  
>    ![밥](http://www.bibigo.com/img/kr/img_bap1.jpg)
### HTML
> - `<img></img>`를 사용합니다. `width`와`height`를 사용해 크기를 조절할 수 있습니다.
>   `<img src="http://www.bibigo.com/img/kr/img_bap1.jpg" width="300px" height="300px">` 은  
>   <img src="http://www.bibigo.com/img/kr/img_bap1.jpg" width="300px" height="300px">  

# 목차
### Markdown
> - `-`나 `+`나 `*`를 사용합니다.

> - 목차1은 `- 목차1`  
> - 목차2는 `- 목차2`  
> - 목차3은 `- 목차3`

> - `tab`으로 들여쓰기 하여 사용할수도 있습니다.  
> - 목차1
>   - 목차2 
>     - 목차3

> 는 
> ~[목차 예시]https://github.com/billCollection/theorem-summary/blob/master/%EC%84%A4%EB%AA%85%EC%9A%A9%20%EA%B7%B8%EB%A6%BC/%EB%AA%A9%EC%B0%A8.PNG
