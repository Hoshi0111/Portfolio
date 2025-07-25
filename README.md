# Portfolio

## 自己紹介
**西田星翔**<br>
にしだほしと<br>
<br>
京都大学情報学研究科に所属するエンジニア志望の大学院生です。<br>


## HEAL
５人チームでのWebアプリのプロトタイプ開発<br>
〇概要<br>
_Healthcare Empowerment through AI Linguistic_<br>
留学生などが自国以外で診療を受ける際、医師の質問や治療の説明をよく理解できない不安を解消するための診療補助システム<br>
〇機能<br>
・AIが具合の悪いところやいつから症状があるかなどの問診を母国語で行う<br>
・医者と患者の診察チャットではそれぞれの母国語に翻訳<br>
・診察時には医者側のチャットに含まれる医療用語をAIが判別し、タップすることで医療用語データベースから解説を提示、データベースになければ解説をAIが自動で生成<br>
〇工夫点<br>
・covid-19やcorona,covidなど同義で複数の言い方があるものを統一するために同義語テーブルを作成<br>
・医療用語データベースの内容は医者が書き換え可能で、医者の承認があるかどうか判別可能に<br>

<p align="center">
  <img src="./HEAL/images/patient_1.png" alt="Image 01" width="200">
  <img src="./HEAL/images/patient_2.png" alt="Image 02" width="200">
  <img src="./HEAL/images/doctor.png" alt="Image 03" width="200">
</p>

〇担当<br>
主にバックエンド<br>
DB処理・API実装・LLM接続<br>
〇使用ツール<br>
Python,Flask,SQLite,OpenAIAPI

## ちょろよい
５人チームでのモバイルアプリのプロトタイプ開発<br>
〇概要<br>
お酒があまり得意ではない人向けの飲み会支援アプリ<br>
スムーズな注文ができるように心がけて制作<br>
〇機能<br>
・メニュー表の写真からOCR技術を使用して商品名を抽出<br>
・アンケートから気分を入力しお酒を提案<br>
・杯数表示と飲みすぎ防止のための警告を行い、今までに飲んだお酒も記録される<br>
〇工夫点<br>
・お品書きにあるお酒のテキストをタップすると、そのお酒を注文するかどうか選択でき、長押しするとお酒の詳細が表示される。お酒にあまり詳しくなくてもすぐにどんなお酒か分かるように<br>

<p align="center">
  <img src="./Choroyoi/images/home.png" alt="Image 12" height="300">
  <img src="./Choroyoi/images/photo.png" alt="Image 13" height="300">
  <img src="./Choroyoi/images/extract.png" alt="Image 14" height="300">
  <img src="./Choroyoi/images/result.png" alt="Image 15" height="300">
</p>
〇担当<br>
主にフロントエンド<br>
画面遷移・表示処理・ログイン機能・全体デバッグ<br>
〇使用ツール<br>
TypeScript,HTML/CSS,ReactNative,firebase

## ゲーム
趣味で行っているチームまたは個人のゲーム開発<br>
〇使用ツール<br>
C#,Unity<br>

### ツチノコ見つけた（オンラインボードゲーム/開発中）
３人チームでのモバイルゲーム開発<br>
〇概要<br>
ツチノコとハンターに分かれて行うターン制のボードゲーム<br>
12×12マスの中でツチノコのいるマスをハンターが探索すればハンターの勝ち<br>
ツチノコはハンターに見つからずにアイテムを集めきれば勝ちとなる<br>
〇機能<br>
・オンライン対戦<br>
・CPU対戦<br>
〇工夫点<br>
・試行を繰り返しながらゲーム性を強化<br>
・ハンター側のCPUは強化学習を用いてAgentを作成<br>
〇担当<br>
インゲームシステム<br>

<p align="center">
  <img src="./Game/Tsuchinoko/Tsu_play_image1.jpg" alt="Image 211" height="300">
  <img src="./Game/Tsuchinoko/Tsu_play_image2.jpg" alt="Image 212" height="300">
  <img src="./Game/Tsuchinoko/Tsu_end_image.jpg" alt="Image 213" height="300">
</p>



