# application
■サービス概要
どんなサービスなのかを３行で説明してください。

・ユーザーが登録したレシピから栄養バランス(完全ではなくてよい)を考え、前日の献立を鑑みた献立を作成してくれる

■ このサービスへの思い・作りたい理由
このサービスの題材となるものに関してのエピソードがあれば詳しく教えてください。
このサービスを思いつくにあたって元となる思いがあれば詳しく教えてください。

・一人の時など毎日の料理の献立を考えるのが面倒だと思ったため。
・ユーザーがおいしそうだと思った料理を保管してそれから献立や栄養バランスを考えて提案してくれれば楽だと考えたため。

■ ユーザー層について
決めたユーザー層についてどうしてその層を対象にしたのかそれぞれ理由を教えてください。

・料理する人
理由：料理する人は、メモやレシピの記録などを取るときがあると考えたため。尚且つ次の日の献立を提示することで毎日の献立を考える時間が短縮できるのではないかと考えたため。

■サービスの利用イメージ
ユーザーがこのサービスをどのように利用できて、それによってどんな価値を得られるかを簡単に説明してください。

・レシピの記録だけでなく、前日のレシピから栄養バランスを考えて献立を提案する
価値：献立を考える時間を短縮
・動画や写真の保存機能
価値：視覚的に見やすくなる
・人数で分量を計算し直す機能
価値：人数の変化に適応できるため
・食材の賞味期限管理(通知でお知らせ)
価値：賞味期限を確認しなくてよくなる

■ ユーザーの獲得について
想定したユーザー層に対してそれぞれどのようにサービスを届けるのか現状考えていることがあれば教えてください。

■ サービスの差別化ポイント・推しポイント
似たようなサービスが存在する場合、そのサービスとの明確な差別化ポイントとその差別化ポイントのどこが優れているのか教えてください。
独自性の強いサービスの場合、このサービスの推しとなるポイントを教えてください。

・ユーザーが気に入って記録したレシピから献立を考える
なお、前日の献立で足りていない栄養素などを提案する
・打ち込んだ人数に応じて分量変化

■ 機能候補
現状作ろうと思っている機能、案段階の機能をしっかりと固まっていなくても構わないのでMVPリリース時に作っていたいもの、本リリースまでに作っていたいものをそれぞれ分けて教えてください。

〇MVPリリース
・会員登録
・ログイン(ログイン後自分のレシピを記録できるようにする)
・メモ機能(動画、写真も保存可能)
・献立作成機能(栄養バランスを加味する)
・通知機能

〇本リリース
・人数分量計算機能
・食材の賞味期限管理

■ 機能の実装方針予定
一般的なCRUD以外の実装予定の機能についてそれぞれどのようなイメージ(使用するAPIや)で実装する予定なのか現状考えているもので良いので教えて下さい。

Food API: 食材やレシピデータを提供。
・Spoonacular API: 世界中のレシピを取得可能。
画像認識（オプション機能）:
・食事写真を解析して栄養情報を自動登録する。
・ツール: Google Vision API

■アプリの拡張性確認の観点
家にある食材で作れる料理などを検索できる機能
四季や体調を加味した料理を提案する機能
料理レシピのtweet機能
