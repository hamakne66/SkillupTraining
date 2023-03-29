# CLI
<!--こちらのファイルで答えてください。-->
あなたの友達リカは、ハッカー映画の大ファンです。あなたがエンジニアになることを聞いて、興奮し、長年の疑問を持っていることを打ち明けました。   

リカちゃんが理解しやすい言葉で彼女の質問に答えましょう。  

1．「映画の中でトレーナーが着いているハッカーがカッコイイよね！ガタガタでタイピングするのもめっちゃカッコいい。でも、なぜハッカーたちはマウスを使わなくてもコンピューターを操作できるのでしょうか？」
これは、ハッカーたちがCLI (Command Line Interface) でコンピューターを操作しているからです。CLIについて説明してください。

A1
コンピュータやソフトウェアを操作する方式の一つで、全てのやり取りを文字によって行う方式。
windowsOSではcommandPromptでの操作がこれに当たる。
他の操作方式には、GUI(Graphical User Interface)が存在する。こちらは、画面上で視覚的にコンピュータを操作する方式である。


2．「いろいろ聞いても、実際に使えた方がいいよね。」とリカちゃんが言います。そこで、リカちゃんにCLIの使い方を教えてあげましょう。リカちゃんには、フォルダを作成したり、映画の感想を書くためのファイルを作成したり、既存の映画の感想ファイルをフォルダに移動する方法を教えてください。

A2
OSにwindowsを使っている場合、"command prompt"を起動してください。
"newfolder"という名前のフォルダを作成： mkdir newfolder
"newfolder"というフォルダが存在することを確認する： dir
作成した"newfolder"に移動する： cd newfolder
"movieImpression"という空のファイルを作成： type null > movieImpression.txt
"movieImpression"の内容を確認する： type movieImpression.txt
"movieImpression"に書き込む： copy con movieImpression.txt  ==> 書きたい内容を書き込む

