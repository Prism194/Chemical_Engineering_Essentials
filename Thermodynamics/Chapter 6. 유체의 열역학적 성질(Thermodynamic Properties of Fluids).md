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
- 이를 대입하면 $dH^{ig}=C_{P}^{ig}dT,dS^{ig}=C_{P}^{ig}\frac{dT}{T}-R_{}\frac{dP}{P}$(6.23, 6.24)
	-> 이 식은 3.3, 5.5절에서 이상기체 상태에 대해 제시한 식들이다
4\) 액체 상태에 적용
- 부피 팽창률 정의 : $\beta=\frac{1}{V}\left(\frac{\partial V}{\partial T}\right)_{P}dT+\left(\frac{\partial V}{\partial P}\right)_{T}dP$ 
- 이 식을 사용하면, $\left(\frac{\partial S}{\partial P}\right)_{T}=-\beta V,\left(\frac{\partial H}{\partial P}\right)_{T}=\left(1-\beta T\right)V$이 되며
- 이렇게 적용 가능하다.$dH=C_{P}dT+\left(1-\beta T\right)VdP,dS=C_{P}\frac{dT}{T}-\beta VdP$ (6.27), (6.28)
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
- dU, dS를 T와 V에 대해 미분하면 $dU=\left(\frac{\partial U}{\partial T}\right)_{V}dT+\left(\frac{\partial U}{\partial V}\right)_{T}dV$ $dS=\left(\frac{\partial S}{\partial T}\right)_{V}dT+\left(\frac{\partial S}{\partial V}\right)_{T}dV$이다.
- 이들 역시 dU에 대한 기본식과 Maxwell 관계식을 사용하면 아래와 같은 식을 얻을 수 있다.
- $dU=C_{V}dT+\left\lbrack T\left(\frac{\partial P}{\partial T}\right)_{V}-P\right\rbrack dV$ , $dS=C_{V}\frac{dT}{T}+\left(\frac{\partial P}{\partial T}\right)_{V}dV$
- 이들은 조성이 일정한 균질유체의 내부에너지와 엔트로피를 온도 및 부피와 연관시키는 일반식이다.
- 이들 역시 부피 팽창률, 등온 압축률과 연관해 나타낼 수 있다.

5\. 생성함수로서의 Gibbs 에너지
1\) 깁스 에너지를 H, V에 연관시키자
- $dG=VdP-SdT$이고, G = H - TS이다.
- $d\left(\frac{G}{RT}\right)=\frac{1}{RT}dG-\frac{G}{RT^2}dT$라는 특수한 항등식에 위 정의를 사용하면 $d\left(\frac{G}{RT}\right)=\frac{V}{RT}dP-\frac{H}{RT^2}dT$이다.
- 이 식은 무차원이다
- 기존 깁스 에너지의 미분꼴과 달리, 엔탈피가 나타나고 있어 사용하기 편리하다
2\) 실제 V, H값 표현 by Gibbs 에너지
- d(G/RT)에 대한 식을 응용하면, 다음 식이 나온다. $\frac{V}{RT}=\left\lbrack\frac{\partial\left(\frac{G}{RT}\right)}{\partial P}\right\rbrack_{T},\frac{H}{RT}=-T\left\lbrack\frac{\partial\left(\frac{G}{RT}\right)}{\partial T}\right\rbrack_{P}$ 
- 이는 H, V에 대한 직접적인 표현이다.
- H, V에 대한 식을 응용해서 S, U에 대한 식도 결정 가능하다
3\) 생성함수로서의 Gibbs 에너지
<font color="#003380"><strong><center>Gibbs 에너지가 정준변수인 T, P의 함수로 주어지면, 간단한 수학적 연산을 통해 다른 열역학적 성질들에 대한 생성함수로서의 역할을 한다.</center></strong></font>
- cf. Helmholtz 에너지 역시 비슷한 일을 할 수 있다

6.2 잔류성질(residual property)
1\. 정의 및 목적
- 정의 : $M^{R}=M-M^{ig}$ <=> $M=M^{ig}+M^{R}$
- 목적 : 성질계산을 이상상태 성질들에 대한 계산과, 이상기체 상태 값에 대한 보정인 잔류성질 계산으로 나누었다.
	-> 이상기체 상태 성질 : 실제 분자구조는 반영하나, 분자 간 상호작용 무시
	-> 잔류성질 : 분자 상호작용 보정
