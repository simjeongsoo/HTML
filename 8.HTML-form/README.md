## HTML form
* 사용자가 입력한 데이터(입력값)를 서버(정보를 제공하는 호스트)로 보내기 위해 사용하는 태그
* 서버와 클라이언트에 대한 이해도 필요  
```
<form>
	<input type=“text” placeholder=“id”>
	<br>
	<input type=“text” placeholder=“password”>
	<br>
        <input type="submit" value="login">
</form>
```  
-> login 버튼을 누르면 입력된 아이디와 비밀번호가 서버로 전송되고(요청),  
서버 측에서 데이터를 처리한 결과를 클라이언트에게 보내준다(응답)  
<br/>
* Form 의 속성  
action : 입력값을 전송할 서버의 url  
method : 클라이언트가 입력한 데이터를 어떤 식으로 전송할지( GET or POST )  
`<form action=“example.php” method=“POST”></form>`  
-> example.php 라는 서버 프로그램으로 입력값을 전송하여 요청할것  
-> POST 방식으로 전송 할 것   

——————————————————————————————---------------------------------------------------------———————————
GET : 서버에 요청을 보내어 응답을 받아냄   
POST : 서버에 요청을 보내어 작업을 수행 / 서버에있는 데이터를 추가,수정,삭제 한 후에 응답을 받아냄  
