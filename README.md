
<pre>
다음은 데이터 파일(population.csv)에 대한 설명입니다.

AGE: 나이, int
SEX: 성별 (남, 여), string
SCHL: 학력 (중졸이하, 고졸, 전문학사, 고졸, 학사, 석사, 박사), string
WORK: 직장형태 (기업, 공무원, 자영업, 비영리단체), string
INCOME: 연소득, double


[문제1]   
결측값을 가지고 있는 행과 AGE 변수에서 20세 ~ 50세 범위 밖의 값을 가지고 있는 행을 제거합니다.
INCOME 변수의 이상치를 tukey 방식으로 확인하고 제거합니다. 이 때 제거된 이상치의 개수와 이상치 
제거 이후의 최소값, 최대값을 순서대로 기술하십시오.



[문제2]
[문제1]의 결과에서 개인소득이 3/4분위수 이상인 고소득자들은 1로, 그렇지 않으면 0의 값을 가지는 
HIGH_INCOME 변수를 추가하고, 원핫인코딩이 적용된 SCHL변수들 중 박사와 HIGH_INCOME 변수 간의 
상관계수 값과 p-value 값을 구하십시오. (상관계수는 피어슨의 상관계수를 구하고, 계수의 값은 소수점 
셋째자리에서 반올림하고 소수점 둘째자리까지 표시하십시오.) 
</pre>


<pre>
다음은 톨게이트 시간대별 통행량 데이터 파일(traffic.csv)에 대한 설명입니다.

date: 년월일, string
T0: 00~01시의 통행량
...
T23: 23~24시의 통행량

[문제1]   
톨게이트의 시간당 평균 통행량이 가장 많은 주와 해당 주의 시간당 평균 통행량을 구하십시오. 
(통행량은 소수점 첫째자리에서 반올림해 정수부만 표시하십시오.)

[문제2]
시간당 평균 통행량이 가장 많은 요일과 해당 요일의 시간당 평균 통행량을 구하고, 
분산분석의 실행 결과 요일별 시간당 평균 통행량의 F-value와 p-value를 구하십시오. 
이 때 시간당 평균 통행량이 동일한 요일은 무엇입니까? 
(통행량, F-value, p-value는 소수점 넷째자리에서 반올림한 값으로 셋째자리까지 표시하십시오.)
</pre>
