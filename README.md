Лаба по AI
==========

Кластеризовать облако точек.

Как скомпилировать
==================

Из зависимостей только gnuplot, поэтому без кабалов обошлось.

```bash
$ make # лол
```

Как запустить
=============

В stdin подаются координаты в формате "x y _" по одной на строке.

Через runhaskell:

```bash
$ cat input.txt | runhaskell clust.hs 47 Complete
```

Скомпилированную версию:

```bash
$ cat input.txt | ./clust 47 Complete
```

Пример работы
=============

![alt tag](https://raw.github.com/kosmaks/clustering/master/screenshot.png)
