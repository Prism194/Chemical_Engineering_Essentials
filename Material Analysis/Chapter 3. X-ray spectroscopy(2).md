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
![[Pasted image 20241020215226.png|300]]
- X-ray의 변환 종류scatter(산란, 우리는 이 경우에 주목, 여기서 회절하는 것 찾기), fluorescene(형광), transmit(전달(통과)), thermal energy로 변환 가능
- 회절하는 경우 : 회절 각도와 해당 광선의 강도는 결정 구조에 내재되어 있다
	-> 따라서, 결정 구조의 종류, 양을 결정 가능
<font color="#003380"><strong><center>X-ray diffraction의 정의 : 결정 물질의 구조에 대한 정보를 얻기 위한 분석 방법</center></strong></font>

V. XRD instrument
1\. 왜 XRD를 쓰고, 왜 X-ray를 쓰는가?
1\) X-ray 사용 이유
- material의 원자 간 평균 간격이 X선의 파장과 유사하기 때문
2\) XRD 사용 이유
- 원자 배열, 대칭성, unit cell dimension 등을 분석하여 원자 및 분자의 구조 결정 및 분석
2\. XRD의 구조
![[Pasted image 20241020215252.png|500]] 
![[Pasted image 20241020215319.png]]
- 빈칸 뚫고 채우라는 문제가 나올 수 있다맨
- 짝을 이루는 관계 : scatter slit - anti- scatter slit
	soller slit - solar slit
	divergence slit-receiving slit
	X-ray tube-Detector
3\. X-ray tube
1\) X-ray generations - X-ray tube 분석
![[Pasted image 20241020215337.png|400]]
과정
- 1. vaccum tube에서 cathode가 가열되어 열전자를 내뿜는다
- 2. 이들은 음극과 양극 사이의 강한 전압에 의해서 가속화된다 -> **이들은 target 물질과 충돌한다**
- 3. 이 과정에서, **전자들의 운동에너지가 X-ray**와 thermal energy로 변환된다

일부 물질의 역할
- copper target : 주로 Cu가 사용되며, 이외에도 Cr, Fe, Co, Mo, Ag, W등이 사용된다
- Be-window : 베릴륨은 다른 물질들보다 absorption coefficient(흡수 계수)가 훨씬 낮다
	그리고, 얇은 Be window는 대기압을 견디고 튜브 내의 진공 유지가 가능하다
	=> 따라서 Be-window를 통해서 X-ray가 나가게 한다.
- cooling water : target에서 발생한 열은 cooling water system에 의해 냉각된다
cf. 왜 진공어야 하는가? : 방출된 전자가 target 물질과만 만나게 하기 위해서

2\) X-ray generations - X-ray의 실제 발생 과정
과정
- 1. 강한 전압 부과
- 2. 전자의 가속
- 3. 타깃 물질과 충돌
- 4. X-ray 발생

- 이를 실제 도식과 관련해 보면 다음과 같다
![[Pasted image 20241020215402.png|350]]
- 즉, 전자가 원자 내의 전자를 쳐서 X 선이 발생함을 알 수 있다
cf. X-ray 생성 효율($\epsilon$)
$\epsilon=1.1\times10^{-9}\times Z\times V$
- Z : 타깃 물질의 원자번호
- V : 전자들의 가속 전압

4\. X-ray의 종류
1\) Characteristic X-rays
![[Pasted image 20241020215451.png]]
- Characteristic X-ray : 표적 물질의 요소들에 국한된다
- **Discrete(이산적) 에너지 레벨**로 구성되며, 이들은 K, L, M계열로 분류된다
- 이름 붙이기 : 전자가 떨어지는 위치가 첫자리 e.g. K껍질로 떨어지면 K__ 
	자신보다 한 껍질 위에서 왔으면 $\alpha$, 두 껍질 위면 $\beta$
	마지막 자리 결정은 위에 있는 예시 정도만 외우기
- 모든 물질에 대해서 $K\alpha1$과 $K\alpha2$의 강도 비율은 대략 2:1이다
	-> $K_{\alpha}=\frac13\left(2\cdot K_{\alpha1}+K_{\alpha2}\right)$

2\) continuous X-rays(Bremsstrahlung X-Rays)
![[Pasted image 20241020215508.png|300]]
- 원자핵의 전기장에 의해 전자가 감속하면서 방향이 변화하고, 에너지가 손실된다
- 이 에너지 손실이 연속적 X선 스펙트럼으로 방출
- 연속 X선 강도 -> 가속도 전압에 정비례

