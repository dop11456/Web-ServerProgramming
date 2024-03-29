<%@ page language="java" contentType="text/html; charset=UTF-8"
    pageEncoding="UTF-8"%>
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Insert title here</title>
</head>
<body>
	<div align="center"></div>
	<table border="1" width="550" height="300">
		<tr align="center">
			<td>이름</td>
			<td> <input type = "text" name= "txtName"  size ="10"></td>
		</tr>
		<tr align="center">
			<td>폰번호</td>
			<td> <input type = "text" name= "txtPhone"  size ="15"></td>
		</tr>
		<tr align="center">
			<td>메일</td>
			<td> <input type = "text" name= "txtMail"  size ="30"></td>
		</tr>
		<tr align="center">
			<td>주소</td>
			<td> <input type = "text"name= "txtAddress"  size ="50"></td>
		</tr>
		<tr align="center">				
				<td colspan="2">
					<button type="submit">저장</button>
					<button type="reset">취소</button>
				</td>	
			</table>
			<nav>
	<ul>
		<li><a href="index.jsp">홈으로</a><li>
	</ul>
</nav>			
</body>
</html>

<%@ page language="java" contentType="text/html; charset=UTF-8"
    pageEncoding="UTF-8"%>
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Insert title here</title>
</head>
<body>
	<div align="center"></div>
	<table border="1" width="800" height="300">
		<tr>
			<th width="15%">이름 </th>
			<th width="20%">폰번호 </th>
			<th width="25%">이메일 </th>
			<th width="40%">주소 </th>
		</tr>
		<tr align="center">
			<td>손희창</td>
			<td>010-8033-9178</td>
			<td>dop11456@naver.com</td>
			<td>부산시 금정구 구서중앙로 52 우성아파트 6동 301호</td>
		</tr>
		<tr align="center">
			<td>홍길동</td>
			<td>010-1111-1111</td>
			<td> gdhong@gmail.com</td>
			<td>서울시 강남구 가야로 349번길 24 밀가든아파트</td>
		</tr>				
	</table>
	<nav>
	<ul>
		<li><a href="index.jsp">홈으로</a><li>
	</ul>
</nav>
</body>
</html>
<%@ page language="java" contentType="text/html; charset=UTF-8"
    pageEncoding="UTF-8"%>
<!DOCTYPE html>
<html>
<%
String str1="손희창";
String str2="안녕하세요";
%>
<meta charset="UTF-8">
<title>Insert title here</title>
<body>
<nav>
	<ul>
		<li><a href="input.jsp">명함입력</a><li>
		<li><a href="serch.jsp">명함검색</a><li>
		<li><a href="index.jsp">홈으로</a><li>
	</ul>
</nav>
<h2>처음 만들어보는 <%= str1 %></h2>
		<p>
		<%
		out.println(str2+str1+"입니다. 열공합시다. 010-8033-9718");
		%>
		</p>	
</body>
</html>
