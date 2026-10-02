# HW4：分支、合併、Fork、Pull Request 實作紀錄

學號：111210552  
姓名：林小蓮  
班級：資工四  

---

## 專案連結

- 母專案：https://github.com/juli-se-example/git-example
- 分支：https://github.com/juli-se-example/git-example/tree/developJuliBranch
- 子專案（Fork）：https://github.com/julianalidya/git-example

---

## 1. 分支（Branch）

從 `main` 建立新的分支：

`developJuliBranch`

並在此分支建立：

`juliBranch.md`

完成後提交（Commit）變更。

---

## 2. Pull Request

完成分支修改後，建立 Pull Request：

`developJuliBranch` → `main`

Pull Request 用來確認分支中的修改，再將修改合併至主分支。

---

## 3. 合併（Merge）

確認 Pull Request 後，將 `developJuliBranch` 合併至 `main`。

合併完成後，`juliBranch.md` 已成功加入母專案的 `main` branch。

---

## 4. Fork

將母專案 Fork 至個人 GitHub 帳號。

母專案：

`juli-se-example/git-example`

Fork 後的子專案：

`julianalidya/git-example`

---

## 5. Fork 修改

在 Fork 後的 repository 中建立：

`juliFork.md`

此檔案只建立於 Fork repository，用來確認 Fork 可以獨立於母專案進行修改。

---

## 6. GitHub Flow 實作流程

本次練習完成以下流程：

`main`

↓

`developJuliBranch`

↓

`juliBranch.md`

↓

`Commit`

↓

`Pull Request`

↓

`Merge into main`

↓

`Fork repository`

↓

`juliFork.md`

---

## 完成項目

- [x] 建立母專案
- [x] 建立 Branch
- [x] 新增 `juliBranch.md`
- [x] Commit
- [x] 建立 Pull Request
- [x] Merge 至 `main`
- [x] Fork repository
- [x] 在 Fork 新增 `juliFork.md`

---

## 練習目的

透過本次作業練習 Git Flow 與 GitHub Flow，了解 Branch、Commit、Pull Request、Merge 與 Fork 的基本操作方式。
