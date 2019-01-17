# GlobalHookProject
複数のウィンドウをグループ化して一括管理することを目的としたアプリケーションです。

## 機能
+ 指定キーを押下してウィンドウを他のウィンドウにくっつけるとグループになります。  
    + 非グループのウィンドウを移動
	    + 非グループのウィンドウにくっつける：新規グループ
		+ グループのウィンドウにくっつける：そのグループに追加
	+ グループのウィンドウを移動
	    + 非グループのウィンドウにくっつける：そのグループに追加
		+ グループのウィンドウにくっつける：ウィンドウをそのグループに移動
+ グループ単位の機能  
    + ウィンドウの表示・最小化の切り替え  
    + ウィンドウを閉じる  
    + ウィンドウをタイル状に並べる  
    + グループ内のアプリケーションを保存する  
+ ウィンドウが他のウィンドウ・タスクバー・画面の端にくっつきます。  
+ 指定キーを押下したままウィンドウを移動させると隣接ウィンドウも同時に移動します。  

## 動作環境
Windows10  
64bitのアプリケーション 

動作しないもの（確認したもののみ）  
+ 32bitのアプリケーション  
+ Excel、WordなどのMicrosoftOffice  
+ タスクマネージャーなどのシステムアプリケーション  
+ UWPアプリ  

## 既知のバグ
+ ランチャーが非表示にならない時がある
+ スケールが大きい場合に、ウィンドウを同時移動すると勝手に移動するウィンドウがある場合がある
+ 

## 作者

[hn20156066](https://github.com/hn20156066)
