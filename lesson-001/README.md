# angular-helloworld
angular-helloworld

## 確保nodejs已安裝,npm可正常使用

## 使用npm安裝angular/cli,後續才能使用ng命令
```
npm install -g @angular/@cli
```
## 使用ng建立專案
```
ng new lesson-001
```

## 建立依賴庫
```
npm install
```
## 啟動
```
npm start
```
# 常用語法

## 檢查版本
```
ng version
```


## 建立元件
```
ng g c tasks --skip-tests
```

## for loop
```TypeScript
@for (user of users; track user.id)
```
## ngFor ngIf
```TypeScript
<li *ngFor="let user of users">
<app-tasks *ngIf="selectedUser; else fallback" [name]="selectedUser.name" />
```



