# 長照系統 開發說明

## 系統狀態

Update Time : 2020-11-23

### 開發中

1.廚房出餐
2.失智共照
3.支持服務

### 已完成

1.日照系統  
2.輔具系統  
3.系統管理
4.轉介系統
5.專業服務
6.活力站
7.社工補助


## 開發環境

#### 前端

Html：html5  
Javascript：jquery 3.2  
CSS：Bootstrap 3.7.7  
js、css打包工具：laravel-mix

需求軟體  
1.NODEJS  
2.文字編輯器

iis 設定:

    <mimeMap fileExtension=".hbs" mimeType="text/x-handlebars-template" />
    <mimeMap fileExtension=".woff2" mimeType="application/font-woff2" />
	<mimeMap fileExtension=".json" mimeType="application/json" />
	
複製config.sample.js並重新命名config.js

修改

    //基礎路徑
    var baseurl = protocol + '://' + url('hostname') + ":8080";
    //網頁路近
    var baseurldir = baseurl + '/TT_StMaryApp/';
    //API路近
    var wsurl = baseurl + '/STMaryWSAPI/';

