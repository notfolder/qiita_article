openwebuiにパッチをprしてリリースされた件

ファイルを出力するようなMCPサーバーを呼び出すために、どうしてもセッション情報が欲しかった
llmを呼び出す際にはセッション情報をhttpヘッダに付けてくれるのに、MCPサーバー呼び出しには付けてくれてなかったので、実装した。
もちろんcopilotさんと一緒に直して検証しまくってから本家にpr
https://github.com/open-webui/open-webui/pull/21092

非常に小さい変更だが、初めて本格的なOSSへのPRだったので緊張した。
AIに翻訳やお作法などを聞きながら投稿後の対応などをできた。

下記で取り込まれた様子。
https://github.com/open-webui/open-webui/releases/tag/v0.8.4
