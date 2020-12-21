# nishika classical music composers classification competition
- [about competition](https://www.nishika.com/competitions/8/summary)  
- score: micro f1(各クラスのTP,FN.FP,TNを和にしてからF値を計算)
## directories
```
nishika_composer
┣ data <- 音源データとcsv
┣ notebook <- ipynb
┣ src <- ノートブック以外
┗ output
```
## about notebooks
|No|概要|
|---|---|
|001|test, trainの各ファイルを30秒ごとにトリミング|
|002|mel spectrogramの作成、リサイズ|
