G:\我的雲端硬碟\PythonTemplate
git-crypt export-key
git-crypt unlock
# ------------------------------------------------------------------------------
2025.08.27
採用VNPY 4.1.0 為base
# ------------------------------------------------------------------------------
Ubuntu Linux環境下如何進行開發。
01. 根據〔月-日-時分〕建立目錄，並cd進入該目錄。
02. git clone取得原始碼。CD進入該Repo
03. git-crypt解碼。
04. 執行【code .】
05. 開啟 VS Code的終端機
06. 在終端機中執行【bash create_env.sh】來建立虛擬環境。
07. 在終端機中執行【conda activate 虛擬環境的絕對路徑+剛剛建立的虛擬環境安裝目錄】
    目的是切換虛擬環境至我們自行定義的虛擬環境。
08. 編輯launch.json中項目【"Linux Debuging: main.py"】
    修改其中欄位："python": "/home/elvis/projects/09-01-0015/uivnpy/my_env_miniconda3/bin/python"
    💢注意路徑的指定要正確。
09. F5觸發除錯器啟動。