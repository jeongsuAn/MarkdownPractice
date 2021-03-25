> 마크다운 사용법
<br>

# __제목 (Headings)__
제목을 만들기 위해 두가지 방법을 사용할 수 있다
- code 앞에 `#` , `##` , `###` , ... , `#######` 을 넣어 제목수준을 정할 수 있다.   
`#`을 사용후 띄어쓰기를 해줘야 마크다운 문법이 인식한다는 것을 기억해야한다.   
- 원하는 제목을 만든 후 그 아래줄을 `====` 혹은 `----`로 해주면 제목이 만들어진다.   

이러한 두가지 표현 기법은 markdown파일을 txt에디터로 열었을 때에도 그 의미를 잘 파악할 수 있게 해준다.

*__MarkDown 문법__*
```
# Heading Level 1
## Heading Level 2
### Heading Level 3
#### Heading Level 4
##### Heading Level 5
###### Heading Level 6

Heading Level 1
===============

Heading Level 2
---------------
```
*__출력__*   
# Heading Level 1
## Heading Level 2
### Heading Level 3
#### Heading Level 4
##### Heading Level 5
###### Heading Level 6    

Heading Level 1
===============

Heading Level 2
---------------   

  
<br> <br> <br> <br> <br>


# __줄바꿈 (Line Breaks)__
* 띄어쓰기를 두번이상 한 후, 엔터(enter 혹은 return)를 하면 줄바꿈이 된다.   
* `<br>`을 입력하면 줄바꿈이 된다. `<br>`을 이용하면 여러줄 줄바꿈이 가능하다!  
<br>

## 문단 구분
엔터를 두번 하면 문단을 구분 할 수 있다.   

<br> <br> <br> <br> <br>

# __강조 (Emphasis)__
텍스트를 굵게 하거나 이텔릭체로 만들어서 강조할 수 있다.  
<br>

## 굵게 (bold)

`**  **`, `__ __`을 이용하여 텍스트를 굵게 표시할 수 있다. 

*__MarkDown 문법__*
```
**bold text**

__bold text__

중간**만** bold
```
*__출력__*   
**bold text**

__bold text__

중간**만** bold  

<br>

## 이탤릭체 (Italic)
`*  *`, `_ _`을 이용하여 텍스트를 이탤릭체로 표시할 수 있다.  

*__MarkDown 문법__*
```
*italic text*

_italic text_

중간*만* italic
```
*__출력__*   
*italic text*

_italic text_

중간*만* italic

<br>

## 굵은 이탤릭체 (Bold and Italic)
`***  ***`, `___ ___`을 이용하여 텍스트를 굵은 이탤릭체로 표시할 수 있다.  

*__MarkDown 문법__*
```
***bold italic***

___bold italic___

_**bold italic**_

*__bold italic__*

중간***만*** bold italic
```
*__출력__*   
***bold italic***

___bold italic___

_**bold italic**_

*__bold italic__*

중간***만*** bold italic

<br> <br>  <br> <br> <br>


# __인용구 (Blockquotes)__
단락앞에 `>` 을 추가하여 인용구를 생성 할 수 있다.
> 다음과 같이 인용구가 생성된 것을 확인 할 수 있다.  

<br>

## 여러 단락이 있는 인용구 (Blockquotes with Multiple Paragraphs)
첫번째 단락과 두번째 단락 사이에 `>`를 추가하여 여러단락의 인용구를 표현 할 수 있다.  

*__MarkDown 문법__*
```
> 첫번째 단락
>
> 두번째 단락  
```
*__출력__*   

> 첫번째 단락
>
> 두번째 단락    

<br>

## 중첩 인용구 (Nested Blockquotes)
중첩하려는 단락에 `>>`를 추가하여 중첩 인용구를 표현 할 수 있다.  

*__MarkDown 문법__*
```
> 첫번째 단락
>
>> 중첩하려는 단락  
```
*__출력__*    

> 첫번째 단락
>
>> 중첩하려는 단락    