### リンクスライダー（対戦型パズルゲーム）
Webで遊べるゲームを個人開発<br>
〇概要<br>
昔好きだったアニメに登場する二人対戦型のパズルゲームの再現<br>
２人のプレイヤーがスライダーを乗り継ぎしながら中央のマスに先に停止した方の勝ちとなる<br>
〇機能<br>
・CPUとの対戦(EASY/NORMAL/HARD/HELLの四つの難易度)<br>
・ローカル対戦<br>
・オンライン対戦(ランダムマッチ/プライベートマッチ)(時間制限あり)<br>
〇工夫点<br>
・もともとのゲームでは消極的な行動が最善となってしまう場合があるため、得点マスの機能を追加してゲームのバランスを調整。戦術の幅が広がってより面白くなった<br>
・CPUはMiniMax法のアルゴリズムを採用、より人間らしい動きをするように評価値を改善<br>
・画面遷移時やマッチング中のアニメーションを含め統一感のあるデザインに<br>


<p align="center">
  <img src="./Game/LinkSlider/LS_title.png" alt="Image 221" height="180">
  <img src="./Game/LinkSlider/LS_game.png" alt="Image 222" height="180">
  <img src="./Game/LinkSlider/LS_end.png" alt="Image 223" height="180">
  <img src="./Game/LinkSlider/LS_online.png" alt="Image 224" height="180">
</p>

[ここ](https://unityroom.com/games/link_slider)をクリックして遊ぶ<br>

### サイコロ麻雀（ミニゲーム）
Webで遊べるゲームを個人開発<br>
〇概要<br>
１４個のサイコロを振って役を作る１人用の暇つぶしゲーム<br>
ボタンをクリックするだけで遊べる<br>
〇機能<br>
・サイコロの出た目を取得し役判定を行う<br>
・今までに出た役は保持され一覧として表示<br>
〇工夫点<br>
100万回のシミュレーションを行ってレア度を設定<br>

<p align="center">
  <img src="./Game/DiceMahjong/DM_game.png" alt="Image 232" height="180">
  <img src="./Game/DiceMahjong/DM_end.png" alt="Image 233" height="180">
  <img src="./Game/DiceMahjong/DM_result.png" alt="Image 234" height="180">
</p>

少数ですが何人かTwitterで共有してくれました<br>

<p align="center">
  <img src="./Game/DiceMahjong/twitter_1.PNG" alt="Image 235" height="120">
  <img src="./Game/DiceMahjong/twitter_2.PNG" alt="Image 236" height="160">
  <img src="./Game/DiceMahjong/twitter_3.PNG" alt="Image 237" height="160">
</p>

[ここ](https://unityroom.com/games/dice_mahjong)をクリックして遊ぶ<br>

### そのほかのゲーム

## 研究
〇概要<br>
アバターロボットと呼ばれる遠隔操作分身ロボットを用いた接客は場所を問わない点や衛生面で魅力的<br>
これを用いてカスタマーハラスメント対策システムを開発<br>
〇手法<br>
ワーカーインタビューを通じて丁寧な口調がストレスを感じにくいという知見を得る<br>
顧客の音声を排除し、丁寧な印象のテキストに変換して表示させるシステムを考案<br>
音声合成の機能を追加し実験を行う<br>
〇工夫点<br>
・顧客側がラグを感じさせないようにフィラーを入れたりロボットに動きを追加したり<br>
・音声認識への不安を軽減するため、リプレイボタンを追加して音声を聞ける機能を追加<br>
・クレームの文を200以上集めてテキスト変換を行いながらプロンプトを改良<br>

<p align="center">
  <img src="./Research/images/research_aproach.png" alt="Image 32" height="100">
  <img src="./Research/images/system_overview.png" alt="Image 31" height="200">
</p>
〇使用ツール<br>
Python,ROS,Whisper(OpenAI),GPT4o

## インターン
### LLMを用いたWebアプリ
４人チームでのアプリ開発<br>
〇担当<br>
バックエンド<br>
DB設計・機能設計・LLM処理<br>
〇使用ツール<br>
Python,FastAPI,mySQL,OpenAIAPI,BingSearchAPI,langchain

### 経路探索APIを利用したWebアプリ
２人チームでのフロントエンドアプリ開発<br>
〇使用ツール<br>
JavaScript,Vue

