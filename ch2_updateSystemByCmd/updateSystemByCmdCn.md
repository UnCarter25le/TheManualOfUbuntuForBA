# 更新Ubuntu軟件指令

## 前言


1. 終端機Terminal示意：
![終端機Terminal示意](/ch2_updateSystemByCmd/photo/terminal_1.png)
    - 說明：必須倚賴這樣的視窗介面(終端機)下達命令指令，透過殼程式(shell script)跟[kernel](https://zh.wikipedia.org/wiki/%E5%86%85%E6%A0%B8)(計算機概論稱作核心)溝通，讓kernel安排CPU、RAM、ROM等硬體裝置運作完成使用者、應用程式需要的操作。

    - 執行：按下ctrl+alt+T呼叫出終端機，對它下達想執行的指令可。例如「ls」瀏覽當前目錄下的檔案。

    - Windows系統的cmd、powershell視窗介面和Ubuntu的終端機存在的目的是一樣的。


----

1. [更新系統軟體指令](https://askubuntu.com/questions/94102/what-is-the-difference-between-apt-get-update-and-upgrade)
    - &&之前的update，目的讓系統知道從Ubuntu官方提供系統必要的更新patch(補丁)，以及軟體可更新的版本資訊。
    - &&之後的upgrade，目的讓系統根據update獲得的待更新軟體清單，更新軟體與必要系統資訊。
    - 日後將補充如何讓upgrade不對指定軟體升級的辦法。這非常有效，這幫助我在UbuntuOS上得以使用Virtualbox。

    sudo apt-get update && sudo apt-get -y upgrade

----

## 附錄
1. 安裝可解壓縮rar檔案的軟體：
    
    sudo apt-get install p7zip-rar


2. [安裝可解壓縮7z檔案的軟體](https://askubuntu.com/questions/54654/compress-and-split-files-in-the-file-explorer)：
    
    sudo apt-get install p7zip-full

3. 安裝終端機編輯器：
    
    sudo apt-get install vim

4. 安裝終端機拜訪網路資源的軟體(類比python爬蟲程式)：
    
    sudo apt-get install curl


