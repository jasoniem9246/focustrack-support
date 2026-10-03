# FocusTrack — GitHub Pages upload

繁中／English 靜態客服及隱私網站。無 build、無依賴、無表單。未公開部署。

## Jason 自行上傳
1. 登入您要使用的 GitHub 帳戶。Email 不能推算 GitHub username。
2. 建立要代管此網站的 repository。GitHub Pages 的可用性取決於帳戶方案及 repository visibility；選擇公開 repository 前請確認只放本 ZIP 的公開網站檔案。勿上傳 App 私有 repository。
3. 解壓縮此 ZIP，把 index.html、support.html、privacy.html、assets/、.nojekyll 與 README.md 放在 repository 根目錄。請確認隱藏檔 .nojekyll 也有上傳。
4. Settings → Pages → Build and deployment → Deploy from a branch，選擇 main 與 /(root)，Save。若介面不同，以當前 GitHub Pages 設定為準。
5. 等待部署完成，使用 Settings → Pages 顯示的實際 HTTPS URL。請實際開啟首頁、support.html 與 privacy.html，確認 CSS、信箱及手機閱讀正常。
6. 將兩個實際 HTTPS URL 回傳，供後續 App / App Store Connect 接入；本次不修改 App 或 ASC。

## URL 模板（只作文件示例；尚未部署或驗證）
- 首頁：https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPOSITORY/
- Support URL：https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPOSITORY/support.html
- Privacy Policy URL：https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPOSITORY/privacy.html
上述占位符必須換成實際 username / repository，勿直接貼入 ASC。以 Pages 顯示網址為準；自訂網域或 username.github.io repo 可有不同 URL。

## 接入邊界
客服信箱：miorbit.support@gmail.com。Public HTML 未包含私人帳戶 email。網頁 mailto 無 subject/body/device query。更新 App 的郵件內容與真機收信驗證是另一項工作。

Issue #4/#5/#6/#9 可引用此網站為 support/privacy 候選交付；候選檔案不等於已部署 URL、ASC 完成、Kids Category 審核通過或公開上線。不關閉 issue 或合併 PR。

政策按已核准的有限 active-data 刪除邊界撰寫，未承諾完全抹除、固定保存天數或醫療效果。發布前請由 owner 最後確認文字與當前 App build 相符；以本機網站測試不能代替 IPA、真機或 Apple 審核驗證。
