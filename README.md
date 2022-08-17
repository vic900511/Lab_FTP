# Lab_FTP
FTP procedure in linux
```bash
ftp ip port
```
- 輸入帳號密碼進入 FTP server
- cd 到要下載檔案的目錄
- mget filename (mget * 可下載整個目錄的檔案)
- 每下載一個檔案會詢問一次，可用 prompt 關閉詢問
```bash
ftp> prompt
ftp> mget *
```
