# CASL_Comment
## どんなソースを想定しているか
* ラベル、命令、オペランドの区切りは「**タブ**」
* 二行目以降でメモリにデータを入れる
* メインの処理は「MAIN」ラベルの行から始まる


## 皆様に改良して欲しいとこ
48行目以降に

```python
if order == "LD":
  print(row_str + "\t;" + register + " <= (" + address + ")")
```

こーんな感じで、対応する命令とコメントを増やしていってほしいです。  
よろしくお願いしますm(_ _)m
