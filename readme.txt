dispImage.exe

プログラムの概要

	Imageクラスおよび、CImageクラスによる画像のロード、編集、セーブを行うテスト・プログラムです。

	マウスによる画像スクロール、マウス・ホイールによるスクリーンセンター中心のズーム。
	Gdiplusによる、なめらかフリーハンドラインの描画。
	RichTextEditerを利用した透明テキストエディタによる画像への回転テキスト出力。
	画像の選択範囲外を透明化（アルファpng作成）。
	カラー選択ダイアログ。
	フォント選択ダイアログ。
	などの機能をもっています。

	対応画像フォーマットは、jpg, bmp, png, tif（サイズは16000×16000pixelまで）。
	それ以上の画像は、自動でリサイズされます。



開発環境
	Windows 11
	Visualstudio 2022    VC++ MFC

	クラス
	CdispImageDlg　	メイン
	Cbutton			ボタン
	Cdata			イメージ・ロード、セーブ
	Cshape			図形描画
	Ctext				テキスト描画
	CcolDlg			カラー選択ダイアログ
	CfontDlg			フォント選択ダイアログ



