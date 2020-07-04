# 宝塔API SDK
## 使用方法
修改成自己的宝塔接口和Api密钥
```
$bt = new Bt('http://127.0.0.1:8888','xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx');
header('Content-type: application/json');
echo json_encode($bt->GetSystemTotal());
```