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

從母專案的 `main` 建立新的分支：

`developJuliBranch`

並在此分支建立檔案：

`juliBranch.md`

完成後提交（Commit）變更。

---

## 2. Branch Pull Request

完成分支修改後，建立 Pull Request：

`developJuliBranch` → `main`

透過 Pull Request 確認分支中的修改內容，並準備將修改合併至主分支。

---

## 3. Branch 合併（Merge）

確認 Pull Request 後，將 `developJuliBranch` 合併至 `main`。

合併完成後：

`juliBranch.md`

成功加入母專案的 `main` branch。

---

## 4. Fork

將母專案：

`juli-se-example/git-example`

Fork 至個人 GitHub 帳號。

Fork 後的子專案：

`julianalidya/git-example`

Fork repository 可以獨立於母專案進行修改。

---

## 5. Fork 修改

在個人的 Fork repository 中建立：

`juliFork.md`

完成修改後提交（Commit）變更。

此時 Fork repository 與母專案產生不同的修改內容。

---

## 6. Fork Pull Request

完成 Fork repository 的修改後，建立 Pull Request：

`julianalidya/git-example:main` → `juli-se-example/git-example:main`

Pull Request：

`Create juliFork.md`

確認修改內容且沒有衝突後，準備將 Fork 中的修改合併回母專案。

---

## 7. Fork 合併（Merge）

確認 Pull Request 後，將 Fork repository 的修改合併至母專案的 `main` branch。

合併完成後：

`juliFork.md`

成功加入母專案。

---

## 8. GitHub Flow 實作流程

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

↓

`Commit`

↓

`Pull Request to mother repository`

↓

`Merge into mother repository`

---

## 完成項目

- [x] 建立母專案
- [x] 建立 Branch
- [x] 新增 `juliBranch.md`
- [x] Commit Branch 修改
- [x] 建立 Branch Pull Request
- [x] Merge Branch 至 `main`
- [x] Fork repository
- [x] 在 Fork 新增 `juliFork.md`
- [x] Commit Fork 修改
- [x] 從 Fork 建立 Pull Request
- [x] Merge Fork 修改至母專案

---

## 練習目的

透過本次作業實際操作 Git Flow 與 GitHub Flow，了解 Branch、Commit、Pull Request、Merge 與 Fork 的基本使用方式，以及如何透過 Pull Request 將不同 Branch 或 Fork repository 的修改整合回主要專案。
