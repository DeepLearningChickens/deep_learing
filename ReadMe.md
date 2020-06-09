# 6/3 회의시작

git init

git remote add origin https://github.com/DeepLearningChickens/deep_learing.git

git branch 자기이름

git checkout 자기이름

git commit -am "first commit"

git push -u origin hyehyeong

#06.09 준영 사례찾기
#동일한 데이터로 분석한 사례 2개 

https://www.kaggle.com/chrischien17/which-predicts-fake-news-better-bert-or-cnn

Loss value: 21.403350672446006, accuracy:0.5041322112083435

model.fit(texts_train, y_train,
              batch_size=128,
              epochs=5,
          validation_data =(texts_test, y_test),
          verbose=True)



https://www.kaggle.com/mohamadalhasan/fake-news-around-syrian-war

cv_df.groupby('model_name').accuracy.mean()

model_name
LinearSVC                 0.500598
LogisticRegression        0.509332
MultinomialNB             0.503106
RandomForestClassifier    0.519317
Name: accuracy, dtype: float64

https://www.kaggle.com/kerneler/starter-fake-news-dataset-4e88fa9f-b/data


