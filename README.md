# 課題1提出用のディレクトリです。
* theme1.htmlは課題1のhtmlファイルです。  
* style1-10.cssは課題1のcssファイルです。  
* img1-9はHTML・CSSを学ぼう9章演習問題2のchapter9_exercise/imgにある画像ファイルです。

## 再提出修正内容。
* CSSの@media screen and (max-width: 425px)を@media screen and (max-width: 768px)へ修正しました。
* CSSの@media screen and (max-width: 768px)での.step-boxの marginを: 0 5% 5% 20px;から: 0  5% 20px 5%へ修正しました。
* CSSの.step-box:last-child {margin-right: 0;}でmargin-rightがレスポンシブ対応でもmargin-rightが0になっているため、
  @media screen and (max-width: 768px)での .step-box:last-childの margin-rightを: 5%;(margin-leftは5%になっていますが念のため)に修正しました。