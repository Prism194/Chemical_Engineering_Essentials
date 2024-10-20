I\. X-ray diffraction(X-ray 회절)
1\. X-ray diffraction
- 빛을 회절시키기 위해서는, diffraction granting spacing(회절격자 간격, spacing between planes)이 빛의 파장과 비슷해야 한다. 즉 d값이 X-ray 파장과 유사해서 X-ray를 쓴다.
- X-ray들은 원자의 평면(planes of atoms)에 의해 회절된다 -> atom plane의 구조 파악 가능
- interplanar spacing(평면 간 간격) : 원자의 평행한 평면 사이 거리
2\. X-rays to determine crystal structure
- 결정형 평면들은 incoming X-ray들을 회절시킨다
![[Pasted image 20240930191904.png]]![[Pasted image 20240930192051.png]]
- 첫 번째 그림에서, 1번 X-ray와 2번 X-ray의 차이는 purple line만큼이다. 이 값은 $2d\sin\theta$ , 이것이 파장과 비례하면 X-ray들이 2번째 그림처럼 회절되었다고 볼 수 있다.
- 특정 각도에서에서 회절이 일어나서($\theta_{c}$값을 통해) d값을 계산할 수 있다.
- 회절은 $\theta=\theta_{c}$일 때 일어난다
- 회절각 $\theta_{c}$를 측정하여 interplanar spacing d를 결정한다 -> 공식 참조
- e.g. Fe(BCC)($\alpha-iron$(BCC))의 경우, XRD 분석 결과 (110) plane, (200) plane, (211) plane을 가짐 -> 이들을 파악하면 Fe(BCC)임을 파악 가능
II. The identification of lattice planes
1\. Point coordinates(점 좌표)
![[Pasted image 20240930192433.png|150]]![[Pasted image 20240930192926.png|350]]
1\) 정의
- 정의 : 단위 셀 안에서의 lattice position(사실상 점의 위치)
- 단위 셀 edge length a, b, c의 부분 배수로 결정
2\) 구하는 법(e.g. unit cell upper corner, 위 그림)
- 1. 격자 포지션 : a, b, c
- 2. unit cell edge length(a,b,c)로 나누고 comma 삭제
	->$\frac{a}{a}\frac{b}{b}\frac{c}{c}=111$
- 3. unit cell corner의 점 좌표 -> 111
3\) 예시
- a 0 0 -> a/a, 0/b, 0/c -> 1 0 0
- a/2 b c -> a/2 /a , b/b c/c -> 1/2, 1, 1 ...
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
- 가장 오른쪽 검은 사각형 예시 : 0 b c/2 -> 0/a b/b (c/2)/c \[0 1 1/2] -> \[0 2 1]
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

3\.  Family of directions
![[Pasted image 20240930195241.png]]
1\) 정의 : <font color="#003380"><strong>결정학적으로</strong></font> 동등한 모든 방향들(원자 간 간격이 동일한 점들)
	-> crystal lattice에서 대칭적적으로 동등하다는 것을 의미한다. 즉, 그 방향들을 돌리고 뒤집으면 같은 방향이 될 수 있다는 것이다
	-> 격자가 대칭적으로 이루어졌기에, 동등한 방향들은 같은 원자 간 간격을 가질 것이다. 따라서  원자 간 간격이 동일 점들은 결정학적으로 동등한 모든 방향을 나타낼 수 있다
	-> 그렇다면, 모든 원자 간 간격이 동일한 점들은 결정학적으로 동등한 것인가?
2\) 표기 : angle bracket(<>)안의 인덱스로 표시
- e.g. <100> : \[100], \[010], \[001], \[$\bar{1}00$], \[$0\bar{1}0$], \[$00\bar{1}$], 위 그림에서도 보이듯이, 결정학적으로 동등한 모든 방향(원자 간 간격이 동일)들을 찾을 수 있다. 나머지 예시도 마찬가지(위 그림은 모든 예시를 다 넣은 것이 아니니 주의)
 ![[Pasted image 20240930200521.png|300]]
- <100>은 6개, \<110>은 12개, \<111>은 8개의 서로 다른 방향들이 각각의 family에 속해있다

