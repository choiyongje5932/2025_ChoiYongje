# 2025_ChoiYongje
2025년 프로그래밍언어활용 1학기

#202210929 소프트웨어학부-컴퓨터소프트웨어전공 최용제

<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>자기소개</title>
</head>
<body>
    <h1>안녕하세요!</h1>
    <p>저는 <span id="name">홍길동</span>입니다.</p>
    <p>나이는 <span id="age">30</span>살이고, 직업은 <span id="occupation">소프트웨어 개발자</span>입니다.</p>
    <p>저의 취미는 <span id="hobby">독서</span>입니다.</p>

    <button onclick="updateIntroduction()">자기소개 수정</button>

    <script>
        function updateIntroduction() {
            document.getElementById("name").innerText = prompt("이름을 입력하세요:");
            document.getElementById("age").innerText = prompt("나이를 입력하세요:");
            document.getElementById("occupation").innerText = prompt("직업을 입력하세요:");
            document.getElementById("hobby").innerText = prompt("취미를 입력하세요:");
        }
    </script>
</body>
</html>
