# Postman-study

# HttpRequest를 통해 데이터를 전달하는 방법
> GET 방식의 Query Parameter
>> URL 뒤에 "?name=hansu&addr=seoul" 방식으로 전달 <br>
>> message body 없이 URL 쿼리 파라미터에 데이터 전달 <br>
>> header의 content-type이 null <br>

>POST 방식의 HTML Form
>> Header의 content-type이 application/x-www-form-urlencoded <br>
>> message body에 쿼리 파라미터 형식으로 전달 name=hansu&addr=seoul <br>
>> GET의 Query Parameter 방식과 포맷이 같기 때문에 HttpServletRequest.getParameter 를 통해 똑같이 접근할 수 있다. <br>
> - list Data 보낼때 : Parameter들을 body > application/x-www-form-urlencoded에 담아서 보내면 된다.
>> 그러면, HttpServletRequest.getParameter을 통해 데이터를 꺼낼 수 있기 때문이다.

