# Portfolio

## 自己紹介
**西田星翔**<br>
にしだほしと<br>
<br>
好きなこと<br>
・野球観戦　父の影響で幼少期から阪神ファンです。<br>
・ゲーム　友人とFPSをよくやります。野球ゲームが大好きです。シミュレーションゲームも好きです。<br>
・ボードゲーム　将棋が結構得意です。麻雀も好きです。友人とBGAをたまにやります。<br>
・パズル　アニメの影響で小学生のころドはまりしました。カックロがものすごい得意でした。<br>
・卓球　高校は卓球部でした。ひたすらフットワークをやってました。<br>

## HEAL
５人チームでのWebアプリのプロトタイプ開発<br>
・概要<br>
_Healthcare Empowerment through AI Linguistic_<br>
留学生などが自国以外で診療を受ける際、医師の質問や治療の説明をよく理解できない不安を解消するための診療補助システム<br>
・機能<br>
AIが具合の悪いところやいつから症状があるかなどの問診を母国語で行う<br>
医者と患者の診察チャットではそれぞれの母国語に翻訳<br>
診察時には医者側のチャットに含まれる医療用語をAIが判別し、タップすることで医療用語データベースから解説を提示、データベースになければ解説をAIが自動で生成<br>
・工夫点<br>
covid-19やcorona,covidなど同義で複数の言い方があるものを統一するために同義語テーブルを作成<br>
医療用語データベースの内容は医者が書き換え可能で、医者の承認があるかどうか判別可能に<br>

<p align="center">
  <img src="./HEAL/images/patient_1.png" alt="Image 01" width="200">
  <img src="./HEAL/images/patient_2.png" alt="Image 02" width="200">
  <img src="./HEAL/images/doctor.png" alt="Image 03" width="200">
</p>
・担当<br>
主にバックエンド<br>
DB処理・API実装・LLM接続<br>
・使用ツール<br>
Python,Flask,SQLite,OpenAIAPI

## ちょろよい
５人チームでのモバイルアプリのプロトタイプ開発<br>
・概要<br>
お酒があまり得意ではない人向けの飲み会支援アプリ<br>
スムーズな注文ができるように心がけて制作<br>
・機能<br>
メニュー表の写真から商品名を抽出<br>
アンケートから気分を入力しお酒を提案<br>
杯数表示と飲みすぎ防止のための警告を行い、今までに飲んだお酒も記録される<br>
・工夫点<br>
お品書きにあるお酒のテキストをタップすると、そのお酒を注文するかどうか選択でき、長押しするとお酒の詳細が表示される。お酒にあまり詳しくなくてもすぐにどんなお酒か分かるように<br>

<p align="center">
  <img src="./Choroyoi/images/home.png" alt="Image 12" height="300">
  <img src="./Choroyoi/images/photo.png" alt="Image 13" height="300">
  <img src="./Choroyoi/images/extract.png" alt="Image 14" height="300">
  <img src="./Choroyoi/images/result.png" alt="Image 15" height="300">
</p>
・担当<br>
主にフロントエンド<br>
画面遷移・テキスト処理・ログイン機能・全体デバッグ<br>
・使用ツール<br>
TypeScript,HTML/CSS,ReactNative,firebase

## ゲーム
個人開発<br>
・使用ツール<br>
C#,Unity,PUN2,Blender
### オンラインFPS
・概要<br>
複数人のオンラインで遊べるFPSゲーム<br>
弾を当てれば点数が増え、当たられたらＨＰが減るだけの単純な内容
（ＨＰが０になれば派手に爆散します）<br>
ワールドは作成者の高校の教室を再現<br>

<p align="center">
  <img src="./Game/FPS/screen1_fps.png" alt="Image 211" height="120">
  <img src="./Game/FPS/screen2_fps.png" alt="Image 212" height="120">
  <img src="./Game/FPS/screen3_fps.png" alt="Image 213" height="120">
</p>

### 対戦型パズルゲーム
・概要<br>
二人対戦型のパズルゲームの再現<br>
オンライン対戦とローカル対戦が可能<br>
[ここ](https://unityroom.com/games/link_slider)をクリックして遊ぶ

<p align="center">
  <img src="./Game/LinkSlider/title_LS.png" alt="Image 221" height="150">
  <img src="./Game/LinkSlider/game_LS.png" alt="Image 222" height="150">
</p>

### ミニゲーム
・概要<br>
１人用の暇つぶしゲーム<br>
ボタンをクリックするだけで遊べる<br>
[ここ](https://unityroom.com/games/dice_mahjong)をクリックして遊ぶ<br>

<p align="center">
  <img src="./Game/DiceMahjong/title_dcmj.png" alt="Image 231" height="150">
  <img src="./Game/DiceMahjong/dice_dcmj.png" alt="Image 232" height="150">
  <img src="./Game/DiceMahjong/result_dcmj.png" alt="Image 233" height="150">
</p>

少数ですが何人かTwitterで共有してくれました<br>

<p align="center">
  <img src="./Game/DiceMahjong/twitter_1.PNG" alt="Image 234" height="120">
  <img src="./Game/DiceMahjong/twitter_2.PNG" alt="Image 235" height="160">
  <img src="./Game/DiceMahjong/twitter_3.PNG" alt="Image 236" height="160">
</p>

## 研究
・概要<br>
アバターロボットと呼ばれる遠隔操作分身ロボットを用いた接客は場所を問わない点や衛生面で魅力的<br>
これを用いたカスタマーハラスメント対策システムを提案する<br>
・手法<br>
ワーカーインタビューを通じて丁寧な口調がストレスを感じにくいのでは<br>
顧客の音声を排除し、丁寧な印象のテキストに変換して表示させるシステムを考案<br>
・工夫点<br>
顧客側がラグを感じさせないようにフィラーを入れたりロボットに動きを追加したり<br>
音声認識の不安を軽減するため、リプレイボタンを追加して音声を聞ける機能を追加<br>
クレームの文を200以上集めてテキスト変換を行いながらプロンプトを改良<br>

<p align="center">
  <img src="./Research/images/research_aproach.png" alt="Image 32" height="100">
  <img src="./Research/images/system_overview.png" alt="Image 31" height="200">
</p>
・使用ツール<br>
Python,ROS,Whisper(OpenAI),GPT4o

## インターン
### LLMを用いたWebアプリ
４人チームでのアプリ開発<br>
・担当<br>
バックエンド<br>
DB設計・機能設計・LLM処理<br>
・使用ツール<br>
Python,FastAPI,mySQL,OpenAIAPI,BingSearchAPI,langchain
### 経路探索APIを利用したWebアプリ
２人チームでのフロントエンドアプリ開発<br>
・使用ツール<br>
JavaScript,Vue

