# Автоматическая обработка текстов 

Емельянов Антон

email: login-const@mail.ru

telegram: @king_menin



|                       | Лекции                                                                                                                                           | Практика                                                    | Домашнее  задание                                                   |
|-----------------------|--------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------|---------------------------------------------------------------------|
| занятие 1 (21 апреля)  | Введение: задачи автоматической обработки текстов и основные подходы к их решению. Токенизация, морфологический анализ. Sequence labeling  | Регулярные выражения, лемматизация, POS-тэггинг, морфологический анализ. | Генерация текста по шаблону. Извлечение телефонных номеров из текста.   
| занятие 2 (28 апреля)  | Тематическое моделирование  | Применение тематического моделирования и визуализация коллекций. Классификация.| Тематический анализ коллекции


## 21 апреля

Данные к занятию лежат в папке: [git:sem1](https://github.com/king-menin/nlp-course/tree/master/sem%201)

Лекция 1: [intro.pdf](https://github.com/king-menin/nlp-course/blob/master/lecture%201.%20intro%20to%20nlp/intro.pdf)

Лекция 2: [morphology.pdf](https://github.com/king-menin/nlp-course/blob/master/lecture%202.%20morphology/morphology.pdf),  практика [sem1.ipynb](https://github.com/king-menin/nlp-course/blob/master/sem%201/sem1.ipynb), домашнее задание: [hw1.ipynb](https://github.com/king-menin/nlp-course/blob/master/hw1/hw1.ipynb)

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

## 28 апреля

Данные к занятию лежат в папке: [git:sem2](https://github.com/king-menin/nlp-course/tree/master/sem%202)

Лекция 3: [topic modeling.pdf](https://github.com/king-menin/nlp-course/blob/master/lecture%203.%20topic%20modeling/topic%20modeling.pdf),  практика [topic modeling.ipynb](https://github.com/king-menin/nlp-course/blob/master/sem%202/topic_modeling.ipynb) или (для тех, кто хочет выполнять семинары онлайн) [topic modeling.ipynb](https://drive.google.com/file/d/18QKAqSRyHxueej6XBSNLcEgY9Fr7_kAO/view?usp=sharing)

Лекция 4: [classification.pdf](https://github.com/king-menin/nlp-course/blob/master/lecture%204.%20classification/classification.pdf),  практика [classification.ipynb](https://github.com/king-menin/nlp-course/blob/master/sem%202/classification.ipynb) или (для тех, кто хочет выполнять семинары онлайн) [classification.ipynb](https://drive.google.com/file/d/1I9qBSkgILoLl0fLtm7Mqrl6L3xBv3IOr/view?usp=sharing), данные [data-train.txt](https://drive.google.com/file/d/19e2fOFpykP4iWCCCxzlJraAilvnVb1m9/view?usp=sharing), домашнее задание: [hw2.ipynb](https://github.com/king-menin/nlp-course/blob/master/hw2/hw2.ipynb)

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
* pymystem3
* python-rake
* wordcloud
* gensim
* pyLDAvis
* fasttext (не путайте с fastText)

## 12 мая

Данные к занятию лежат в папке: [ru.vec](https://www.dropbox.com/s/0x7oxso6x93efzj/ru.tar.gz), [all.txt](https://www.dropbox.com/s/ksm21a8y6lgl511/all.txt.zip?dl=0)

Лекция 5: [distributive semantic.pdf](https://github.com/king-menin/nlp-course/blob/master/lecture%205.%20distibutive%20semantic/distributive%20semantic.pdf),  практика [ds.ipynb](https://github.com/king-menin/nlp-course/blob/master/sem%203/ds.ipynb), домашнее задание: [hw3.ipynb](https://github.com/king-menin/nlp-course/blob/master/hw3/hw3.ipynb)

Необходимые библиотеки Python:
* gensim
* [pydsm](https://github.com/jimmycallin/pydsm)
* pyemd
* matplotlib
* sklearn
* numpy





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