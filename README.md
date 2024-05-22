# life game

## what is the Conway's Game of Life?
> 1970年にイギリスの数学者ジョン・ホートン・コンウェイ (John Horton Conway) が考案した数理モデルである。
> 単純なルールから複雑な結果が生成され、パズルやミニスケープの要素を持っている。
> 生命の誕生、進化、淘汰などのプロセスを連想させるパターンも存在し、シミュレーションゲームと分類される場合がある。

wiki:https://ja.wikipedia.org/wiki/%E3%83%A9%E3%82%A4%E3%83%95%E3%82%B2%E3%83%BC%E3%83%A0


## Rule

- 死んでいるセルの周囲に、生きているセルが3つあれば、次の世代に生物が誕生する
- 生きているセルの周囲に、生きているセルが…
-- 1つ以下ならば、過疎なので生物は死滅する
-- 2つか3つあれば、次の世代も生存する
-- 4つ以上ならば、過密なので死滅する


## package

* crossterm
* lazyrand


## project init

```
mkdir life_game
cd life_game
cargo init
cargo add lazyrand
cargo add crossterm
```