4\. <font color="#003380"><strong>Crystallographic Planes</strong></font> -> 중요!
1\) Miller indices(밀러 인덱스)
- 정의 : 밀러 지수는 평면이 결정학적 x, y, z축과 만나는 절편의 역수이다. 이 축들은 cubic unit cell의 평행하지 않은 세 개의 모서리(edge)에 해당한다.
- 목적 : 구체적인 결정 평면을 알아내기 위해서
2\) 구하는 법
- 1. 평면이 선택된 원점을 지날 때는 다른 unit cell에 새로운 원점 잡기(점으로 만나는 것 뿐 아니라 면이 가로질러가더라도) -> 왜냐하면 intercept를 구하기가 어렵기 때문, 대부분 문제는 통과 x
- 2. 평면이 x, y, z 축들과 만나는 절편값 읽기
- 3. 절편의 역수(reciprocal) 취하기
- 4. lattice parameter a, b, c를 각각 곱해서 절편의 역수값을 normalize(정규화)하기
- 5. 정수값으로 축소
- 6. 구해진 Miller indices들을 소괄호로 감싸고, 콤마는 쓰지 않기
3\) 문제 예시들
![[Pasted image 20240930201643.png|]]
- z축과의 교점은 없다(무한대 처리)
![[Pasted image 20240930201756.png]]
![[Pasted image 20240930201824.png]]
- 3번째 경우 풀이
- 1. Relocate origin - 필요 없음
- 2. 절편 : a/2, b, 3c/4
- 3. 역수 : 2/a, 1/b, 4/3c
- 4. 정규화 : 2, 1, 4/3
- 5. reduction : 6, 3, 4
- 6. Miller indices : (6 3 4)

4\) crystallographic plane들의 예시들(연습하기)
![[Pasted image 20240930202138.png]]
- 회색 삼각형 예시
- a/2, b/2 c -> 2/a, 2/b, 1/c -> 2 2 1 -> (221)
5\) cubic system에서 (hkl)과 \[hkl]의 관계
![[Pasted image 20240930202242.png|300]]
- [hkl] 방향과 (hkl) 방향은 서로 수직
- cubic crystal에 대해서, <font color="#003380"><strong>같은 인덱스값을 가지고 있는 plane과 direction은 서로 수직이다</strong></font>.
6\) 표기법 정리
- point coordinates : a b c
- directions : \[a b c]
- planes : (a b c)

5\. Hexagonal unit cells에서 Miller indices를 구하자
1\) 예제 :  a1, a2, a3 z축에서의 절편을 구하고, Miller indice를 구하라
![[Pasted image 20240930202614.png]]
- 유사한 방법으로 해결 가능하다, origin 지나는 건 고려 안해도 됨
2\) 예시들(연습하기)
- a1, a2, z축에서의 절편을 구하고, Miller indice를 구하라
![[Pasted image 20240930202741.png|400]]
- 첫 번째 : a, a, -a/2, c -> 1/a, 1/a, -2/a, 1/c -> 1 1 -1 1 -> ($11\bar{2}1$)

III. Neighboring planes & Interplanar spacing
1\. Crystallographic planes
1\) Family of directions
- 정의 : 결정학적으로 동등한 방향들(같은 atomic spacing을 가진 것들)
- e.g. <100> : \[100], \[010], \[001], \[$\bar{1}00$], \[$0\bar{1}0$], \[$00\bar{1}$]
2\) Family of planes(curly bracket{}으로 표시)
![[Screenshot from 2024-09-30 20-33-03.png]]
- 정의 : 결정학적으로 동등한 평면들(같은 atomic packing을 가진 것들, property가 동일함)
- e.g. {100} : (100), (010), (001), ($\bar{1}00$), ($0\bar{1}0$), ($00\bar{1}$)

2\. The neighboring planes
![[Pasted image 20240930212334.png|300]]
- 면들은 무한대로 계속해서 중첩돼 있을 것
- index 0 : plane이 해당하는 축과 평행하다는 것을 의미,
- indexing은 non-orthogonal axes(직각이 아닌)에 대해서도 성립
![[Pasted image 20240930203701.png]]
(a)
- 무한대, 무한대, c -> 0 0 1/c -> 0 0 1, 나머지들도 다 (001) plane들이다
plane들이 무한히 반복된다

