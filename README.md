# hsptv_forum_mute
hsptv!forum mute-plus  

機能  

HSPTV!掲示板（https://hsp.tv/play/pforum.php ）にミュート機能を追加します。  
特定ユーザ名と投稿内容を非表示にできます。  
ミュートワードとしても利用できます（ただしユーザ名優先）  
この機能はユーザ名などの設定をローカル保存しています。  

![Image](https://github.com/user-attachments/assets/7be80815-0e06-4467-a08d-199f7a0b5859)

-----  
インストール  

ブラウザのGreasemonkey系の拡張機能(Tampermonkey)にて利用するユーザースクリプトとなります。  
対応ブラウザと拡張機能についてはGreasy Fork（https://greasyfork.org ）などを参照してください。  

Chromeブラウザでのインストール  
１．Chromeウェブストアから拡張機能のTampermonkeyを追加します。  
２．手動の場合は、Tampermonkeyにて「新規スクリプトを追加」を行います。  
Greasy Forkを利用してインストールする場合には以下となります。  
https://greasyfork.org/ja/scripts/524054-hsptv-forum-mute-plus  
３．HSPTV!掲示板にて右下に(M)ボタンがあれば動作しています。  

ChromeにてTampermonkey拡張機能を利用するには、デベロッパーモード(開発者モード)が  
有効であることを確認してください（Manifest V3の仕様らしいです）  

-----  
使用について  

この機能を利用することで、特定ユーザの投稿を非表示にできたり  
非表示キーワードとして扱うことが出来ます。  

この機能は、不快な投稿から距離を取る権利を尊重するために制作されました。  
例えば、仕事や学校でストレスを感じる場合、それらの環境から距離を取ることが  
大切であるように、掲示板でも嫌な投稿を避ける権利があります。  
この機能は、一般的なSNSで採用されているミュート機能に近いものです。  

利用によるトラブルについては責任を負いませんので、ご了承の上でご利用ください。  
この機能は掲示板上の一部の投稿内容を見れなくするためのものであり、  
それに伴う影響についてはご自身で判断し、対処していただく必要があります。

-----  
使用上の注意  

IPアドレスによるミュートは行っていませんので  
ユーザ名のなりすましや重複するユーザ名の場合には全てミュート対象となります。  
aやmesなど短いユーザ名やHSP命令、正規表現の利用により多くの条件が該当する場合があります。  
ミュート数の上限は設けていませんので多すぎると負荷がかかることがあります。  

-----  
この機能の制作の発端は以下のスレッドとなります。  
https://hsp.tv/play/pforum.php?mode=all&num=102883  
Chrome＋Tampermonkey拡張機能＋ChatGPTにて開発・動作確認しています。
