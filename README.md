#### 開発メモ
ワークフロー
<br>　<img width="600" src="https://user-images.githubusercontent.com/40127279/127756657-844234f8-22e1-4109-9f9b-44d84bb8a50f.png">

### 1.うんちくのパース
　うんちくサイトからうんちく部分を抽出します
<br>　https://hq-improve.com/zatsugaku/ というサイトを対象にしました
<br>　多数のうんちくがあるのと、strongタグでの抽出ができそうでしたので
<br>　ただサイトの更新はなさそうなので、トリビアのワークフローみたいに
<br>　アクセスなしでもよかったかも。まぁパースの練習ということで。。。
<br>
<br>　あとはsedで抽出した結果をそのままRandomユーティリティに渡すだけでOKでした
<br><img width="480" src="https://user-images.githubusercontent.com/40127279/127756701-a2cee3b6-17c0-48e5-9557-7cd318578f61.png">

<br>　どうでもよいですが、RunScriptはechoのワンライナーです
<br><img width="600" src="https://user-images.githubusercontent.com/40127279/127756681-2c533971-0d83-4031-8af3-da51c37e6d17.png">
### 2.うんちくを喋らせる
　Randomユーティリティがうんちくを1つだけ選んでくれるので、それをMacに喋らせます
<br>　Sayコマンドを使っているだけです
<br>　ちなみに『アレクサ、うんちく教えて』とお願いすると、知っていましたか？に続けて
<br>　うんちくを言ってくれるので、同じようにしてみました
<br>　<img width="600" src="https://user-images.githubusercontent.com/40127279/127756713-aac3cd66-7573-402b-af4d-b3bb2f3db7fe.png">

<br>　さらに、アレクサは雑学でも、豆知識でも、教えてくれるので、真似してみました
<br>　と言っても、単に、入口のキーワードを増やしただけで、どのキーワードでもネタ元は
<br>　同じサイトです。ネタサイトを変えてみるのも面白そうですね。
<br>　
<br>　最後にうんちくをブラウザで検索させています
<br>
#### 背景
　Lesson19のどこでもターミナルのサンプルでsayコマンドを知ったので作ってみました
<br>　
#### 取扱説明
### 機能:
　macがうんちくを喋ってくれる
### インストール:
　1.[Alfredworkflow](https://github.com/KitanoTamotsu/unchiku/releases/download/1.0/unchiku.alfredworkflow.zip)をダウンロード 
<br>　2.ファイルをダブルクリックしてワークフローに登録
### 使い方:
　キーワード『うんちく教えて』で起動
<br>　（「雑学教えて」や「豆知識教えて」でも同じ動きをします）
<br>
<br>
[トップページに戻る](https://kitanotamotsu.github.io/)

