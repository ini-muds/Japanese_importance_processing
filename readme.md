# 本リポジトリについて
## 数学参考書を対象とした重要語抽出によるメタデータ生成方式と学習者の学習進度に合致した参考書推薦システムの実現に関する研究
本リポジトリは上記タイトルで行った研究で利用していたコードになります。  
主に日本語ライブラリによる形態素解析とTF-IDFによる重み付けを行なっております。  
今後自然言語処理にチャレンジする方々に対して少しでもアシストになれば幸いです。  
  
## 動作環境
Python = 3.9.10  
最新版だと対応していないライブラリもあるのでご注意ください。  
本研究ではPythonのライブラリ管理にはpipを用いております。  
また、termextract別途インストールの必要があります。[こちら](https://github.com/kanjirz50/termextract)をご参照ください。  

## 本リポジトリ内の内容
Japanese_importance_pricessing_ginzaでは、形態素解析ライブラリにginzaを用いてその後TF-IDFで重み付けを行なっております。
Japanese_importance_pricessing_termextractでは形態素解析ライブラリにjenomeを用いてその後TF-IDFで重み付けを行なっております。
## 補足
実際の実験では、書籍データを約200ほど抽出して実験を行いました。  
形態素解析とは、文章を意味を持つ最小の単位(＝形態素)に細分化し、一つひとつの品詞・変化などを判別していく作業です。    
TF-IDFとは、TF(その文章中で特定の単語がどれだけ登場するか)×IDF(その他の文章と比較して特定の単語がどれほど希少であるか)という計算結果です。  
