# Определение токсичных комментариев

## Статус проекта: завершён

## Описание проекта

Интернет-магазин «Викишоп» запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.
Обучите модель классифицировать комментарии на позитивные и негативные. В вашем распоряжении набор данных с разметкой о токсичности правок.

## Навыки и инструменты

- **pandas**
- **numpy**
- **re**
- **nltk**
- **matplotlib**
- sklearn.pipeline.**Pipeline**
- catboost.**CatBoostClassifier**
- sklearn.tree.**DecisionTreeClassifier**
- nltk.tokenize.**word_tokenize**
- nltk.stem.**WordNetLemmatizer**
- sklearn.model_selection.**train_test_split**
- sklearn.feature_extraction.text.**TfidfVectorizer**
- sklearn.linear_model.**LogisticRegression**
- sklearn.metrics.**f1_score**
- nltk.corpus.**stopwords**
- sklearn.model_selection.**GridSearchCV**

## Цель исследования

Определение токсичности комментариев.

## Ход исследования

Интернет-магазин запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Требуется инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.

## Описание данных

Столбец text в нём содержит текст комментария, а toxic — целевой признак.

## Вывод по итогам исследования

Самый высокий f1 у LogisticRegression
