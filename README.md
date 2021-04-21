# 3Dbutton
FlipButton

![플립박스](https://user-images.githubusercontent.com/69416518/115511868-4f204b80-a2bc-11eb-85f7-238c2495fcec.JPG)



perspective: 1000px; 
/* 값이 작으면 원근감이 가까워지고 크면 멀어짐 주로 최상위 태그에 설정*/


transform-style: preserve-3d; 
/* 3D 공간배치 x,y에 추가로 z축 생성 */

transform: rotateX(90deg) translateZ(150px); 
/* deg = degree(각도), Z축은 X축과 Y축의 교점을 기준으로 수직을 유지하기 때문에 X,Y기울기에 따라 Z축으 기울기도 바뀜 */
/* 첫번째 버튼 중 back면을 x축을 기준으로 90도로 눕힌 뒤, Z축을 이용해 배치를 front면 위쪽으로 이동을 시켜 옆에서 봤을 때 T 모양으로 형성되도록 함*/


transform: translateZ(50px);
/* T모양으로 있는 것을 박스모양(ㄱ자)으로 만들기 위해 front를 50px만큼 사용자 기준 화면쪽으로 이동시킴 */