<br>

## 다른요소가 있는 인용구 (Blockquotes with Other Elements)
인용구 안에 다른 마크다운 문법에 맞는 요소를 활용할 수 있다.
(모든 문법이 적용되는 것은 아니다)

*__MarkDown 문법__*
```
> 첫번째 단락
> - 순서가 정의되지 않는 리스트 
> - 순서가 정의되지 않는 리스트 
> 1. 첫번째 순서 리스트  
> 2. 두번째 순서 리스트  
>
> `단어나 코드` 표시하기
```
*__출력__*    
> 첫번째 단락
> - 순서가 정의되지 않는 리스트 
> - 순서가 정의되지 않는 리스트 
> 1. 첫번째 순서 리스트  
> 2. 두번째 순서 리스트  
>
> `단어나 코드` 표시하기

<br> <br> <br> <br> <br>

# __리스트 (List)__ 
순서가 정의된 리스트나 순서가 정의되지 않은 리스트를 사용할 수 있다.

## 순서가 정의된 리스트 (Ordered Lists)
`1.`, `2.`, `3.`등을 이용하여 순서가 정의된 리스트를 정의할 수 있다.  
마크다운 문법에서는 사용자의 편의를 고려하여 순서가 뒤죽박죽 되지 않도록 도와준다

*__MarkDown 문법__*
```
1. 첫번째 아이템
2. 두번째 아이템    
    1. indented item
4. `4.`를 넣어도 올바르게 `3.` 으로 출력된다. 
    1. `1.`으로만 표시해도 
    1. 자동으로 오름차순으로 
    1. 표시된다 
```
*__출력__*    
1. 첫번째 아이템
2. 두번째 아이템    
    1. indented item
4. `4.`를 넣어도 올바르게 `3.` 으로 출력된다. 
    1. `1.`으로만 표시해도 
    1. 자동으로 오름차순으로 
    1. 표시된다 

<br>

## 순서가 정의되지 않은 리스트 (Unordered Lists)
`-`, `*`, `+` 를 이용하여 순서가 정의되지 않은 리스트를 정의할 수 있다.   
문단 처음에 기호를 사용한뒤 띄어쓰기(space)를 사용하면 적용된다.  

*__MarkDown 문법__*
```
- `-` 를 이용하여 만든 순서가 정의되지 않은 리스트
    - `-` 를 이용하여 만든 indented item
    * `*` 를 이용하여 만든 indented item
    + `+` 를 이용하여 만든 indented item
    일반 문자를 indented 할 수도 있다.
    > 인용문을 indented 하는 것도 가능하다.

      #inclued <iostream>

      int main(){
          return 0;
      } //이와 같은 코드를 넣는 것도 가능하다

    다음과 같은 명령어를 사용하여 이미지를 삽입 하는것도 가능하다  
    ![hogikUniv](./hongikUniv.png) -> 이렇게 추가시 이미지 사이즈 조절 안됨   
    <img src="./hongikUniv.png" alt="drawing" width="100"/>
       
* `*` 를 이용하여 만든 순서가 정의되지 않은 리스트
+ `+` 를 이용하여 만든 순서가 정의되지 않은 리스트
```
*__출력__*    
- `-` 를 이용하여 만든 순서가 정의되지 않은 리스트
    - `-` 를 이용하여 만든 indented item
    * `*` 를 이용하여 만든 indented item
    + `+` 를 이용하여 만든 indented item
    일반 문자를 indented 할 수도 있다.
    > 인용문을 indented 하는 것도 가능하다.
    
      #inclued <iostream>

      int main(){
          return 0;
      } //이와 같은 코드를 넣는 것도 가능하다
    
    다음과 같은 명령어를 사용하여 이미지를 삽입 하는것도 가능하다  
    ![hogikUniv](./hongikUniv.png) -> 이렇게 추가시 이미지 사이즈 조절 안됨   
    <img src="./hongikUniv.png" alt="drawing" width="100"/>
       
