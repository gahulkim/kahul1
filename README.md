# kahul1
<!doctype html>
<html lang="ko">
<head>
	<title>온라인 프로필</title>
	<meta charset="utf-8">
  <link rel="stylesheet" href="css/style.css">
  <style>
    table {
      width:70%;  /* 표의 너비 */
      border:1px solid #222; /* 1픽셀짜리 표 테두리 */
      border-collapse: collapse; /* 중복되는 표와 셀의 테두리를 한 줄로 표시 */
    }
    thead {
      background:#eee;  /* 제목 행의 배경 색 */
    }
    th, td {
      border:1px solid #ccc; /* 1픽셀짜리 셀 테두리 */
      padding:5px;  /* 셀 테두리와 셀 내용 사이의 여백(패딩) */
      font-size:0.8em;  /* 셀의 글자 크기 */
    }
  </style>
</head>

<body>
    <div id="container">
        <!-- 사이드바 -->
        <aside>
            <div id="namecard">
                <img src="images/pf.jpg" alt="">
                <h1>gahul kim</h1>    
                <p>오늘은 남은 인생이 시작되는 첫째날</p>
            </div>
            <div id="detail">
                <p>Yeonggwang, Korea</p>
                <p>rkgml4419@gmail.com</p>                                 
            </div>
            <div id="sns">
                <h2>SNS</h2>
                <ul>                    
					<li>
						<a href="https://www.github.com/">github</a>
					</li>
					<li>
						<a href="https://www.google.com/search?q">google</a>
					</li>
				</ul>
            </div>           
        </aside>
        <div id="main">
            <!-- 자기 소개 -->
            <section>
                <h2 class="subtitle">Who am I?</h2>
                <p><mark>저는 컴퓨터</mark>에 관심이 많습니다. <br>현재 영광의 영광공고에서 공부중입니다.</p>
            </section>

            <!-- 경력 -->
            <section>
                <h2 class="subtitle">Experience</h2>
                <ul>
                    <li>제과제빵
                        <ul>
                            <li>제과와 제빵</li>
                            <li>수업 시간</li>
                        </ul>
                    </li>
                    <li>푸드 스타일링
                        <ul>
                            <li>조형감각 높히기 </li>
                            <li>미술적, 예술적 감각</li>
                        </ul>                        
                    </li>
                </ul>             
            </section>

            <!-- 숙련도 -->
            <section>
                <h2 class="subtitle">Skills</h2>

            </section>

            <!-- 학력 -->
            <section>
                <h2 class="subtitle">Education</h2>
                <table>
                  <caption>시간표</caption>
                  <thead>
                      <tr>
                        <th>월</th>
                        <th>화</th>
                        <th>수</th>
                        <th>목</th>
                        <th>금</th>
                      </tr>
                  </thead>
                  <tbody>
                      <tr>
                        <th>자율</th>
                        <th>국어</th>
                        <th>성공</th>
                        <th>음악</th>
                        <th>음악</th>
                      </tr>
                      <tr>
                        <th>진로</th>
                        <th>체육</th>
                        <th>통과</th>
                        <th>통사</th>
                        <th>식과</th>
                      </tr>
                      <tr>
                        <th>국어</th>
                        <th>영어</th>
                        <th>국어</th>
                        <th>통과</th>
                        <th>성공</th>
                      <tr>
                        <th>식과</th>
                        <th>통사</th>
                        <th>수학</th>
                        <th>체육</th>
                        <th>수학</th>
                      </tr>
                      <tr>
                        <th>통과</th>
                        <th>식위</th>
                        <th>음악</th>
                        <th>동아리</th>
                        <th>통사</th>
                      </tr>
                      <tr>
                        <th>영어</th>
                        <th>성공</th>
                        <th>영어</th>
                        <th>동아리</th>
                        <th>식위</th>
                      <tr>
                        <th>수학</th>
                        <th>식과</th>
                        <th>식위</th>
                        <th>방과후</th>
                        <th>보건</th>
                          </tr>
                      </tr>
                      </tr>
                  </tbody>
                </table>
            </section>
        </div>        
    </div>
</body>
</html>