3\) Characteristic X-rays + continuous X-rays
- 실제 X-선 환경에서는  Characteristic X-rays + continuous X-rays 둘 다 생성된다
	-> XRD 분석에서는 crystal structure, lattice parametes에 대한 정보를 얻기 위해 **주로 Characteristic X-rays에 집중**
- 반면, 연속 X선은 background noise로 간주


5\. 기타 장비들
1\) Beta-filter
![[Pasted image 20241020215549.png|350]]
![[Pasted image 20241020215607.png|350]]
-> Ni filter 사용 전후 Cu target의 X-ray spectrum
- Beta-filter 용도 : monochromate X-rays(X-ray의 단색화)
	구체적으로 말하면, $K_{\alpha}$ radiation은 최대한 유지하고, $K_{\beta}$와 **continuous X-ray(white radiation) 억제** , 혹시 모르니까 continuous X-ray라고 쓰자
- Filter의 absorption edge 위치 : 표적 물질의  Kα 및 Kβ 파장의 사이에 존재 -> Kβ 흡수하도록
	cf. absorption edge : 물질의 흡수 스펙트럼에서 급격한 불연속성이 나타나는 위치(파장)
- e.g. 니켈 메탈의 absorption edge : 타깃 물질인 copper는  Kα (λ=1.542 Å)와 Kβ (λ=1.392 Å) 와 같은 파장을 가진다. 이때 니켈은 그 사이인 1.488 Å 만큼의 absorption edge를 가진다.
	-> 이때 니켈 foil은 Cu Kβ X-ray의 강도를 줄일 수 있다.
	-> 당연하지만, target 물질에 따라서 나타나는 파장의 위치들이 다르고, 이는 곧 사용할 Beta-filter도 달라진다는 것을 의미
2\) Divergence slits
![[Pasted image 20241020215646.png|600]]
- 목적 : incident beam(입사 빔) 경로에 divergence slit을 장착하여 equatorial(적도의, 즉 수평의) divergence를 제어, 입사 X선 빔에 노출되는 샘플의 양(길이) 제어
-> 그림을 보고 이해하자

3\) soller slit
![[Pasted image 20241020215705.png]]
- 목적 : 입사 및 회절 X선 beam의 축 방향(axial, 수직) divergence를 제어하기 위함
- 이점 : 2theta-type scan에서 peak shape improve, resolution 향상

4\) scatter / anti-scatter slits
- 목적 : 회절된 X선 빔의 산란 각도를 제한
- 이점 : 검출기에 도달하는 산란된(scattered) X선의 각도 범위를 제한 ->회절된(diffracted) X선 신호의 해상도와 선택성을 개선

VI. Principle and characteristic of XRD
1\. 간섭
1\) constructive interference(보강 간섭)
![[Pasted image 20241020215813.png|200]]
- in phase radiation(동일한 위상)
2\) destructive interference(상쇄 간섭)
![[Pasted image 20241020215825.png|200]]
- out of phase radiation(반대인 위상)

2\. <font color="#ff0000"><strong>Bragg's law</strong></font> -> 매우 중요
![[Pasted image 20241020215841.png|400]]
1\) 정의
- Bragg's law : $n\lambda=2d_{hkl}\sin\theta$
- 𝝀= X선 파장  
- 격자 평면 사이의 d=거리  
- 𝜃= 입사 빔과 격자 평면 사이의 각도
2\) 유도
- 두 radiation의 길이 차이는 $2d\sin\theta$이다.
- 그리고 두 radiation은 보강 간섭을 한다.
- 그런데 보강 간섭이 일어날 경우, 두 radiation의 파장 차이는 $n\lambda$이다. 따라서 $n\lambda=2d_{hkl}\sin\theta$이다.
cf. 우리가 입사하는 X-ray광선에 대해서, 항상 이것이 Bragg's law를 만족시킨다는 게 아니다. 
-> 오히려, X-ray 특정 각도로 광선을 입사했을 때, 강한 보강 간섭이 나타난다면, Bragg's law를 만족시킨다고 보고, 여기에서 d값과 theta값을 구하는 것이다.

3\) 특징
- 우리가 $d_{hkl}$과 $\theta$를 안다면 우리는 정확한 $\lambda$를 알 수 있다
- **만약 우리가 $\lambda$와 $\theta$를 안다면, 우리는 상을 구별할 수 있다 => 우리가 XRD를 사용하는 이유**
- 



