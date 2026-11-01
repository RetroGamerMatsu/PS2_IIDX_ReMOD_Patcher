# PS2_IIDX_ReMOD_Patcher
このパッチはClaude Codeを用いて作られています  
実機（OPL）でプレイする場合はISOに直接パッチを当てる必要があります

PS2版IIDXで17 SIRIUS以降の機能を使えるようにするパッチです  
PCSX2,OPLでの動作を確認済

## 現在の対応状況
15 DJ TROOPERS  
16 EMPRESS + PREMIUM BEST

14以前の作品も対応予定です（8th以前、特に5th以前の作品はできる範囲でやります）
US版は未定です

## 追加機能

### LIFT (17 SIRIUS)
判定幅を上下に動かすことができます （SUDDEN+と併用可能）  
PS2の作品はレーンカバーが1つしか指定できないのでSUDDEN+と同じものがカバーとなりますが、可能であれば別々に設定できるようにする予定です

### FAST/SLOW （17　SIRIUS）
判定が黃GREAT以下のときのタイミングのズレを表示します
設定方法は17 SIRIUS〜19 Lincleのものを参考にしています
リザルト画面でのFAST/SLOWの数（20 tricoro）も実装されています

### EX-HARD (19 Lincle)
HARDよりもゲージの減少が激しくなるオプションです  
専用のランプ・クリアフォルダ実装済み  
内部的にはHARDクリアの扱いなのでパッチを外すとHARDクリアとして扱われます（再びパッチを当てるとEX-HARDクリア扱いに戻ります）

### DJLEVEL VIEW (34 ZINRAI)
選曲画面でLEVELの数字の横にプレイした曲のランクが表示されます
