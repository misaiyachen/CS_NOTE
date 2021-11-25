# CS_NOTE
W1:
  安裝、註冊GitHub

W2:
  Unix
    linux內核:
      常用分支:
        1.Debian:新手級、易用
          版本:
            (1).Ubuntu:Linux Mint、elementary OS
            (2).deepin
        2.Fedora:企業級、保守
          版本:
            RHEL:CenOS、Oracle Linux
        3.SUSE
          (1).SLES:openSUSE
          (2).Arch Linux
  指令
    cd:變換目錄
    pwd:顯示幕前的目錄
    mkdir:建立新目錄
    rmdir:刪除空內容的空目錄
    cp:複製
    mv:移動
    ls:顯示目錄下的所有內容
    cat:查看檔案內容
    nano:
      Ctrl C:顯示游標所在
      Ctrl W:查詢命令
    vi/vim:
      一般模式:可使用上下左右操控游標、刪除字元、複製貼上檔案
      編輯模式:編輯文字
      
  身分:
    1.user(owner)
    2.group:將帳號歸類，有助於類似專案開發、每個使用者均可加入多個群組
    3.others
  更改使用者權限:
    1.ls-l:查看每個檔案跟目錄的擁有者與群組
    2.chown:修改檔案跟目錄的擁有者與目錄
    3.chmod:控制檔案如何被他人調用
    4.mode:許可權設定字串

W3
  壓縮檔案:
    概念:
      1.將閒置空間釋出
      2.將重複的資料進行統計
    考慮因素:
      1.壓縮率
      2.解壓縮所需時間
      3.解壓縮所需的記憶體空間
      4.相容性
    壓縮類型:
      1.gzip
      2.xz
      3.tar.gz
  OSI、TCP/IP
    OSI:
      1.實體層
      2.資料連接層
      3.網路層
      4.傳輸層
      5.會談層
      6.展現層
      7.應用層
    TCP/IP:
      1.網路存取層
      2.網際網路層
      3.傳輸層
      4.應用層
