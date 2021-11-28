# subject-1128
# windows
## 画像キャプチャ : WIN + SHIFT + S
(ウインドウのキャプチャ : ALT + SCREEN)

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
  - test
    
![image](https://user-images.githubusercontent.com/89338401/143733528-0271a468-a6b1-4823-886f-3b777af0ae57.png)

# タスクマネージャー
### ショートカットキー : CTRL + SHIFT + ESC
