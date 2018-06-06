# Firebase

[Firebase](https://firebase.google.com/) is Google's mobile platform that helps you quickly develop high-quality apps and grow your business.  

`npm install -g firebase-tools`  
`firebase login`  

打開[firebase控制台](https://console.firebase.google.com/u/0/)，點擊添加項目 `test-firebase`  

`cd test-firebase`  
`firebase init`  選擇`Hosting` 按下空格&輸入鍵

> ? What do you want to use as your public directory? dist  
? Configure as a single-page app (rewrite all urls to /index.html)? Yes  
+  Wrote dist/index.html  

`firebase deploy`  
> https://test-firebase-2e72e.firebaseapp.com