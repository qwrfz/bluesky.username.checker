<h1>bluesky.username.checker</h1>
⚠️このチェッカーは自分がturbowarpで作成したものをpackager.turbowarp.orgでhtmlに変換したものです。⚠️<br>
変化する部分の文字はX、Y、Z、W、A、Bを使って入力してください。<br>
毎秒300回以上チェックすると429が出ます。<br>
bsky.social以外のドメインも確認できます。<br>
ドメイン部分を指定しない場合、bsky.socialドメインを使用してチェックします。<br>
allはアルファベットと数字と"-"、letterはアルファベット、numberは数字です。<br>
チェックし終わるとtxtファイルとして未作成リストを保存できます。<br>
<h1>使用したAPI</h1>
https://public.api.bsky.app/xrpc/com.atproto.identity.resolveHandle?handle={username} <br>
※{username}のところがユーザーネームを入力する部分です。
<h1>使用例</h1>
<p align="center">
  <img src="example.gif" alt="demo" width="400">
</p> <br>
