# 調整中文鍵盤

## 前言


1. [下載ubuntu16.04映像檔](https://www.ubuntu-tw.org/modules/tinyd0/)(ubuntu正體中文網)。
![下載Ubuntu16.04映像檔示意](/ch1_adjustKeyboard/photo/download_ubuntu1604.png)

2. 啟用Ubuntu16.04：
    > 對Google Search下「windows virtual box install ubuntu 16.04」，可獲得安裝的參考方式。
    1. WindowsOS使用者，借助VirtualBox或VMware開啟。
    2. MacOS使用者，借助VirtualBox或VMware開啟。

3. 以Windows 8.1 PC 搭配 Virtual Box完成**設定步驟**範例。
----

## 設定步驟
> 按下列步驟設定好「酷注音」這個支援繁、簡體輸入法。

1. 點擊左方設定鈕，打開設定視窗，點選「Language Supoort」。

![點擊左方設定鈕，打開設定視窗](/ch1_adjustKeyboard/photo/adjust_1.png)

2. 照指示安裝支持功能。

![照指示安裝支持功能](/ch1_adjustKeyboard/photo/adjust_2.png)

3. 視窗的Language分頁，點擊Install/Remove Languages鈕，勾選Chiese(traditional)，按apply鈕。

![Language分頁，點擊Install/Remove Languages鈕，勾選Chiese(traditional)，按apply鈕](/ch1_adjustKeyboard/photo/adjust_3.png)


4. Regional Formats分頁，選擇漢語，點擊Apply System-Wide。

![Regional Formats分頁，選擇漢語，點擊Apply System-Wide](/ch1_adjustKeyboard/photo/adjust_4.png)



5. 回到Language分頁，input method system選擇「fcitx」，點擊Apply System-Wide。

![回到Language分頁，input method system選擇「fcitx」，點擊Apply System-Wide](/ch1_adjustKeyboard/photo/adjust_5.png)



6. 回到Regional Formats分頁，按圖片選擇Chinese,Literary，讓系統以簡體中文顯示日期資訊。若要繁體顯示，選擇漢語。

![回到Regional Formats分頁，按圖片選擇Chinese,Literary，讓系統以簡體中文顯示日期資訊。若要繁體顯示，選擇漢語](/ch1_adjustKeyboard/photo/adjust_6.png)


7. 選擇畫面右上的設定鈕，Log Out。必須再登入系統，語言設定才能生效。

![選擇畫面右上的設定鈕，Log Out。必須再登入系統，語言設定才能生效](/ch1_adjustKeyboard/photo/adjust_7.png)


8. 選擇畫面上方的企鵝，點選ConfigureFcitx。

![選擇畫面上方的企鵝，點選ConfigureFcitx](/ch1_adjustKeyboard/photo/adjust_8.png)


9. 於Input Method分頁，點選加號。

![於Input Method分頁，點選加號](/ch1_adjustKeyboard/photo/adjust_9.png)


10. 取消Only Show Current Language的勾選，輸入chew，得到Chewing(注音)輸入法，點擊OK。

![取消Only Show Current Language的勾選，輸入chew，得到Chewing(注音)輸入法，點擊OK](/ch1_adjustKeyboard/photo/adjust_10.png)


11. 選擇畫面上方的企鵝，就可選擇「酷注音」了。

![選擇畫面上方的企鵝，就可選擇「酷注音」了](/ch1_adjustKeyboard/photo/adjust_11.png "圖片說明")

----

## 附錄
1. [讓虛擬機和本機OS「共用剪貼板、拖拉檔案」的設定方法](https://blog.xuite.net/yh96301/blog/300815666-VirtualBox+5.2%E5%AE%89%E8%A3%9DUbuntu+16.04%E8%88%87Windows+10%E5%85%B1%E7%94%A8%E5%89%AA%E8%B2%BC%E7%B0%BF)

    > - 共用剪貼版意思是讓Ctrl+C與Ctrl+V可以在兩個系統間有作用。
    > - 拖拉檔案意思是在兩個系統間進行檔案拉進、拉出。

    1. 選擇裝置，選擇插入Guest Additions CD 映像，點擊同意安裝功能。
    ![選擇裝置，選擇插入Guest Additions CD 映像，點擊同意安裝功能](/ch1_adjustKeyboard/photo/takeCopyAndDragIntoEffect_1.png)

    2. 選擇裝置，選擇共用剪貼簿，再選擇雙向。
    ![選擇裝置，選擇共用剪貼簿，再選擇雙向](/ch1_adjustKeyboard/photo/takeCopyAndDragIntoEffect_2.png)

    3. 重啟虛擬機，讓功能生效。

2. [使virtaulbox支持USB3.0傳輸的設置方法(上VirtualBox官網下載擴增包安裝即可)](https://jingyan.baidu.com/article/22a299b5e0198a9e19376a38.html)

    > - 預設僅能使用1.0，因此建議升級成USB3.0。至少Virtual Box 6.0.8版本預設是1.0。

    1. 從Virual Box官網下載擴充包。All supported platforms就是了；下載下來後，雙擊安裝！
    ![從Virual Box官網下載擴充包。All supported platforms就是了；下載下來後，雙擊安裝！](/ch1_adjustKeyboard/photo/usb3setting_1.png)

    2. 如果要移除，就在preference中可以移除。
    ![從Virual Box官網下載擴充包。All supported platforms就是了；下載下來後，雙擊安裝！](/ch1_adjustKeyboard/photo/usb3setting_2.png)