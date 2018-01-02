# TemplateByAPBCSS
## About
Atomc Designを取り入れたCSSアーキテクチャであるAPBCSS(Atmic Prts Base CSS)を使ったテンプレートです。

## Atomic Designとは
デザイン設計思想の一つで、５つのステージから構成されている
+ Atoms(アトム) - 原子　・・・　それ以上分解できない要素のこと（ボタン、ラベルなど）
+ Molecules(モルキュール) - 分子 ・・・　Atomsを組み合わせたもの（テキストとボタンがついたもの）
+ Organisms(オルガニズム) - 有機体　・・・ 分子同士を組み合わせた要素（ナビゲーション、フッターなど）
+ Templates(テンプレート) - テンプレート ・・・有機体を組み合わせた要素（モーダルビュー、ナビゲーションメニュー、フッター）
+ Pages(ページ) - ページ　・・・　固有のページ、テンプレートに具体的な画像、文字を入れたもの

## APBCSSとは
Atomic Designにおける、これ以上分割することのできない要素Atomsをベースに定義していくCSS設計方法のこと。
OOCSSとSMACSSを取り入れていて、マルチクラスの使用やbase,pages,partsディレクトリで管理している。
そして、以下６つのクラスタイプで構成されている

+ Atoms ・・・ 分割できない最小のパーツとなるクラス名
+ Module ・・・ UIパーツを含むモジュールのクラス名
+ Skin ・・・　装飾用のクラス名
+ Number ・・・　ナンバリング用のクラス名
+ State ・・・　部品の状態を表すクラス名
+ Other ・・・その他のクラス名、サービス名やコントローラー名など

## 参考
+ Atomic Design http://atomicdesign.bradfrost.com/chapter-2/
+ APBCSS http://apbcss.com/
