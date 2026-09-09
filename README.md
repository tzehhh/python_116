# Python 程式設計講義（掃描本）

《一步到位！Python 程式設計》第四版（陳惠貞 著，旗標出版）的課堂講義掃描，
依章節分頁閱讀，附可點擊的章節目錄。目前收錄第 2、3、4、5、6、9 章。

## 檔案

- `index.html` — 總目錄（首頁）
- `ch2.html` … `ch9.html` — 各章閱讀頁
- `img/` — 頁面圖片

純靜態網頁，不需要任何後端。直接用瀏覽器開 `index.html` 就能看，
也可以放到 GitHub Pages 或任何靜態主機。

## 發布到 GitHub Pages

```bash
git init
git add .
git commit -m "Add Python 講義 scanned e-book"
git branch -M main
git remote add origin https://github.com/<你的帳號>/<repo 名稱>.git
git push -u origin main
```

推上去之後到 repo 的 **Settings → Pages**，Source 選 `Deploy from a branch`，
分支選 `main`、資料夾選 `/ (root)`，存檔後約一分鐘網址就會生效。
