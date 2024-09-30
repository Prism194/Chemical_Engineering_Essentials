I\. X-ray diffraction(X-ray 회절)
1\. X-ray diffraction
- 빛을 회절시키기 위해서는, diffraction granting spacing(회절격자 간격, spacing between planes)이 빛의 파장과 비슷해야 한다.
- X-ray들은 원자의 평면(planes of atoms)에 의해 회절된다
- interplanar spacing(평면 간 간격) : 원자의 평행한 평면 사이 거리
2\. X-rays to determine crystal structure
- 결정형 평면들은 incoming X-ray들을 회절시킨다
![[Pasted image 20240930191904.png]]![[Pasted image 20240930192051.png]]
- 회절은 $\theta=\theta_{c}$일 때 일어난다
- 회절각 $\theta_{c}$를 측정하여 interplanar spacing d를 결정한다 -> 공식 참조

II. The identification of lattice planes
1\. Point coordinates(점 좌표)
![[Pasted image 20240930192433.png|150]]![[Pasted image 20240930192926.png|350]]
1\) 정의
- 정의 : 단위 셀 안에서의 격자 위치
- 단위 셀 edge length a, b, c의 부분 배수로 결정됩니다
2\) 구하는 법(e.g. unit cell upper corner, 위 그림)
- 1. 격자 포지션 : a, b, c
- 2. unit cell edge length(a,b,c)로 나누고 comma 삭제
	->$\frac{a}{a}\frac{b}{b}\frac{c}{c}=111$
- 3. unit cell corner의 점 좌표 -> 111

2\. Crystallographic Directions(결정학적 방향)
1\) 정의
- ㅁㅁㅁ
2\) 구하는 법(예시 참조)
![[Pasted image 20240930193217.png|150]]![[Pasted image 20240930193826.png|400]]
- 1. vector tail, vector head의 coordinates(좌표)를 결정
	위 경우, vector tail은 $x_1=0,y_1=0,z_1=0$
	vector head는 $x_1=a,y_1=0,z_1=c/2$
- 2. tail point 좌표를 head point 좌표로 뺀다
- 3. 좌표 간의 차를 격자 parameter a, b, c로 normalize : ($\frac{a-0}{a},\frac{0-0}{b},\frac{\frac{c}{2}-0}{c}$)
- 4. 최소 정수 값으로 맞추기 : 1, 0, 1/2 -> 2, 0, 1
- 5. comma를 빼고, square bracket으로 감싸기 : 2, 0, 1 -> \[2 0 1]
3\) 또다른 예시
![[Pasted image 20240930193934.png|150]]
- 1. Point coordinates of tail and head
	vector tail : $x_1=a,y_1=\frac{b}{2},z_1=0$
	vector head : $x_2=-a,y_2=b,z_2=c$
- 2 & 3. substract and normalize
	$\frac{-a-a}{a}=-2,\frac{b-\frac{b}{2}}{b}=\frac12,\frac{c-0}{c}=1$
	=> -2, 1/2, 1
- 4 & 5. in this case, multiply by 2 to eliminate the fraction, then place in square brackets(no commas)
	-4,1,2 =>\[$\bar{4} 1 2$]
- cf. overbar -> 음수 표현

4\) Family of directions
![[Pasted image 20240930195241.png]]
- 정의 : <font color="#003380"><strong>결정학적으로</strong></font> 동등한 모든 방향(원자 간 간격이 동일)
- 표기 : angle bracket(<>)안의 인덱스로 표시
- e.g. <100> : \[100], \[010], \[001], \[$\bar{1}00$], \[$0\bar{1}0$], \[$00\bar{1}$], 위 그림에서도 보이듯이, 원점에서 1만큼 거리가 떨어져 있는 격자점들을 모두 나타낸
- 