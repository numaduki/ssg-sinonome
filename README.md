# sinonome  

## 概要

Windows用静的サイトジェネレータです。  
特別な環境を用意せずに、ウェブサイトを作成できます。

1. ブログ記事やウェブページなどのテキストを書く  
2. 独自タグとHTMLタグを使ってテンプレートを書く  
3. sino.exeを実行してファイルを出力

という作業の流れで、サイトファイル一式を出力します。


## クイックスタート

sino.exe をダブルクリックして実行します。  
既にサンプルデータが入っており、サンプルサイトが出力されます。

詳しい使い方はウェブサイトの解説をご参照ください。


## 想定される利用シーン

- テキストメインの小規模ブログを作成したい
- ローカルマシンでも見られるHTMLマニュアル類を作成したい  
  など

小規模なHTML一式を出力するのに向いています。

オリジナルのテーマを作ることもできますが、その場合もHTMLに似たテンプレートタグを使うので、おそらくとっつきやすいと思います。


## アンインストール方法

インストールファイルを全て削除してください。
レジストリへの書き込みや、インストールディレクトリ以外へのファイル出力は行っていません。


## ご注意

- 本ソフトウェアは完全に制作途中であり、うまく動作しない・動作が不安定などの可能性があります。
- 今後、大幅な仕様変更を行う可能性があります。  
- ソースコードを見ることはできますが、全く整理されておらず、著しく可読性が低いことをご了承ください。


## sinonome のライセンス

-	現在検討中であり、ライセンスは付与していません。  
	したがいまして、改変の有無を問わず、再頒布はお控えください。  
	（いずれは自由に使ってもらいたいと考えていますので、その際には何らかのライセンスを付与すると思われます）


## 使用しているライブラリ類のライセンス

### Yet Another AYA - YAYA（修正BSDライセンス）

```
Copyright (c) 2007-, 整備班  
All rights reserved.  
http://ms.shillest.net/

ソースコード形式かバイナリ形式か、変更するかしないかを問わず、以下の条件を満たす場合に限り、再頒布および使用が許可されます。

・ソースコードを再頒布する場合、上記の著作権表示、本条件一覧、および下記免責条項を含めること。  
・バイナリ形式で再頒布する場合、頒布物に付属のドキュメント等の資料に、上記の著作権表示、本条件一覧、および下記免責条項を含めること。  
・書面による特別の許可なしに、本ソフトウェアから派生した製品の宣伝または販売促進に、「整備班」の名前または貢献者の名前を使用してはならない。

本ソフトウェアは、著作権者および貢献者によって「現状のまま」提供されており、明示黙示を問わず、商業的な使用可能性、および特定の目的に対する適合性に関する暗黙の保証も含め、またそれに限定されない、いかなる保証もありません。著作権者も貢献者も、事由のいかんを問わず、 損害発生の原因いかんを問わず、かつ責任の根拠が契約であるか厳格責任であるか（過失その他の）不法行為であるかを問わず、仮にそのような損害が発生する可能性を知らされていたとしても、本ソフトウェアの使用によって発生した（代替品または代用サービスの調達、使用の喪失、データの喪失、利益の喪失、業務の中断も含め、またそれに限定されない）直接損害、間接損害、偶発的な損害、特別損害、懲罰的損害、または結果損害について、一切責任を負わないものとします。
```

### fpc-markdown: Markdown Processor for FPC (Apache License 2.0)

```
Copyright (C) Miguel A. Risco-Castillo

FPC-markdown implementation is a fork of Grahame Grieve pascal port Delphi-markdown

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

```
