# nohup

> 當終端被關閉時允許程序繼續存在運作。
> 更多資訊：<https://www.gnu.org/software/coreutils/manual/html_node/nohup-invocation.html>.

- 執行一個可以在終端機之外繼續執行的程序：

`nohup {{程序指令}} {{參數1 參數2 ...}}`

- 在背景啟動 `nohup`：

`nohup {{程序指令}} {{參數1 參數2 ...}} &`

- 執行可以在終端機之外繼續執行的的 `.sh` 檔：

`nohup {{sh檔案}} &`

- 執行一個程序並將其輸出寫入特定文件：

`nohup {{程序指令}} {{參數1 參數2 ...}} > {{文件路徑}} &`
