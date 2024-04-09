## 動作環境
Python = 3.9.10  
最新版だと対応していないライブラリ有り  
本研究ではPythonのライブラリ管理にはpip 
また、termextract別途インストールの必要。[こちら](https://github.com/kanjirz50/termextract)

## 本リポジトリ内の内容
Japanese_importance_pricessing_ginzaでは、形態素解析ライブラリにginzaを用いてその後TF-IDFで重み付け
Japanese_importance_pricessing_termextractでは形態素解析ライブラリにjenomeを用いてその後TF-IDFで重み付け
## 補足
実際の実験では、書籍データを約200ほど抽出して実験。  
形態素解析とは、文章を意味を持つ最小の単位(＝形態素)に細分化し、一つひとつの品詞・変化などを判別していく作業    
TF-IDFとは、TF(その文章中で特定の単語がどれだけ登場するか)×IDF(その他の文章と比較して特定の単語がどれほど希少であるか)という計算結果  
