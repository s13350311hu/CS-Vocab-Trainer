# 第一次使用 GitHub：CS Vocab Trainer 上線步驟

## A. 建立 GitHub repository

1. 打開 https://github.com/ 並登入。
2. 右上角按 `+`。
3. 按 `New repository`。
4. `Repository name` 輸入 `CS-Vocab-Trainer`。
5. `Description` 可以貼 README 裡的中文描述。
6. 選 `Public`。
7. 不要勾選 `Add a README file`，因為本資料夾已經準備好 README。
8. 按 `Create repository`。

## B. 上傳檔案

1. 在新 repository 首頁按 `Add file`。
2. 選 `Upload files`。
3. 把整個專案資料夾裡的檔案拖曳到上傳區。
4. 確認畫面上至少看到 `index.html`、`README.md`、`LICENSE`。
5. 往下找到 `Commit changes`。
6. 保持預設的 `Commit directly to the main branch`。
7. 按 `Commit changes`。

## C. 開啟 GitHub Pages

1. 在 repository 上方按 `Settings`。
2. 左側找到 `Pages`。
3. 在 `Build and deployment` 的 `Source` 選 `Deploy from a branch`。
4. `Branch` 選 `main`。
5. 資料夾選 `/(root)`。
6. 按 `Save`。
7. 等部署完成後，回到 `Settings → Pages`，按 `Visit site`。

你的網址會類似：

`https://你的GitHub帳號.github.io/CS-Vocab-Trainer/`

## D. 以後更新網站

1. 修改本機的 `index.html`。
2. 到 GitHub repository。
3. `Add file` → `Upload files`。
4. 上傳新的 `index.html`。
5. `Commit changes`。
6. 等待 Pages 重新部署。

GitHub Pages 更新可能需要幾分鐘才會出現在網站上。
