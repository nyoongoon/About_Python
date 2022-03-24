# About_Python
파이썬을 공부하면서 알게된 것을 기록하는 저장소입니다.
<br/><br/><br/><br/>

# CountVectorizer
- sklearn.feature_extraction.text.CountVectorizer
- 특징 추출을 해주는 하나의 클래스
- 영상, 자연어 같이 분석이 어려운 데이터를 비교와 해석에 필요한 형태로 변형시켜 처리할 수 있게 해줌.
- 텍스트 특징추출은 문자열을 수치 벡터로 만드는 방법
- 단어들의 카운트(출현 빈도(frequency))로 여러 문서들을 벡터화.
- 카운트 행렬, 단어 문서 행렬(
Term-Document Matrix, TDM) 모두 소문자로 변환시키기 때문에 me와 Me는 모두 같은 특성이 된다.
- 가장 단순한 특징으로, 텍스트에서 단위별 등장횟수를 카운팅하여 수치 벡터화를 시킴. 
- 카운팅 방법 : 먼저 단어 사전 벡터를 만들고 카운팅할 문장을 확인아며 그 단어 사전의 횟수를 카운팅하는 것.

<br/><br/>
# pandas_loc\[\]
- 행 조회하기 위해서 행(인덱스 명을 입력)
```python
df = pd.DataFrame(data)
df.loc['2월'] # 결과타입: pandas.core.series.Seies
```
<br/><br/>

# pandas_apply()
- 데이터프레임을 조작하다보면 내가 정의해놓은 함수에 따라 전체 데이터프레임이나 특정한 column의 값들이 일괄적으로 변경하기를 원할 수 있음. 
- def(x): 처럼 함수로 나타낸 코드의 return 값을 모든 데이터프레임에 적용하고 싶을 때 apply함수 적용.
<br/><br/>
