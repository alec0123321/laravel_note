# Laravel
## 一開始先測試 route/app.php 去連接 view/blade.php的頁面
## php artisan make:model Post --m
## 把return view的邏輯寫在pages.controller.php 也可以用 make:controller pages.controller
## make:controller PostController --resorce
## 先建立 function create
```
return view('posts.create)
```
## view/posts/create.blade.php 要建立起來這就不多說了
## blade裡面都是用boostrap 4建構的
## https://laravelcollective.com/docs/master/html
### 把 form的功能裝回去 網址裡面有使用說明 主要就是改php 裡面的設定然後再跑一次 require 就好了 再把參數設定好
## 建立 create.blade.php
## 使用form::label...

### mysql如果要用在window上可能還是用wamp比較方便因為已經裝好了phpmyadmin

## Parsley
### http://parsleyjs.org/
