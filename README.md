# 職務経歴書
## 基本情報
エンジニアとして、フロント・バックエンド・サーバーサイドの2年7ヶ月の保守/運用実務経験があります。

<table>
    <tr>
        <td><strong>氏名</strong></td>
        <td>石川 哲平(いしかわ てっぺい)</td>
    </tr>
    <tr>
        <td><strong>生年月日</strong></td>
        <td>1995年6月1日</td>
    </tr>
    <tr>
        <td><strong>Qiita</strong></td>
        <td>https://qiita.com/mikohiki</td>
    </tr>
</table>

## 野望
私自身の野望としては、「この人がいれば場の流れを変えられる」と思われる本物のフルスタックエンジニアになることです。

#### 理由
「本物の存在」になることが私自身が人生を通して成し遂げたいことなため。  
また、幼馴染3人や尊敬するエンジニアの先輩と起業なり仕事を通してワクワクするような仕事を行いたいので、なんでもできるフルスタックエンジニアになる必要があります。  
(ワクワクするような仕事 = この世でまだ気付かれてないけど、テクノロジーなどで解決できたらとても効率的になること)

#### 計画
現在26歳なので、30歳までに一通りの技術や経験を積みたいと考えています。  
なので、スカウトを頂いた会社様では開発業務をメインに行いたいと思っております。  
Railsなどのバックエンドが一番得意なので、決済追加開発のような重めの開発タスクなどなんでも挑戦したいです。Reactも実務経験済みなのでReactなどを使った開発機会がありましたら挑戦したいです。
後にサーバーサイドにも今以上に精通することを目指しています。

ビジョン
<table>
    <tr>
        <td><strong>2019年〜2022年?</strong></td>
        <td>フルスタックで保守(26歳)</td>
    </tr>
    <tr>
        <td><strong>2022年〜2023年</strong></td>
        <td>開発(27歳)</td>
    </tr>
    <tr>
        <td><strong>2023年〜2025年</strong></td>
        <td>サーバーサイド・開発(29歳)</td>
    </tr>
    <tr>
        <td><strong>2025年〜</strong></td>
        <td>フルスタック(30歳)</td>
    </tr>
</table>

## 長所・短所
- 長所: 負けず嫌い  
  入社当時は誰よりもソースを書く・読む速度が遅かったが、寝る時間以外全てソースコードを読み実力がついたため、社員130人の中で10%の人がもらえる評価を得た。

- 短所: 熱しやすくて冷めやすい  
  興味を持つが一気に集中して実行するため、目標を達成するとすぐに他の興味があるものを行ってしまう。

## 価値観
- 世界は解釈の問題
- どんなに良いプロダクトや技術があったとしても、人やチームが良くなければ物事はうまくいかない。逆に人やチームが良ければ、現状悪いプロジェクトでも未来は明るい。

## スキル
- Ruby: 2.7年
- Ruby on Rails: 2.7年
- react: 2.7年
- redux: 2.7年
- JavaScript: 2.7年
- jQuery: 2.7年
- html: 2.7年
- css: 2.7年
- linux: 2.7年
- PostgreSQL: 2.7年
- Elastic serch: 2.7年

## 学歴・職歴

| 年月 | 学歴・職歴 | 備考 |
|:---|:---|:---|
|2015年 ~ 2019年|獨協大学法学部法律学科|法哲学を学ぶ|
|2018年|短期集中プログラミングスクール TECH::EXPERT(株式会社div) 入学|Ruby on Railsを用いたwebアプリケーションを作成。TECH::EXPERT初の新卒卒業生|
|2019年 ~ 現在|株式会社テモナ入社|webアプリケーションエンジニアとして新卒入社。3年目に保守チームのリーダーに昇格|

## 職務経歴
## 2019年4月 ~ 現在: 株式会社テモナ(正社員として在籍)
### ①期間内訳
- 2019年4月 ~ 2019年8月
#### プロジェクト
- 既存通知機能の機能削除と機能開発
#### 概要
- 通知機能で不要なお気に入り機能の削除、「対応/未対応」確認機能の実装、通知ログ削除バッチ処理の開発
#### 使用技術
- Ruby, Ruby on Rails, JavaScript, CoffeeScript,PostgreSQL, CSS, HTML
#### 業務内容兼課題
1. 通知機能に「対応/未対応」確認機能がなかったため、機能の実装

