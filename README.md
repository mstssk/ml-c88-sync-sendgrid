## Setup

1. Checkout this repo.
2. `npm install`
3. `tsc`
4. Copy `built/tsc.js` into Google Forms' Script Editor.
5. Menu: `リソース` -> `すべてのトリガー` -> `新しいトリガーを追加`
6. `handleFormSubmitted`, `フォームから`, `フォーム送信時`  
   `通知`は任意で  
7. 保存しようとすると権限の承認を求められるので`承認する`
8. Menu: `ファイル` -> `プロジェクトのプロパティ` -> `スクリプトのプロパティ`
9. プロパティを追加
    参考: https://sendgrid.com/docs/API_Reference/Marketing_Emails_API/emails.html
    - api_user
    - api_key
    - list_name
    - alert_to : エラー時のメール送信先
