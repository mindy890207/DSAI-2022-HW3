# DSAI-2022-HW3
Code是使用FTP上upload的F74076174-9.zip，
Github 的部分因筆電送修故還未上傳Code ，
有先寄信告知助教。

## 模型訓練
採用autoarima來predict 用電以及產電。

## 買賣標準
將預測的產電扣掉用電，若是小於0則判斷為要去買電；大於0則是將多餘的電賣掉。
買賣價格約定在2.5，以排名來看效果不錯。
