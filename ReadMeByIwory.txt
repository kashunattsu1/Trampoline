【フォルダ構成について】
現環境ではアセットのロックができず同じファイルを触ると競合する可能性があります。
ソース・コンテンツ共にRootに各人のフォルダを作成してその以下で作業を行ってください。
もし他の人のフォルダ以下を触りたい場合は必ずその人に連絡してください。

【クラス・構造体等のプレフィックスについて】
すでにエンジン側等でクラスが作成されているのが原因で名前が競合する可能性があります。
なのでプレフィックスとして「TP」をつけるようにしてください。
→悪い例：USoundManager
　良い例：UTPSoundManager

【コミット時の注意点】
現環境ではコミットのタイミングが被ると不具合が起こる可能性があります。
それを回避するためにコミット前に必ずDiscordのコミット報告所チャンネルで報告してください。
コミットが完了したらその旨とリビジョン番号を併せてコミット報告所チャンネルに投稿してください。
また作業を開始する前などにSVNの更新をかけて、
最後にコミット報告があったリビジョン番号を取得できているか確認してください。