# cut_pgm

pgmファイルの余計な部分をカットする

コード：https://github.com/YuichiroHatanaka/cut_pgm/blob/master/cut.ipynb

※読み込むpgmファイルが大きい場合、読み込むのに数分かかる場合がある

#コードの内容

１．pgmファイルを行列の形で読み込む

２．各行の最小値を求める

３．１行目から白の要素を持つ行までの行数を計測し、削除する

４．行列を90度回転させる

５．２〜４を計４回繰り返す

# 結果

## before   (map.pgm)

4000 ピクセル * 4000 ピクセル

![map](https://user-images.githubusercontent.com/73636802/145337453-297813a1-7c75-4a8c-a4ab-3219d573d27a.png)

## after   (new.pgm)

909 ピクセル * 555 ピクセル

![new](https://user-images.githubusercontent.com/73636802/145337392-0cabd967-f67b-4ee1-be4d-d645f18af140.png) 


