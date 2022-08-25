# 데이터 수정 및 삭제 페이지 만들기


## 실행화면
![image](https://user-images.githubusercontent.com/93521131/186558766-edc7221e-f761-4e09-a360-43a59e2c6a5f.png)


## 코드 리뷰 

![제목 없음](https://user-images.githubusercontent.com/93521131/186558912-d7317d37-c5d1-4cc8-86cb-aed400743f4e.png)

먼저 빨간 색 으로 표시 되어 있는 부분을 만들어 준다. 보기는 빨간색으로 표시되어 있는 부분을 만들기 위한 html 코드이다.

![image](https://user-images.githubusercontent.com/93521131/186559161-5452a285-61f8-4eb4-b051-9fdf065a93a7.png)

만든 후에 데이터가 들어가야 하는 부분의 테이블을 만들어주어야한다. 데이터가 들어가야 하는 부분은 이부분이다.

![제목 없음2](https://user-images.githubusercontent.com/93521131/186559414-facd6b3b-d987-4a88-a8c6-12852272998f.png)

보기와 같이 테이블의 길이를 정해주어 웹페이지에 보여주면 간단하지만, 데이터의 양을 초과하면 더이상 추가가 안되므로, 데이터의 갯수에 따라
테이블의 길이가 가변적으로 바뀔 수 있게 해주기 위해, 보기 와 같이 코드를 작성해  주었다.
![image](https://user-images.githubusercontent.com/93521131/186559827-b23bd69c-9fac-4a56-840a-69ed47fd84d5.png)

보기는 jsp 로 작성한 코드인데, while문 안에 next() 메소드는 DB(데이터베이스)의 다음 순서에 있는 데이터를 뜻한다. 즉 DB안에 데이터의 다음 순서가 있으면
true 이지만 마지막 순서가 되면 while문의 조건의 false가 되므로, table 생성을 종료하는 형식의 jsp코드이다.  

![image](https://user-images.githubusercontent.com/93521131/186560514-5923f810-b166-486c-a1fa-d50dedb84fde.png)

앞에서 설명한 웹페이지의 테이블을 생성하기전, DB안에 있는 데이터를 가져온것이다.

![image](https://user-images.githubusercontent.com/93521131/186560865-2eb75cb6-e933-42dd-b059-e12b451c1597.png)

<td>태그 안에서 가져올 데이터 가 String인 이유가  sql을 가져올 때 String으로 선언해주었기 때문이다.

실행화면은 맨처음에 설명하였으므로, 이상 설명을 마치겠다.






