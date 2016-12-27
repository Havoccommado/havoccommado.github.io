## hello world
```javascript
var a = 'hello world';
```

## ——php数据库连接
```php
	
$conn = mysqli_connect("localhost","root","","havoc");

if (!$conn){
    die("链接失败..");
}

$conn->query("set names utf8");//设置编码防止乱码
```
