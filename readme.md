
twitter-sentiment

Repository of course work, attempting to Russian twitter sentiment analysis

В данном репозитории содержатся (будут содержаться) попытки к анализу высказываний в русскоязычном твиттере. Главной целью является попытка получения информации о мнениях о политиках или же определенных известных личностях

В будущем, данное приложение должно представлять собой WEB-приложение на Django

На сегодня в репозитории содержится:

    более-менее реализация анализатора, с использованием классификатора стохаистического градиентного спуска
 (просто потому что из все других классификаторов, он работал более-менее. Кроме него еще был PassiveAgressive, но 
про него с точки зрения математики я ваааааще ничего не смогу рассказать, пока чт) http://scikit-learn.org/stable/modules/sgd.html#sgd
    скрипт получения информации из твиттера
    выборка обученных твитов
    начальный каркас Django-application

Результаты всех тестов на данный момент довольно странные, обучающая выборка tweets.json из просторов интернета, (и судя по результатам обучена не на "политических твитах")
Что нужно реализовать:

    Словарь, если использовать методы со словарем
    Обучающую выборку, на твитах по теме, если анализируем политиков
    Пожалуй, посмотреть другие методы анализа (алгоритмы нужно будет переписывать 100%)
    Проверять тональность относительно личности, а не общее положение относительно текста твита


