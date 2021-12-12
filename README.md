# subject-1128
# windows
## 画像キャプチャ : WIN + SHIFT + S
(ウインドウのキャプチャ : ALT + PrintSCREEN)

![image](https://user-images.githubusercontent.com/89338401/143732857-5716d7a2-70e8-4928-a2a9-8305901ec095.png)

**タスクバーを右端をクリックするとデスクトップが表示されます**

```sql
SELECT 
* 
FROM
  INFORMATION_SCHEMA.VIEWS
  
 {
    "code-runner.showRunIconInEditorTitleMenu": true,
    "code-runner.runInTerminal": true,
    "code-runner.executorMap": {
        "vbscript": "cscript //Nologo"
    },
    "code-runner.fileDirectoryAsCwd": true,
    "terminal.integrated.profiles.windows": {
        "PowerShell": {
            "source": "PowerShell",
            "icon": "terminal-powershell"
        },
        "Command Prompt": {
            "path": [
                "C:\\WINDOWS\\system32\\cmd.exe"
            ],
            "args": [],
            "icon": "terminal-cmd"
        },
        "Git Bash": {
            "source": "Git Bash"
        }
    },
    "terminal.integrated.defaultProfile.windows": "Command Prompt",
    "terminal.integrated.fontSize": 16,
    "editor.renderWhitespace": "boundary",
    "csv-edit.fontSizeInPx": 14,
    "csv-preview.formatValues": "never",
    "[csv]": {
        "files.encoding": "shiftjis"
    },    
    "terminal.integrated.defaultLocation": "editor",
    "[vbs]": {
        "files.encoding": "shiftjis"
    },
    "runTerminalCommand.commands": [
        {
            "command": "cscript download\\setup-vscode-user.vbs && cscript C:\\Users\\%USERNAME%\\AppData\\Roaming\\Code\\User\\script\\sworc-settings-download.vbs",
            "name": "基本設定",
            "auto": true,
            "group": "設定"
        },
        {
            "command": "cscript C:\\Users\\%USERNAME%\\AppData\\Roaming\\Code\\User\\script\\workspace-build-download.vbs",
            "name": "ワークスペース作成",
            "auto": true,
            "group": "設定"
        },
        {
            "command": "explorer {resource}",
            "name": "選択したファイルを既定のアプリで開く",
            "auto": true
        },
        {
            "command": "code {resource}",
            "name": "VSCode でフォルダを開く",
            "auto": true
        }
    ]  
}

```

<br>
<br>

- ウインドウを左右に並べるには？
  - 右に置きたいウインドウをドラッグしてデスクトップの右端へ持って行く
  - そうすると、残ったウインドウの一覧が左半分に表示されるので、選択する
  - 境界をマウスで長押しすると黒い移動用の境界用コントロールが現れる

    
![image](https://user-images.githubusercontent.com/89338401/143733528-0271a468-a6b1-4823-886f-3b777af0ae57.png)

# タスクマネージャー
### ショートカットキー : CTRL + SHIFT + ESC
#### ▼ タスクマネージャの詳細で必要な列はプラットホーム
![image](https://user-images.githubusercontent.com/1501327/143733802-d39c8668-99da-41af-b6e9-9ab342f3a179.png)\
※ アプリが 32 か 64 かを確認できる

![image](https://user-images.githubusercontent.com/1501327/143733976-162e2e79-1d81-40b4-aa52-9dde6ba06fba.png)

## Windows ロゴ キーのキーボード ショートカット

![image](https://user-images.githubusercontent.com/1501327/145702847-13755607-f7cc-4964-82a9-3d922f6d1e37.png)

| キー | 内容 ♥
| :--- | :--- 
| I | 設定
| E | エクスプローラ
| R | ファイル名を指定して実行
| S | 検索
| D | デスクトップ

| キー | 内容 
| :--- | :--- 
| . | 編集中に絵文字ウィンドウ
| G | ウィンドウの動画化
| V | クリップボードの履歴
| S | 検索
| D | デスクトップ

