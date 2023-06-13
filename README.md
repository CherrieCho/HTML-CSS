## Input 태그에서 name, id, value 속성의 차이 정리

1. **Input id**: *label for*랑 연결지어서 label을 클릭할 때 둘 다 활성화 될 수 있도록 한다.<br><br>
2. **Input name**: 데이터가 서버로 전송될 때를 고려하여 그 특정 인풋태그의 *데이터를 지칭*하기 위한 변수 지정 용도로 사용된다. <br> **input type radio** 에서 name 속성은 옵션들이 같은 그룹 내에 묶일 수 있도록 한다.<br><br>
4. **Input value**: 표시되어있는 *디폴트 값*을 말한다. **input type radio** 나 **option** 태그의 경우 서버로 *실제로 넘겨질 값*을 말한다.
*****

The value attribute of the input tag is always optional, but ***considered mandatory for input type checkbox, radio and hidden.***