3\. separation of neighboring planes
1\) 평면의 반복 -> 평면 사이의 간격을 알고 싶다(cubic lattice에서)
- cubic lattice가정(모두 다 a)
![[Pasted image 20240930212949.png|300]]
- (h k 0) plane일 때 cross section이 a/h, a/k임을 이해해야 한다
- 위 그림에서 유도된 대로, a/h, a/k 라고 뒀을 때, 자연스럽게 (hk0) 평면이 형성된다.
- d spacing 값을 구하기 위해서, $\sin^2\theta+\cos^2\theta=1$관계를 사용할 것
- $\sin\theta=\frac{d_{hk0}}{\left(\frac{a}{h}\right)}=\frac{hd_{hk0}}{a},\cos\theta=\frac{d_{hk0}}{\left(\frac{a}{k}\right)}=\frac{kd_{hk0}}{a}$
- $\left(\frac{hd}{a}\right)^2+\left(\frac{kd}{a}\right)^2=1$
- 양변을 d제곱으로 나누면, $\frac{1}{d_{hkl}^2}=\frac{h^2+k^2}{a^2},d_{hkl}=\frac{a}{\left(h^2+k^2\right)^{\frac12}}$(편의상 일부 아래첨자들은 생략함, 실제로는 $d_{hkl}$로 쓰기)
- 이를 3차원으로 일반화하면, $\frac{1}{d_{hkl}^2}=\frac{h^2+k^2+l^2}{a^2},d_{hkl}=\frac{a}{\left(h^2+k^{^2}+l^2\right)^{\frac12}}$
2\) d spacing 구하는 공식
- orthonombic(각도는 다 90도, 길이가 다 다름)의 경우
<<<<<<< HEAD
- $\frac{1}{d^2}=\frac{h^2}{a^2}+\frac{k^2}{b^2}+\frac{l^2}{c^2}$ 

copper 예시
- FCC -> cubic이다
- 220을 줬으니까 그냥 대입해서 풀면 끝난다
- a/2, a/2, $\infty$ -> 2/a 2/a 0 -> 2 2 0
=======
- $\frac{1}{d_{hkl}^2}=\frac{h^2}{a^2}+\frac{k^2}{b^2}+\frac{l^2}{c^2}$
- 책에 있는 예제 확인

IV. X-ray diffraction theory
1\. X-ray
1\) X-ray의 역사
- 1895년 뢴트겐에 의해 발견
- 1912년 짧은 파장을 가진 전자기파임을 밝혀냄
2\) X-ray의 특징
- X-ray : 고에너지 전자기파 -> 서로 다른 정도로 물질 통과 가능
- 생성 : 고속의 전자들이 물질과 충돌하면서, 짧은 파장의 전자기파를 만들어냄
- 효과 : 회절, 반사, 투과(transmission), 이온화, 형광
- 파장대 : $10^{-11}-10^{-8}m$(0.1-100 옹스트롬)
3\) X-ray와 초음파의 비교
- X-ray
- 물질마다 X-ray 흡수 정도가 다르다
	e.g. 뼈 안의 칼슘은 높은 밀도와 원자번호를 가지고 있어서 상대적으로 X-ray 흡수가 잘 된다, 그래서 뼈들은 하얗게 보이고, 지방과 기타 조직들은 회색으로 보임
- 고에너지 radiation 주의
- 고밀도의 구조들을 시각화하는 데 사용되었다(뼈, 폐, 치아 등)

- 초음파
- 높은 진동수의 초음파는 전파 및 되돌아오는 현상을 통해서 조직의 구조를 파악한다
- 무해한 음파 -> 임산부와 어린이들에게 사용하기 적합
- pregnancy scans, 장기 검사, 심장박동, 혈액 흐름 등 파악하는 데 사용

- 기본적으로 X-ray와 초음파는 진동수부터 다르다

2\. X-ray Diffraction(회절)
1\) X-ray 회절
![[Pasted image 20241011143301.png|400]]![[Pasted image 20241011143505.png|300]]
- 평면파들이 장애물과 상호작용하면서 curved wave가 된다. 이때, curved wave의 형태를 역추적하면 장애물의 구조를 알 수 있다
	e.g. 빛의 간섭 패턴을 통해서 slit 간의 거리를 알 수 있다
- X-ray의 경우, cryatal 과 X-ray가 상호작용하면서 나타난 diffracted pattern(회절 패턴)을 관찰하여 원 물질을 재구성할 수 있다
2\) X-ray의 여러 변환 과정