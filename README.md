# pandas_ex

### pandas 복습
```
# iloc 이용해서 인덱싱하는 방법은 loc 메소드와 다름 (위치 기반 인덱싱)
df.iloc[[1, 2, 4], [0, 2]]
df.iloc[:, 1:3]

# 결측치 처리하는 방법 (상황에 따라 함수, 메소드 다름)
df1.dropna(how="any")
df1.fillna(value=5)
pd.isna(df1)
```
