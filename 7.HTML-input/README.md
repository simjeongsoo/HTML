## HTML 입력요소

### Input 태그 
* 사용자로부터 값을 입력받을 수 있는 대화형 컨트롤(or ‘필드’)을 나나탬
* 인라인요소, 단일태그 
* 20여 가지 타입  
`<input />`  
type
1. Default = text 입력  
2. 체크박스  
3. 날짜입력  
4. 색상선택  
5. 버튼  
6. 숫자입력창  

- name 식별자 추가 가능 -> 각각의 입력 항목에 대한 이름  
`<input type=“text” name=“nickname” />`  

- Placeholder -> 안내메시지
- Maxlength 
- Button value
- range max min step 

### Select 
- 다수의 옵션(선택지)을 포함할 수 있는 선택 메뉴
- 메뉴 안에 포함되는 옵션은 option 태그를 사용해 표시 
- 인라인 요소
- Value 값을 이용하여 자바스크립트를 통한 입력값 처리 
- multiple 요소 추가 가능 
- selected  
```
<select name="select" id="select" multiple>
    <option selected value="value1">value1</option>
    <option value="value2">value2</option>
    <option value="value3">value3</option>
    <option value="value4">value4</option>
    <option value="value5">value5</option>
</select>
```

### Textarea
- 여러 줄의 일반 텍스트를 입력할 수 있는 입력요소
- name 속성 추가 가능 
- 인라인 요소  
`<textarea name=“letter”></textarea>`
