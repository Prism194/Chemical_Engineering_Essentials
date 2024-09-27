6.0
- 열역학 제 1, 2법칙으로부터 조성이 일정한 계에 대해 적용된 열역학의 수학적 구조에 대한 기초가 되는 기본적인 성질들 간의 관계식 전개
- PVT 및 열용량 데이터로부터 엔탈피와 엔트로피의 값들을 계산할 수 있는 식 유도
- 선도들이나 표들의 형태들을 예시하고 논의
- 열역학적 성질을 추정할 수 있는 일반화된 상관관계식 전개

6.1 기본적인 성질 관계식
1\. 기본적인 성질 관계식 표현
1\) 유도 및 정의
- $d\left(nU\right)=dQ_{rev}+dW_{rev}$
- $dW=-Pd\left(nV\right)$, $dQ_{rev}=Td\left(nS\right)$
- 따라서, $d\left(nU\right)=Td\left(nS\right)-Pd\left(nV\right)$
2\) 주요 열역학적 성질
- 엔탈피 정의 : $H=U+PV$
- Helmholtz 에너지 정의 : $A=U-TS$
- Gibbs 에너지 정의 : $G=H-TS=U+PV-TS$
3\) 주요 열역학적 성질 미분(n = 1로 두었을 때)
- $dH=dU+PdV+VdP=TdS+VdP$(내부에너지에 대한 식 대입) 
- $dA=-SdT-PdV$
- $dG=-SdT+VdP$
- 따라서, $U=U\left(S,V\right),H=H\left(S,P\right),A=A\left(T,V_{}\right),G=G\left(T,P\right)$
- 이 변수들은 정준(canonical) 변수들이라 하며, 이들의 함수로 나타내어진 열역학적 성질은 독특한 특성을 가진다.
4\) 적용
<font color="#003380"><strong><center>위 식들은 닫힌 PVT계에서 한 평형상태에서 다른 평형상태로의 미소변화를 일으키는 임의의 공정에 대해 적용된다.</center></strong></font>
- 위 식들은 비록 가역공정을 두고 계산되었으나, 상태함수들이므로 비가역 공정에 대해서도 적용 가능하다
- 오직 계의 상태에만 의존한다

2\. Maxwell 관계식
1\) 종류
- $\left(\frac{\partial T}{\partial V}\right)_{S}=-\left(\frac{\partial P}{\partial S}\right)_{V}$
- $\left(\frac{\partial T}{\partial P}\right)_{S}=\left(\frac{\partial V}{\partial S}\right)_{P}$
- $\left(\frac{\partial S}{\partial V}\right)_{T}=\left(\frac{\partial P}{\partial T}\right)_{V}$
- $-\left(\frac{\partial S}{\partial P}\right)_{T}=\left(\frac{\partial V}{\partial T}\right)_{P}$ 
	-> 암기가 필요하다면 암기 팁을 이용하자
2\) 유도
- $dF=\left(\frac{\partial F}{\partial x}\right)_{y}dx+\left(\frac{\partial F}{\partial y}\right)_{x}dy$
- 이때, F를 x로 편미분한 것을 M, y로 편미분한 것을 N이라 두자. M과 N을 각각 y, x로 미분하면 두 식은 같다. 
- 이 관계를 내부에너지, 엔탈피, Helmholtz 에너지, Gibbs에너지의 미분 꼴에 대해 적용하면 Maxwell관계식을 얻을 수 있다

3\. T와 P의 함수로서의 엔탈피와 엔트로피
1\) 목적
- 엔탈피와 엔트로피는 가장 중요한 열역학적 성질
- T, P는 계의 가장 일반적인 측정 가능한 성질
2\) 식 유도
- 기본식 : $dH=\left(\frac{\partial H}{\partial T}\right)_{P}dT+\left(\frac{\partial H}{\partial P}\right)_{T}dP$, $dS=\left(\frac{\partial S}{\partial T}\right)_{P}dT+\left(\frac{\partial S}{\partial P}\right)_{T}dP$(당연)
- $dH=C_{P}dT+\left\lbrack V-T\left(\frac{\partial V}{\partial T}_{}\right)_{P}\right\rbrack dP$, $dH=C_{P}\frac{dT}{T}+\left(\frac{\partial V}{\partial T}_{}\right)_{P}dP$ -> 유도 과정은 책을 참조하라
- 이 식들은 Maxwell 관계식과 엔탈피 식의 미분꼴로부터 얻어졌다.
- <font color="#003380"><strong>일정조성의 균질유체에 대해 엔탈피와 엔트로피를 온도 및 압력과 관련지어주는 일반식들이다.</strong></font> -> 질문
3\) 이상기체 상태에 적용
- $PV^{ig}=RT,\left(\frac{\partial V^{ig}}{\partial T}\right)_{P}=\frac{R}{P}$
- 이를 대입하면 $dH^{ig}=C_{P}^{ig}dT,dS^{ig}=C_{P}^{ig}\frac{dT}{T}-R_{}\frac{dP}{P}$
	-> 이 식은 3.3, 5.5절에서 이상기체 상태에 대해 제시한 식들이다
4\) 액체 상태에 적용
- 부피 팽창률 정의 : $\beta=\frac{1}{V}\left(\frac{\partial V}{\partial T}\right)_{P}dT+\left(\frac{\partial V}{\partial P}\right)_{T}dP$ 
- 이 식을 사용하면, $\left(\frac{\partial S}{\partial P}\right)_{T}=-\beta V,\left(\frac{\partial H}{\partial P}\right)_{T}=\left(1-\beta T\right)V$이 되며
- 이렇게 적용 가능하다.$dH=C_{P}dT+\left(1-\beta T\right)VdP,dS=C_{P}\frac{dT}{T}-\beta VdP$ 
- 부피 팽창률을 사용해서 액체에 대한 엔트로피와 엔탈피를 설명할 수 있다고 보면 된다
- 의의 : 임계점으로부터 먼 액체들은 부피와 부피 팽창률이 모두 작으며 거의 상수로 취급한다, <font color="#003380"><strong>따라서 액체는 대부분의 조건들에서 압력은 큰 영향을 미치지 않는다.</strong></font>(S, H를 P에 대해 편미분한 값이 저 항임을 생각하라)

4\.내부에너지 함수
1\) P의 함수로서의 내부에너지
- H = U + PV, U = H - PV
- 이를 일정한 T에 대해, P에 대해 편미분하면$\left(\frac{\partial U}{\partial P}\right)_{T}=\left(\frac{\partial H}{\partial P}\right)_{T}-P\left(\frac{\partial V}{\partial P}\right)_{T}-V$ 
- H에 대한 P, T의 식을 적용하면, $\left(\frac{\partial U}{\partial P}\right)_{T}=-T\left(\frac{\partial V}{\partial T}\right)_{P}-P\left(\frac{\partial V}{\partial P}\right)_{T}$
- 이는 부피 팽창률과 등온 압축률에 대한 식으로 나타낼 수 있다
	-> $\left(\frac{\partial U}{\partial P}\right)_{T}=\left(-\beta T+\kappa P\right)V$
2\) T와 V의 함수로서의 내부에너지와 엔트로피
