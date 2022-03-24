# About_Python
파이썬을 공부하면서 알게된 것을 기록하는 저장소입니다.

# pandas_loc\[\]
- 행 조회하기 위해서 행(인덱스 명을 입력)
```python
df = pd.DataFrame(data)
df.loc['2월'] # 결과타입: pandas.core.series.Seies
```

# pandas_apply()
- 데이터프레임을 조작하다보면 내가 정의해놓은 함수에 따라 전체 데이터프레임이나 특정한 column의 값들이 일괄적으로 변경하기를 원할 수 있음. 
- def(x): 처럼 함수로 나타낸 코드의 return 값을 모든 데이터프레임에 적용하고 싶을 때 apply함수 적용.
