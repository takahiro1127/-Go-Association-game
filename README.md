## Gorillaのchat機能を元に連想ゲームを作る
①出題者1人がランダムで設定される  
②出題者は画像を複数枚選び、設定した画像から連想される答えをひらがなで入力する。  
③出題者の設定した画像が15秒おきにchatに投げられる  
④chat参加者はお題に対してひらがなで答えを投げる  
⑤最初に答えが合っていた人の文字が赤く表示される  

### ちょっとだけ工夫すればできそうなこと
できればIPとポイントを紐付けて、ポイントを付与して、ランキング形式で表示したりしたい  
IQ問題を出して誰が最初に答えるかとかクイズ系ならなんでもいけそう

## 実装手順
- [ ] chat機能に対して、予め設定していた値だったら赤文字で表示するようにする
- [ ] 赤文字にするのを一番最初の人のみにする
- [ ] 設定する文字列を特定のフォームで選択できるようにする
- [ ] 文字列の設定フォームを特定の人にだけ出すようにする
- [ ] chat内に画像を表示できるようにする
- [ ] 画像を一定時間おきに出すようにする
- [ ] 画像をformから設定できるようにする
- [ ] 画像を複数枚設定できるようにする