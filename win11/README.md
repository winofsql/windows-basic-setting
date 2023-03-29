## タスクバー内を左寄せ
![image](https://user-images.githubusercontent.com/1501327/228454414-b856d46b-fbae-4286-9a80-a51d1784f975.png)

## PowerSHell からコマンドプロンプト
![image](https://user-images.githubusercontent.com/1501327/228454716-d45ce3a3-9442-44b6-97fd-c266ee30494c.png)\
![image](https://user-images.githubusercontent.com/1501327/228454919-a70f1225-9302-45c7-8e77-91eec55ead1f.png)

## 右クリックで Windows10 のポップアップメニューを表示する
### 設定
```reg
reg add "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32" /f 
```

実行後、いずれか
- エクスプローラ再起動
- サインアウトしてサインイン
- 再起動


### 元に戻す
```reg
reg delete "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32" /f 
```
![image](https://user-images.githubusercontent.com/1501327/228455540-32aa04a3-c72a-4ea1-a274-d41e7e5ddc4f.png)
