# TIL
## 20221006
* 문서 단어 행렬
```python
from sklearn.feature_extraction.text import CountVectorizer
cv = CountVectorizer(stop_words='english', max_features=2000) # 문서 단어 행렬 최대 포함 단어 수 :2000
dtm = cv.fit_transform(df.Plot)
```