* `*` 를 이용하여 만든 순서가 정의되지 않은 리스트  


<br> <br> <br> <br> <br> 

# __코드 (code)와 코드 블록(code block)__ 

## 코드 (code)
단어나 구를 코드(code)로 표현하려면 `으로 감싸서 표현한다.    
*__MarkDown 문법__*
```
`code로 표현`
```
*__출력__*    
`code로 표현`  

<br>

## 코드 블록 (code block)
코드로 표현하려는 부분의 앞부분에 4칸의 공간(space)을 두거나 탭(tab)을 하여 코드로 나타낸다.  
 
*__MarkDown 문법__*
```
    #include <iostream>

    int main(){
        std::cout<<"hihi"<<std::endl;
        return 0;
    }
```
*__출력__*     

    #include <iostream>

    int main(){
        std::cout<<"hihi"<<std::endl;
        return 0;
    }

      
<br> <br> <br> <br> <br>

# __수평선 (Horizontal Rules)__
수평선을 만들기위해서는 3개 이상의 `***`, `---`, `___` 을 한줄로 단독으로 사용해야한다.
마크다운 어플리케이션들마다 적용되는 문법이 조금씩 다를 수도 있기 때문에 수평선 앞뒤로 빈줄을 넣어줘야한다.

*__MarkDown 문법__*
```

************

------------

____________
 
