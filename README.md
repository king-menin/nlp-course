# Автоматическая обработка текстов 

Емельянов Антон

email: login-const@mail.ru

telegram: @king_menin



|                       | Лекции                                                                                                                                           | Практика                                                    | Домашнее  задание                                                   |
|-----------------------|--------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------|---------------------------------------------------------------------|
| занятие 1 (21 апреля)  | Введение: задачи автоматической обработки текстов и основные подходы к их решению. Токенизация, морфологический анализ. Sequence labeling  | Регулярные выражения, лемматизация, POS-тэггинг, морфологический анализ. | Генерация текста по шаблону. Извлечение телефонных номеров из текста.   

|

## 14 марта

Данные к занятию: [git]()

Лекция 1: [intro.pdf](https://github.com/king-menin/nlp-course/blob/master/lecture%201.%20intro%20to%20nlp/intro.pdf), лекция 2: (morphology.pdf)[https://github.com/king-menin/nlp-course/blob/master/lecture%202.%20morphology/morphology.pdf]  практика [sem1.ipynb](https://github.com/king-menin/nlp-course/blob/master/sem%201/sem1.ipynb), домашнее задание: [hw1.ipynb](https://github.com/king-menin/nlp-course/blob/master/hw1/hw1.ipynb)

Необходимые библиотеки Python:
* nltk; после установки nltk необходимо из командной строки Python3 вызвать команды
```python
import nltk
nltk.download('stopwords')
nltk.download('punkt')
```
* pymorphy2
* matplotlib
* pandas
* sklearn





## Рекомендуемые ресурсы
### На английском

* [Jurafsky & Martin](https://web.stanford.edu/~jurafsky/slp3/)
* [Курс Лауры Каллмайер по МО для NLP](https://user.phil.hhu.de/~kallmeyer/MachineLearning/index.html)
* [Курс Нильса Раймерса по DL для NLP](https://github.com/UKPLab/deeplearning4nlp-tutorial)
* [Курс в Оксфорде по DL для NLP](https://github.com/UKPLab/deeplearning4nlp-tutorial)
* [Курс в Стенфорде по DL для NLP](http://cs224d.stanford.edu)
* [Reinforcment Learning for NLP](https://github.com/jiyfeng/rl4nlp)


### На русском (и про русский, в основном)

* [НКРЯ](http://ruscorpora.ru)
* [Открытый корпус](http://opencorpora.org)
* [Дистрибутивные семантические модели для русского языка](http://rusvectores.org/ru/)
* [Морфология](https://tech.yandex.ru/mystem/)
* [Синтаксис](https://habrahabr.ru/post/317564/)
* [Томита-парсер](https://tech.yandex.ru/tomita/)
* [mathlingvo](http://mathlingvo.ru)
* [nlpub](https://nlpub.ru)
* [Text Visualisation browser](http://textvis.lnu.se)



## Литература

* Manning, Christopher D., and Hinrich Schütze. Foundations of statistical natural language processing. Vol. 999. Cambridge: MIT press, 1999.
* Martin, James H., and Daniel Jurafsky. "Speech and language processing." International Edition 710 (2000): 25.
* Cohen, Shay. "Bayesian analysis in natural language processing." Synthesis Lectures on Human Language Technologies 9, no. 2 (2016): 1-274.
* Goldberg, Yoav. "Neural Network Methods for Natural Language Processing." Synthesis Lectures on Human Language Technologies 10, no. 1 (2017): 1-309.