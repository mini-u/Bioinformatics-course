# Bioinformatics Lecture - Week3 Markdown Language

## 1. Markdown 소개
### 1.1 Markdown
마크다운(Markdown)은 텍스트 기반의 마크업 언어의 일종입니다. 2004년 존 그루버와 아론 스워츠가 만들었습니다. 마크업 언어는 화면에 표시되는 형식 또는 데이터의 논리적 구조를 나타내기 위한 규칙 언어입니다. 마크다운은 HTML과 같이 복잡한 태그 형식이 아닌 특수기호와 문자를 이용한 간단한 구조로 내용을 작성할 수 있습니다. 마크다운은 Github 등에서 많이 사용합니다.

- 마크다운이 사용되는 곳
1. Github
1. Jupyter Notebook
1. Stack Overflow
1. Blog
1. Obsidian

## 2. Markdown 작성법
### 2.1 Header 작성
헤더는 # 의 개수를 가지고 작성할 수 있습니다.
\# H1
\## H2
\### H3
\#### H4
\##### H5
\###### H6
H6 까지 있습니다.
# H1
## H2
### H3
#### H4
##### H5
###### H6

### 2.2 글씨체
\*이탤릭\* -> *이탤릭*
\*\*강조\*\* -> **강조**
\*\*\*이탤릭_강조\*\*\* -> ***이탤릭_강조***
\~\~취소\~\~ -> ~~취소~~
\<u>밑줄\</u> -> <u>밑줄</u>

### 2.3 목록
순서가 없는 목록은 - 기호와 들여쓰기로 작성합니다.
- 항목 1
    - 항목 1-1
        - 항목 1-1-1
        - 항목 1-1-2
    - 항목 1-2
- 항목 2
- 항목 3

순서가 있는 목록은 1. 을 사용하여 씁니다.
1. 항목 1
    1. 항목 1-1
        1. 항목 1-1-1
        1. 항목 1-1-2
    1. 항목 1-2
1. 항목 2
1. 항목 3


### 2.3 수평선
*** 를 사용하면 수평선을 그을 수 있습니다.
***

### 2.4 인용문
인용문은 > 기호를 사용합니다.
> 인용1
>> 인용2
>>> 인용3

- 사용 예시
> Life is short, You need Python.


### 2.5 링크
링크를 작성할 떄는 [링크 내용](링크주소\)의 형태로 작성합니다.

- 사용 예시
이 설명에 대한 자세한 내용은 다음 [링크](https://www.google.com) 

### 2.6 프로그래밍 코드
마크다운에서 프로그래밍 코드는 \`\`\` 로 시작해서 \`\`\` 로 끝나도록 합니다.
처음 \`\`\` 다음에 언어를 써주게 되면 문법 특이적으로 마크다운 뷰어에서 syntax를 highlight 해줍니다.

- Python 예시
```python
def my_function(name: str) -> None:
    print(f"hello {name}")
```

- LINUX shell 예시
```shell
for name in `cat list.txt`
do
    echo "sample ${name}"
done
```

### 2.7 그림
마크다운에서 그림은 ![image]\(그림 주소) 와 같이 넣습니다.

![image](https://i.namu.wiki/i/d8OOKRzCFLYZROlaDMbne86g_uFmj-0zMAKDGlNVmZEj1o0uK8_j4zwTKo29wRgHqqLYZ6RpP7f1QJoZm_6HCA.webp)

### 2.8 테이블
마크다운에서 표는 다음과 같이 만듭니다.

|제목|내용|설명|
|------|---|---|
|테스트1|테스트2|테스트3|
|테스트1|테스트2|테스트3|
|테스트1|테스트2|테스트3|

### 2.9 수학 수식
$2\times3=6$
${2}^{3}=8$
${log}_{10}2=0.3010$
$\frac{1}{2}=0.5$
$\sqrt2=1.414$

수학 수식 참고 문헌 [링크](https://ko.wikipedia.org/wiki/%EC%9C%84%ED%82%A4%EB%B0%B1%EA%B3%BC:TeX_%EB%AC%B8%EB%B2%95)
