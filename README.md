# KPTとは
KPTをご存知でしょうか。振り返りのためのフレームワークです。
KPTとは、Keep, Problem, Tryの頭文字をつなげたもので、

Keep=良かったこと。
Problem=問題だったこと。
Try=次にやりたいこと、試してみたいこと。

を洗い出すことで、改善を進めていく方法です。

# KPTを使った振り返りの方法
振り返りでは、まずKeepを洗い出しましょう。
それは、振り返りではどうしても自罰的な雰囲気になりがちなためです。
成長をするためには、成功パターンをイメージできなければならないので、自罰はそれの妨げになります。
Keepを最初に洗い出すことで、振り返りを明るい雰囲気にします。
次にProblemを洗い出します。問題を明確にしましょう。また、問題を発見したら、その原因を掘り下げ、問題への対処をTry化します。
最後にTryを洗い出します。自分たちを成功へと導く改善活動を起案していきます。
振り返りが終わったら、記録のためにSnapshotをとっておきましょう。

振り返りは定期的に行うことで改善を続けましょう。
２回め以降の振り返りでは、前回のTryが達成できたかを確認します。
できていることが確認できたら、Tryの項目をKeepに移動します。Tryが出来なかったとしたら、できるTryに変換しましょう。
Tryを見なおせたら、またKeepから洗い出していきます。

# セットアップ
KPT toolはnodeを利用しています。セットアップの前にnodeをインストールしてください。
セットアップは簡単です。４コマンドで実行できます。
```bash:セットアップ方法
git clone -b master https://github.com/ukiuni/KPT.js.git
cd KPT.js
npm install
nohup node kpt.js &
```
http://localhost:3000 にアクセスすると、KPTツールが利用できます。

# KPT toolの使い方
ブラウザでアクセスした後、プロジェクト名を入力して、プロジェクトを作成します。
*表示された画面のURLはあとからは取得できません。ブックマークやメモを行ってください。*
表示される画面で「+」ボタンを作成すると、新しい項目を作成できます。
項目はクリックして編集ができます。ドラッグすることで順番の入れ替えや、Keep、Problem、Tryへの変更ができます。
状態を記録するためには、メニュー右側の「Snapshot」を押してください。新しいウインドウでSnapshotが表示されます。SnapshotのURLも保持しておいてください。