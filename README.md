作業中です。
----

# slag

Unity用組込スクリプトシステム

## 概要

Unityアプリケーション上で実行できるスクリプトシステムを提供

## 特徴

* アプリケーションからロード＆実行
* マルチプラットフォーム
* スクリプトからエンジン・アプリケーションへシームレスな操作が可能
* Javascriptライクな文法で、Javascript対応のエディタを使うことが可能
* コンパイルを省いたバイナリデータからの実行が可能  
* 簡易デバッガ提供(Windowsのみ) 
* チェックサムによる改竄防止

## 用途
  
### 1．アプり配布後に動作またはデータを柔軟に変更

サーバ上に用意したスクリプトを読込ませることで、アプリの動作やデータを変更することが可能。      
これにより、致命的バグ・仕様変更に柔軟に対応することが可能。  

### 2. 実行バイナリ上でのテストコード実行

スクリプトでテストコードを書くことにより、実行バイナリ上で柔軟なテストが可能となる。 
  
### 3．実行バイナリを変更せず、ツールとして使用

スクリプトでツールコードを書くことで、実行バイナリを変更せずにツールとして使うことが可能。
製品に限りなく近いため、品質とパフォーマンスを同時に確認することが出来る。  

#### 利用例  
* メニューエディタ  
* カットシーン   
* レベルエディタ

### 4．開発の最適化

スクリプトとアプリの連携を計画的に行うことで柔軟なシステムを構築することが出来る。  
開発の各フェーズで効果が発揮でき、特に開発終盤の調整段階で多大な貢献が期待できる。

## 使い方・その他
  
[Wiki](https://github.com/NNNIC/slag/wiki)  

