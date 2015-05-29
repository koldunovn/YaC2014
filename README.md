[Video of the talk](https://www.youtube.com/watch?v=9iwfJvSh004)

Инструкции по установке необходимых модулей
===========================================

Самый быстрый способ всё поставить, это установить себе [Миниконду](http://conda.pydata.org/miniconda.html), которая содержит менеджер пакетов [`conda`](http://conda.pydata.org/docs/intro.html) и `Python`.

Далее открываем командную строку (да, на Windows тоже) и пишем:

```
conda install ipython-notebook pandas matplotlib basemap pip
```
и потом
```
pip install apachelog pygeoip
```
После завершения инсталяции скачиваем этот репозиторий, и выполняем в папке с ним:

```
ipython notebook
```

