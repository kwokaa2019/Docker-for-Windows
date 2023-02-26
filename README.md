【安裝方法】

1.啟用 Hyper-V 虛擬譏平台功能 ， 方法如下

以滑鼠右鍵按一下 Windows 鍵，然後選取 [應用程式與功能]→選取相關設定下方右側的 [程式和功能 ]→選取 [開啟或關閉 Windows 功能]→選取 [Hyper-V]，「Windows 子系統 Linux 版」然後按一下 [確定]→安裝完成時，系統會提示您重新啟動您的電腦。

2. Docker Desktop 官方下載地址： https://www.docker.com/products/docker-desktop/

注意：此方法僅適用於Windows 10 操作系統專業版、企業版、教育版和部分家庭版！

3.下載Linux 核心更新套件 官方下載地址：https://wslstorestorage.blob.core.windows.net/wslblob/wsl_update_x64.msi

4.雙擊下載的Docker for Windows Installer 安裝文件，一路Next，點擊Finish 完成安裝。

5.安裝完成後，Docker 會自動啟動。通知欄上會出現個小鯨魚的圖標，這表示Docker 正在運行。

桌邊也會出現三個圖標，如下圖所示：

我們可以在命令行執行docker version 來查看版本號，docker run hello-world 來載入測試鏡像測試。

如果沒啟動，你可以在Windows 搜索Docker 來啟動：

如果啟動中遇到因WSL 2 導致地錯誤，請安裝WSL 2。 官方下載地址：https://learn.microsoft.com/zh-tw/windows/wsl/install

