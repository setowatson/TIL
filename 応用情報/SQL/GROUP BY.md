（データ例）
テーブル名：Sample
class  point
a    |  10
a    |  20
b    |  30
a    |  30
b    |  30


まとめて取得
```
select class,avg(point) from sample group by class;
------
a 20
b 30
------
```

group byしたデータを絞る場合はwhereでなく、「having」
```
select class,avg(point) from sample group by class having point > 20;
------
b 30
------
```

select分で出力できる項目はgroup by でグルーピングした項目と計算系（sumやavg、countなど）のみ
```
select class,avg(point),teacher from sample group by class,teacher having point > 20;
------
b 30 sato
------
```





