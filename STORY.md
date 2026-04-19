# Day055 Story — Visit Question Deck

## Why
毎日使う小さな課題を、1ページで即解決できる形にしたかったため。

## Requirements
- Webブラウザだけで完結すること
- 1画面で主要操作が終わること
- GitHub Pagesで公開できること

## Design highlights
- Day055専用にテーマをseed固定して再生成時の見た目を安定化
- planning用途に寄せた単機能UIで迷いを減らす
- 出力をそのまま再利用できるテキスト構造
- Family: question_deck_pack
- Mechanic: flow_pick
- Input/Output: question_cards -> choice_cards
- Audience Promise: 限られた時間でも聞く順を決めて入れる。
- Publish Hook: 質問カードを自分で追加・編集しながら優先順に並べると、今聞くべき順と後回し項目が一画面で固まる。
- Complexity Tier: small
- Selected components: none
- Complexity hint: Implement the locked brief with one clear hero interaction and keep the main screenshot readable.

## Trade-offs / Known issues
- ローカル保存機能は未実装
- 複雑な入力バリデーションは最小限

## Next ideas
- 履歴保存
- プリセット追加
- エクスポート形式拡張

## Social copy
Day055｜直前質問デッキ
直前に聞く順を決めやすくするためのツールです。
