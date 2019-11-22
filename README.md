# threejs_tutorial

## Step

### 事前準備
1. [vscode](https://code.visualstudio.com/)をインストール

2. vscodeの拡張機能(debug for chrome, Live Server, zenkaku, Japanese Language Pack)をインストール
      - threejs_tutorialをダウンロード
      - 解凍し、そのフォルダをvscodeで開く
      - 推奨事項の拡張機能をインストールし、vscodeを再起動

3. vscodeの設定
      - タブをスペース4つに変換(Editor: Tab Size),(Editor: Insert Spaces)
      - 行末スペースの可視化(Editor: Render Whitespace)
      - 文字コードの自動判別設定("files.autoGuessEncoding": true)

      - (Rictyフォントのインストール&設定)
      - [Debug for chromeを使用する設定]
        + デバッグを開いて、歯車をクリックして、launch.jsonを開く
        + 以下のように変更する
            ```json
            "name": "Launch Chrome against localhost",
            "url": "http://localhost:5500",
            "webRoot": "${workspaceFolder}"
            ```
      - そのほかいいプラグインあれば

### HTML基礎(idとか使いそうなとこ)

### JS基礎

### (JSでHTMLを操作する)

### JSでハマりやすいところ

### Three.jsの概念
- これに沿って進めるー
- https://ics.media/entry/14771
- https://ics.media/tutorial-three/index.html

### Three.js応用(なんか面白そうなの作る)
- https://ics.media/entry/18812
### optional
- Git使う
- ES6で書いてみる
- TypeScript, CoffeeScriptで書いてみる
- CommonJSで書いて、BrowserifyでトランスパイルしGulpで自動実行
- Herokuで動かしてみる
- Node.jsでサーバーサイド書いてみる
- ...

## Downloads
- [Github Desktop for windows](https://desktop.github.com/)