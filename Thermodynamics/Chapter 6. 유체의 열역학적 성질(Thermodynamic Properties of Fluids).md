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
3\. T와 P의 함수로서의 엔탈피와 엔트로피
1\) 목적
- 엔탈피와 엔트로피는 가장 중요한 열역학적 성질
- T, P는 계의 가장 일반적인 측정 가능한 성질
2\) 식 유도
- 기본식 : $dH=\left(\frac{\partial H}{\partial T}\right)_{P}dT+\left(\frac{\partial H}{\partial P}\right)_{T}dP$, $dS=\left(\frac{\partial S}{\partial T}\right)_{P}dT+\left(\frac{\partial S}{\partial P}\right)_{T}dP$(당연)
- $dH=C_{P}dT+\left\lbrack V-T\left(\frac{dV}{dT}_{}\right)_{P}\right\rbrack dP$, $dH=C_{P}\frac{dT}{T}+\left(\frac{dV}{dT}_{}\right)_{P}dP$
- 일정조성의 균질유체에 대해 엔탈피와 엔트로피를 온도 및 압력과 