#### 課題解決のための取り組み
1. 通知機能に新たな機能を追加するだけでは、UIが複雑になりユーザーの利便性が低下する可能性があったため、不要機能の洗い出し
2.  通知機能の「対応/未対応」確認機能の実装とは別に、通知ログデータを削除するバッチ機能の開発。

#### 工夫した点と成果
1. 弊社サービス利用400ショップに対して、シェルスクリプトで不要機能に関係するカラムの利用状態がfalseかつupdated_atが直近1年以上前のショップを洗い出し、利用ショップがいないことを確認した上で対象ソースコードを削除致しました。
2. 通知ログのデータは、システム上CRUD処理に関する動作に紐づいて作成されることが多いため、データ量が必然的に多くなってしまうと考えました。そのため開発とは直に関係ありませんでしたが、永続的にデータを保持するのではなく、半年以上前に作成されたものは削除するようバッチ処理の実装も追加で対応致しました。

---
### ②期間内訳
- 2019年8月 ~ 2021年3月
#### プロジェクト
- 保守グループの運用/保守メンバー
#### 概要
- サブスクリプション実装サービスにおける、利用店舗400ショップを対応する保守チームのメンバー
#### 使用技術
- Ruby, Ruby on Rails, JavaScript, React, Redux, CoffeeScript,PostgreSQL, Zabbix, Nginx, Unicorn, CSS, HTML, Redis, Linuxコマンド, Elastic serch, BackLog
#### 業務内容兼課題
1. ソースコードを読む速さやデバック、検証スキルがなく業務をスピーディーに対応することが不可能な状態。
2. 保守メンバーが私と先輩エンジニア1人にも関わらず、毎日10件近くくるバグ・仕様確認やバックエンド・フロントエンド・インフラ問わずくるサービス全体の修正対応。
#### 課題解決のための取り組み
1. デジタルオーシャンで仮想サーバーを借りて、自宅で弊社提供サービスと同じLinux, Unicorn, Nginx, PostgresSQL, Rails環境を作り、webサービス全体の大枠のイメージと流れを勉強致しました。
2. 入社してから2年間,業務終了後の18:30から独学であったり、保守チームの先輩を誘い24時まで,grep,awkなどのlinuxコマンドの仕様方法やrailsのblankやpresentメソッドの違いなど必要な知識を毎日学習致しました。
#### 工夫した点と成果
1. Rails, JavaScript, Reactなどの概念を頭の中でイメージできるように該当言語が生まれた歴史から学習。そのことによって、言語の特徴を理解することが早いキャッチアップにつながることを学びました。また、同じような悩みを来年度の新卒エンジニアが抱えると考え、アウトプットも兼ねて独断でドキュメントを作成致しました。
2. できるエンジニアと私自身の差分が何かを客観的に観察し、キーボード・マウス・エディターなどのインターフェイスをできる人に揃えたり、どういう考え方でソースコードを読もうとしているのかなどの、指向方法まで真似ました。観察してみたところ、頭の中でバグるパターンの仮説を立てた上でソースコードを読んでいることに気付き、私自身も求めてるゴールとバグが生じる差分の原因を仮説を立てながら考えたところ、毎日10件近くくるバグ・仕様確認の対応可能件数が1,2件から5,6件に増え、先輩と2人でも保守チームを回せるようになりました。

