
go env -w GOPROXY=https://goproxy.cn,direct   
go build .\main.go  
.\main.exe bingo2sql --start-file=C:\Users\Administrator\Desktop\binlog.000024 -t table.sql
