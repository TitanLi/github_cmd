#
github

1.安裝

```
$sudo apt-get install git
```

2.設定

指定使用者名稱及電子郵件帳號

```
$git config --global user.name "Titan"
$git config --global user.email Lisheng0706@gmail.com
--global 將參數設定為全域
```

3.列出git所有設定值

```
$git config --list
```

4.顯示project當前狀態

```
$git status
```

5.將檔案加入追蹤

```
$git add <file name>
```

6.將檔案取消追蹤

```
$git reset HEAD <file name>
```

7.提交修改

```
$git commit -m "Add git command"
```

8.gitignore

```
#註解
#不要追蹤檔名為.a結尾的檔案
*.a
#但要追蹤lib.a
！lib.a
#只忽略根目錄下的TODO檔案。不包含子目錄下的TODO
/TODO
#忽略build/目錄下所有檔案
build/
#忽略doc/notes.txt但不包含doc/server/arch.txt
doc/*.txt
#忽略全部在doc/下的.txt檔案
doc/**/*.txt
```
