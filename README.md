# SemicolonF-ck
Brainf*ck를 응용하여, 세미콜론과 그리스어 물음표만을 이용할 것입니다.

언어 설명 : 기존 Brainf*ck 코드를 짜는 것과 비슷합니다.
개발자를 화나게 하는 방법에서 아이디어를 따왔습니다.

규칙은 다음과 같습니다.

1.이 언어는 ;과 ;를 구분합니다.이때, 첫 번째 ;는 세미콜론, 두 번째 ;는 그리스어 물음표입니다.설명에는 가독성을 위해, ;는 ;로, ;는 : 로 표시하겠습니다.

2.그 외의 글자가 들어간 부분은 무시됩니다.

3.이 언어는 모든 코드를 3글자 단위로 쪼갭니다.이때, 3글자 단위는 하나의 2진수가 됩니다.; 는 0, : 는 1입니다.

4.3번의 예시로, ;:; (;;;)는 010, :::는 111, ;;;는 000이 됩니다.

5.변환된 이진수는 각각 매핑되어, 다음과 같이 변환됩니다.

```
000 => >
001 => <
010 => +
011 => -
100 => .
101 => ,
110 => [
111 => ]
```

예를 들어, ;;;는 000, 즉, >로 변환되고, ::;는 110, 즉, [로 변환됩니다.

코드상으로는 ;;;::;은 >[이 되는 것입니다.

6.이렇게 변환된 코드를 Brainf*ck로 실행합니다.

다음은, Hello, World!를 출력하는 예제입니다.
```
;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;
```

온라인 HTML 페이지로 임시로 인터프리터를 구현하였습니다.주소는 다음과 같습니다.

https://sihyeonlove.github.io/SemicolonF-ck/SemicolonHell

그냥 할 짓 없어서 했습니다 예...감사합니다.
