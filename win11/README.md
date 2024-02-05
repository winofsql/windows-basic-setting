## タスクバー内を左寄せ
![image](https://user-images.githubusercontent.com/1501327/228454414-b856d46b-fbae-4286-9a80-a51d1784f975.png)

## PowerShell からコマンドプロンプト
![image](https://user-images.githubusercontent.com/1501327/228454716-d45ce3a3-9442-44b6-97fd-c266ee30494c.png)\
![image](https://user-images.githubusercontent.com/1501327/228454919-a70f1225-9302-45c7-8e77-91eec55ead1f.png)

## 右クリックで Windows10 のポップアップメニューを表示する
### 設定
```reg
reg add "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32" /f 
```

実行後、いずれか
- エクスプローラ再起動
  - タスクマネージャ > 詳細 > explorer.exe を選択 > タスクの再起動( 右上 )
- サインアウトしてサインイン
- 再起動


### 元に戻す
```reg
reg delete "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32" /f 
```
![image](https://user-images.githubusercontent.com/1501327/228455618-24bd8ae6-3187-47ab-a2c5-2dfaddc2a23c.png)

### ウィジェットを OFF にする

![image](https://user-images.githubusercontent.com/1501327/233825831-f086bc1b-66f3-4c23-baed-9e68ac879a2e.png)

![image](https://user-images.githubusercontent.com/1501327/233825904-45d24361-044d-4726-9916-487e667804f3.png)


### SnippingTool.exe

- 設定

  ![image](https://user-images.githubusercontent.com/1501327/233826576-64a65a5c-8b06-455b-b5de-3f93a3edb38f.png)

- C:\Users\lightbox\Pictures\Screenshots ( スクリーンショットを自動的に保存する )

  ![image](https://user-images.githubusercontent.com/1501327/233826775-04a4dc2a-c232-4b27-a7c9-0bd0787508e9.png)