---
### ③期間内訳
- 2021年3月 ~ 2021年10月
#### プロジェクト
- 保守グループの運用/保守メンバー兼保守グループリーダー
#### 概要
- サブスクリプション実装サービスにおける、利用店舗400ショップを対応する保守チームのメンバー兼リーダー
#### 担当
- リーダー兼バックエンド、フロントエンド、インフラを対応する1メンバーとして以下を担当
#### 使用技術
- Ruby, Ruby on Rails, JavaScript, React, Redux, CoffeeScript,PostgreSQL, Zabbix, Nginx, Unicorn, CSS, HTML, Redis, Linuxコマンド, Elastic serch, BackLog,
#### 業務内容兼課題
1. 先輩エンジニアと私の2人3脚で400ショップ様の対応を行なっていたが、先輩エンジニアが抜け、私がチームリーダとなり新卒5人をまとめるチーム作り。
2. 1000万円の補填になりそうな大きなバックエンドのバグ対応や、バグ対応に伴う1000~5000件のデータ更新作業。
3. 会社初の協力会社様を保守作業にジョインしてもらうための外部会社との連携作業。
#### 課題解決のための取り組み
1. リーダーとして、保守チームが回るようになるように、保守メンバーが自走できるような仕組みづくりを自ら行いました。
2. 保守チームが対応すべき、修正チケットやバグ・仕様確認の未対応チケットが50件ほど溢れている状態から、半年で平均8件まで減らすことを達成致しました。
3. 1000万以上の補填になりそうな保守対応は、データ数が1000~5000件だったりすることもあるため、SQLで不具合データを洗い出せるようにRuby以外の言語でも対応できるよう技術の幅を伸ばす。また、言語に対する理解が浅い場合二次被害を産むことがあるので、根底の理解をできるように再度railsの学習や、apiなどのもっと知識の幅を深める学習を行いました。
#### 工夫した点と成果
1. いつでも質問していいよと言うだけではなく、質問できる環境を作ることからスタート致しました。具体的にはランチをこちらから誘い、その人となりを理解することから努め、その人の物の考え方や学習方法のスタイルなどを理解した上でその人に会う質問の答え方や勉強方法を教えました。
2. 業務対応速度が上がったとしても、根本の不具合件数を撲滅しなければ本質的な解決にならないため、多い不具合のジャンルをチケットベースで洗い出し、問題となってる箇所が決済周りの不具合やデータ更新と判明。判明した上で決済周りのrspecの強化を行なったり、データ更新が必要になってしまっていた原因の、sidekiqの非同期更新時のバッチ処理対応を行いました。
3. 更新対象の件数が1000件を超えると、ただupdate文で更新するだけでは、楽観ロックやデータ更新中に対象データの状態が変わることも考えられるので、トランザクションやrescue処理を設けて、ローカル検証段階で遭遇しなかった自分が想定していないパターンが生じても問題内容な更新スクリプトを作成致しました。

本当に簡単な例ですが、scriptになります。

```
target_user_ids = [1,2,10,20,21,22,...]
# update_failure_listsは更新失敗したUserのidとその時のエラーメッセージを格納する空配列
update_failure_lists = []

def updates_data user, update_failure_lists
  ActiveRecord::Base.transaction do
    # ここに正しく更新したい内容記述
    user.update!(name: 'hogehoge')
  end
rescue => e
    # 開発だけではなく、consoleでの更新時でもイレギュラーを想定してrescue処理は欠かさない
  error_message = "Reason::" + e.message
  update_failure_lists << [user.id, error_message]
end


User.where(id: target_user_ids).each do |user|
  updates_data user, update_failure_lists
end
```

# その他
~2021年10月勉強中の本~

持論として、物事を考える際は「全体から細部へ」の流れで学習することが大切だと考えています。  
そのため、復習も兼ねて再度オブジェクト指向の生まれた歴史など時間がかかりそうな内容を学習しております。

オブジェクト指向でなぜつくるのか 第3版 知っておきたいOOP、設計、アジャイル開発の基礎知識
https://www.amazon.co.jp/%E3%82%AA%E3%83%96%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E6%8C%87%E5%90%91%E3%81%A7%E3%81%AA%E3%81%9C%E3%81%A4%E3%81%8F%E3%82%8B%E3%81%AE%E3%81%8B-%E7%AC%AC3%E7%89%88-%E7%9F%A5%E3%81%A3%E3%81%A6%E3%81%8A%E3%81%8D%E3%81%9F%E3%81%84OOP%E3%80%81%E8%A8%AD%E8%A8%88%E3%80%81%E3%82%A2%E3%82%B8%E3%83%A3%E3%82%A4%E3%83%AB%E9%96%8B%E7%99%BA%E3%81%AE%E5%9F%BA%E7%A4%8E%E7%9F%A5%E8%AD%98-%E5%B9%B3%E6%BE%A4-%E7%AB%A0/dp/4296000187/ref=sr_1_1?__mk_ja_JP=%E3%82%AB%E3%82%BF%E3%82%AB%E3%83%8A&keywords=%E3%82%AA%E3%83%96%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E6%80%9D%E8%80%83&qid=1637084333&s=books&sr=1-1