```
*__출력__*    

************

------------

____________

<br> <br> <br> <br> <br> 

# __링크 (Link)__ 
## 제목을 추가한 링크 (Adding Titles)

링크를 만들기위해서 `[ 제목 ]`뒤에 `(URL)`을 붙여서 표시할 수 있다.   

 *__MarkDown 문법__*

```
제 github URL은 다음과 같습니다 > [jeongsuAn](https://github.com/jeongsuAn)
```
*__출력__*    
제 github URL은 다음과 같습니다 > [jeongsuAn](https://github.com/jeongsuAn)  

<br>

## URL과 Email Addresses  
URL과 email addresses를 링킹하기 위해선 `< >`를 사용한다. 

 *__MarkDown 문법__*

```
<https://www.naver.com>  
<dks9467@g.hongik.ac.kr>
```
*__출력__*    
<https://www.google.com>  
<dks9467@g.hongik.ac.kr>  
  
 <br> 

## 링크 강조 (Formatting Links)
링크를 강조하기 위해서 링크를 굵게하거나, 이태릭체를 하거나, 코드형식으로 바꿀 수 있다. 
 *__MarkDown 문법__*

```
링크를 굵게 하는 방법은 `** **` 나 `__ __` 를 사용한다. __<https://www.naver.com>__  
이태릭체를 표현하기 위해서는 `* *` 나 `_ _` 를 사용한다. _<dks9467@g.hongik.ac.kr>_  
코드 형식으로 하기 위해서는 ` `` ` 후 `#`를 사용한다. [`jeongsuAn`](#https://github.com/jeongsuAn)
```
링크를 굵게 하는 방법은 `** **` 나 `__ __` 를 사용한다. __<https://www.naver.com>__  
이태릭체를 표현하기 위해서는 `* *` 나 `_ _` 를 사용한다. _<dks9467@g.hongik.ac.kr>_  
코드 형식으로 하기 위해서는 ` `` ` 후 `#`를 사용한다. [`jeongsuAn`](#https://github.com/jeongsuAn)  

<br>

## 참조 스타일 링크 (Reference-style Links)
참조 스타일 링크는 URL을 쉽게 표기하여 가독성을 높여주는 방법이다. 이 참조 스타일 링크는 두부분으로 구성된다. 마치 책에서 어려운 내용에 각주를 달아 자세한 내용은 밑에서 각주부분에서 설명하는 것처럼 링크를 따로 적을 수 적어놓을 수 있다. 

### 링크의 첫번째 부분 서식
두 세트의 대괄호 `[ ]`로 형식이 지정된다. 첫번째 대괄호에는 보통 번호가 쓰이며, 두번째 대괄호는 번호에 맞는 링크를 적어두어 그 링크에 들어갈 수 있게 해준다. 이는 텍스트의 가독성을 높힐 수 있는 방법이다.  

### 링크의 두번째 부분 서식
괄호로 묶인 레이블 바로뒤에 콜론 `:`과 하나이상의 공백 ` `을 넣자  
URL링크는 `< >`로 묶을 수 있다.
`" "`, `' '`, `( )`으로 링크의 주석(제목)을 달 수 있다. 

 *__MarkDown 문법__*

```
홍익대 홈페이지인 [클래스넷][1]을 보자  

[1]:https://cn2.hongik.ac.kr/ 
[1]:https://cn2.hongik.ac.kr/  "여러종류의"
[1]:https://cn2.hongik.ac.kr/  '주석 형식을'
[1]:https://cn2.hongik.ac.kr/  (적용할 수 있다)
[1]:<https://cn2.hongik.ac.kr/> "< >로"
[1]:<https://cn2.hongik.ac.kr/> 'URL을'
[1]:<https://cn2.hongik.ac.kr/> (묶을 수도 있다)
```
*__출력__*    
홍익대 홈페이지인 [클래스넷][1]을 보자  

[1]:https://cn2.hongik.ac.kr/ 
[1]:https://cn2.hongik.ac.kr/   "여러종류의"
[1]:https://cn2.hongik.ac.kr/   '주석 형식을'
[1]:https://cn2.hongik.ac.kr/   (적용할 수 있다)
[1]:<https://cn2.hongik.ac.kr/> "< >로"
[1]:<https://cn2.hongik.ac.kr/> 'URL을'
[1]:<https://cn2.hongik.ac.kr/> (묶을 수도 있다)
  

<br> <br> <br> <br> <br> 

# __이미지__
이미지를 추가하려면 `![텍스트][이미지경로]` 형식을 이용하여 이미지를 넣을 수 있다.
또한 이미지 뒤에 주석(제목)을 추가할 수도 있다 `![텍스트][이미지경로 "주석"]`

*__MarkDown 문법__*

```
![hogikUniv](./hongikUniv.png)
```
*__출력__*    
![hogikUniv](./hongikUniv.png)

<br>

## 이미지에 링크 추가하기
이미지를 클릭했을 때 내가 원하는 URL로 가게 하기 위해서는 다음과 같은 형식을 이용하면 된다. 
`[![텍스트](이미지경로)](URL)` 

*__MarkDown 문법__*

```
[![hogikUniv](./hongikUniv.png)](https://www.hongik.ac.kr/index.do "홍익대 홈페이지")
```
*__출력__*    
[![hogikUniv](./hongikUniv.png)](https://www.hongik.ac.kr/index.do "홍익대 홈페이지")


<br> <br> <br> <br> <br> 

# 이스케이프 문자 (Escaping Characters)
이스케이프가 없으면 *과 같은 문자열을 사용할 때 자동으로 리스트 형식으로 바뀔 수가 있다. 
이를 방지하기 위해서는 이스케이프 문자인 `\`가 필요하다
이때 이스케이프 할 수 있는 문자의 종류로는 `\`, `*`, `_`, `{}`, `[]`, `<>`, `()`, `#`, `+`, `-`, `.`, `!`, `|` 등이 있다. 

*__MarkDown 문법__*

```
* 이스케이프 문자 사용 안했을 때

\* 이스케이프 문자 사용 했을 때
```
*__출력__*     
* 이스케이프 문자 사용 안했을 때

\* 이스케이프 문자 사용 했을 때

<br> <br> <br> <br> <br> 

# __GitHub Flavored Markdown__

# __표(Tables)__
각 행은 `|`로 구분되며 행의 내용에 구분을 주기 위하여 `---`를 이용한다.   
`:---`, `:---:`, `---:`을 사용하여 각 열의 정렬 상태를 정의할 수 있다.    
`-`의 개수는 txt파일로 봤을때도 가독성이 좋을 수 있도록 표현해주면 된다.  
`|-------|`로 열의 수를 구분 해놓으면 해당 본문에 아무것도 넣지 않아도 빈칸으로 출력되며, 정해놓은 열밖으로 넘어간 열은 무시된다.  


*__MarkDown 문법__*

```
| 머리말 1열 | 머리말 2열 | 머리말 3열 |
|:---------|:-------:|---------:|
|  본문 1열  | 본문 2열  |  본문 3열 |
|  본문 1열  | 옆 빈칸-> |
|  본문 1열  | 본문 2열  | 본문 3열  | 여기엔 써도 무시됨 |
```
*__출력__*    
| 머리말 1열 | 머리말 2열 | 머리말 3열 |
|:---------|:-------:|---------:|
|  본문 1열  | 본문 2열  |  본문 3열 |
|  본문 1열  | 옆 빈칸-> |
|  본문 1열  | 본문 2열  | 본문 3열  | 여기엔 써도 무시됨 |

<br> <br> <br> <br> <br> 

# __Todo 리스트 만들기 (Task list item)__
`- [ ]`와 `- [x]`,`- [X]` 를 이용하여 Todo list를 만들 수 있다.   
물론 들여쓰기도 가능하다.

*__MarkDown 문법__*

```
- [ ] 마크다운 문서 작성하기
  - [x] Basic Syntax 부분 작성하기
  - [ ] extention 부분 작성하기
- [x] 객체지향 공부하기  
- [X] 알고리즘 공부하기 
- [ ] AI 공부하기 
- [ ] 소프트웨어 공학 공부하기  
```
*__출력__*   
- [ ] 마크다운 문서 작성하기
  - [x] Basic Syntax 부분 작성하기
  - [ ] extention 부분 작성하기
- [x] 객체지향 공부하기  
- [X] 알고리즘 공부하기 
- [ ] AI 공부하기 
- [ ] 소프트웨어 공학 공부하기  

<br> <br> <br> <br> <br> 

# __취소선 (StrikeThrough)__ 
`~~`취소선 넣을부분`~~`을 하면 취소선을 만들 수 있다.  

*__MarkDown 문법__*

```
문장 중간에 `~~`를 이용하여 ~~취소선~~을 만들 수 있다.  

만약  `~~`를 끝맺음 하지 않고 줄이 한칸 ~~띄어지면

취소선이 생기지 않는다~~
```
*__출력__*    

문장 중간에 `~~`를 이용하여 ~~취소선~~을 만들 수 있다.  

만약  `~~`를 끝맺음 하지 않고 줄이 한칸 ~~띄어지면

취소선이 생기지 않는다~~


<br> <br> <br> <br> <br> 


# __자동 링크 (Autolink)__
http를 굳이 넣지 않더라고 자동으로 URL을 인식하여 하이퍼링크로 만들어주는 기능이다.  
이때 몇가지 알아두면 좋은 것들이 있다. 하지만 아래 내용을 알지 않더라도, 그냥 평범하게 주소를 적으면 아무 문제없다.
- 링크 중`<`이 들어가면 `<`이 들어가기 전까지를 링크로 만들어준다.  
- 링크 마지막이 `)`로 끝난다면 링크의 `( )`짝에 맞게까지만 인식한다.  
    ( 링크가 `)`로 안끝나면 상관 없음 )
- 링크 마지막 부분이 `?`, `!`, `.`, `,`, `:`, `*`, `_`, `~`로 끝난다면 이것은 링크로 고려되지 않는다.

*__MarkDown 문법__*

```
www.google.com  

www.google.com 으로 이동  

www.google.com/hih<i 

www.google.com/(hihi)) 

www.google.com?
```
*__출력__*    
www.google.com  

www.google.com 으로 이동  

www.google.com/hih<i 

www.google.com/(hihi)) 

www.google.com?

<br> <br> <br> <br> <br> 