2\. 잔류성질을 계산하기 위한 식 전개
1\) Gibbs 에너지에 대한 잔류성질 유도
-  $\frac{V^{R}}{RT}=\left\lbrack\frac{\partial\left(\frac{G^{R}}{RT}\right)}{\partial P}\right\rbrack_{T}$(6.42)이와 같이 잔류성질은 그냥 R첨자만 붙이면 된다
- T는 일정하다고 두면, $d\left(\frac{G^{R}}{RT}\right)=\frac{V^{R}}{RT}dP\left(T일정\right)$, 이다.
- P=0에서부터 임의의 압력 P까지 적분하면, $\frac{G^{R}}{RT}=J+\int_0^{P}\left(Z-1\right)_{}\frac{dP}{P}$이다. 
	-> $\left(\frac{G^{R}}{RT}\right)_{P=0}=J$ (적분상수)이다.
- 이 식을 간단히 쓰면, $$\frac{G^{R}}{RT}=\int_0^{P}\left(Z-1\right)_{}\frac{dP}{P}$$ 이다.
2\) 엔탈피와 엔트로피의 잔류성질 계산
- 깁스 에너지의 잔류성질에 관한 식으로부터, 엔탈피, 엔트로피의 잔류성질에 대한 식을 구할 수 있다.
- $\frac{H^{R}}{RT}=-T\int_0^{P}\left(\frac{\partial Z}{\partial T}\right)_{P}\frac{dP}{P}$
- $G^{R}=H^{R}-TS^{R}$을 이용하면 엔탈피 잔류성질에 대한 식에서 엔트로피 잔류성질에 대한 식을 구할 수 있다. $\frac{S^{R}}{RT}=-T\int_0^{P}\left(\frac{dZ}{dT}\right)_{P}\frac{dP}{P}-\int_0^{P}\left(Z-1\right)_{}\frac{dP}{P}$(T 일정)
3\) Gibbs 에너지, 엔탈피, 엔트로피의 잔류성질에 대한 식의 응용
- PVT 실험 데이터에서 얻은 값을 적분식에 적용해서 압축인자 Z에 대한 값을 결정할 수 있다
- 반대로 상태 방정식을 통해 얻은 Z값들을 적용해서 잔류성질들을 구할 수 있다

3\. 잔류성질로부터의 실제 엔탈피와 엔트로피 
1\) 유도
- 이상기체 상태에서의 H, S 값(6.23), (6.24)를 적분하여, $H^{ig}=H_0^{ig}+\int_{T_0}^{T}C_{P}^{ig}dT$,$S^{ig}=S_0^{ig}+\int_{T_0}^{T}C_{P}^{ig}dT-R\ln\frac{P}{P_0}$을 얻는다
 - 잔류성질의 정의에 의해 $H^{ig}=H_0^{ig}+\int_{T_0}^{T}C_{P}^{ig}dT+H^{R}$,$S^{ig}=S_0^{ig}+\int_{T_0}^{T}C_{P}^{ig}dT-R\ln\frac{P}{P_0}+S^{R}$이다.
 2\) 의의
 <font color="#003380"><strong><center>이상기체 상태의 실제적 가치 : 실제 기체 성질들의 계산을 위한 바탕</center></strong></font>
 - 우리는 기체의 경우 이상기체 상태 열용량과 PVT 데이터만 있으면 열역학적 성질을 알 수 있다
 - 기체에 대한 실제 적용 : 잔류값들은 일반적으로 상당히 작은 값을 가진다
 - 고체, 액체에 대한 실제 적용 : 잔류값들은 응축에 따른 상당한 엔탈피, 엔트로피 변화를 가져야 하므로 잔류값들이 상당히 커 위 식을 잘 사용하지 않고, 6.27, 6.28 식을 주로 쓴다(액체에 대한 엔탈피, 엔트로피 계산 식 참조)

6.3 비리얼 상태 방정식에 의한 잔류성질
1\. 2항 비리얼 상태 방정식
$Z-1=\frac{BP}{RT}$
- 