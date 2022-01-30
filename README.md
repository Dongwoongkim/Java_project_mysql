# Java_project_mysql

### 🎈 프로젝트 주제 
######  데이터베이스 관리시스템인 MySQL에 접근하여 데이터베이스를 추가, 삭제, 조회할 수 있는 자바 프로그램 

### ✅  코드 개요 

1. GUI구성 코드 (StudentGUI.java) - 프레임 생성
![image](https://user-images.githubusercontent.com/86222503/151692943-069663de-0fca-473e-984b-faed55f251a3.png)


![image](https://user-images.githubusercontent.com/86222503/151692945-a4cb4c13-adda-49ce-80d6-75f114e364b3.png)




- 다음과 같이 setTitle()을 통해 프로그램 제목을 ‘IT정보공학과 JAVA 객체지향프로그래밍 학생 관리 프로그램’으로 지정했고 SetBounds()를 통해 가로,세로 위치 및 크기조정을 했다.
- SetDefaultCloseOperation() 메소드를 이용해 윈도우 창 종료시 프로세스까지 깔끔하게 종료할 수 있도록 설계하였다.

2. GUI구성 코드 (StudentGUI.java) - 입력 패널 생성

![image](https://user-images.githubusercontent.com/86222503/151692979-80e918c1-e905-484a-915c-ee2c506e5036.png)


















-  상단 데이터베이스 정보 입력 패널과 하단에 DB정보 입력 패널을 JPanel을 통해 만들어 추가하였다.

3. GUI구성 코드 (StudentGUI.java) - 하단 기능 버튼 패널 생성
 









- 하단에 DB에 대한 데이터 추가, 수정, 삭제, 조회를 할 수 있는 버튼 패널을 JButton을 사용하여 구현하였다.  


4. GUI구성 코드 (StudentGUI.java) - 정보출력 패널 생성




- 중앙영역에 table을 생성하여 vector를 사용하여 컬럼명을 설정하였다.
- isCellEditable 이라는 부분은 테이블을 직접 수정할수 없게 막아둔 부분이다.

---------------------------------------------------------------------------------------

- StudentDB.java

1. DB와 Eclipse 연결 – getConnection() 메소드



- 이클립스에서 미리 구축한 MySQl의 DB에 접근할수 있도록 getConnection() 메소드를 정의하였다.




 
            String driver = DB 연결할 때 사용할 드라이버 정보
            String url = 접속할 DB 서버
            String user = MySQL 아이디
            String password = MySQL 비밀번호


2. Eclipse를 통해 MySQL로그인 Login() 메소드 / StudentDB.java













- login() 메소드
DB내에 테이블을 통해 생성한 데이터의 정보 (이름 및 비밀번호 )를 통해 Login 할 수 있는 메소드를 정의하였다.

3. Eclipse를 통해 MySQL에 데이터 삽입 insert() 메소드 /StudentDB.java












- insert()메소드
Login을 하면 MySQL에 생성한 데이터베이스에 접근을 할 수 있다.
insert()메소드를 통해 MySQL에 생성한 데이터베이스에 데이터를 추가할 수 있다.








4. Eclipse를 통해 MySQL에 데이터 삽입 delete() 메소드 /StudentDB.java


















- delete()메소드
Login을 하면 MySQL에 생성한 데이터베이스에 접근을 할 수 있다.
delete()메소드를 통해 MySQL에 존재하는 데이터베이스의 데이터를 삭제할 수 있다.


5. Eclipse를 통해 MySQL에 데이터 수정 correct(() 메소드 /StudentDB.java












- correct() 메소드
Login을 하면 MySQL에 생성한 데이터베이스에 접근을 할 수 있다.
correct()메소드를 통해 MySQL에 존재하는 데이터베이스의 데이터를 수정할 수 있다.



### ✅ 프로그램 설명 






















### ✅ 프로젝트 최종결과물 


