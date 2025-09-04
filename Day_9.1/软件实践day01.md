# 软件实践

以下是一个账号注册页面的html代码实现

```html
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<style>
  a {
    color: red;
    text-decoration: none;
  }
</style>

<body>
  <!-- <p>手写代码</p> -->
  <a href="#">*</a>用户名:<input type="text" title="用户名设置成功后不可修改">
  <br>
  <a href="#">*</a>登陆密码:<input type="password" title="6-20位字母、数字或符号">
  <br>
  <a href="#">*</a>确认密码:<input type="password" title="再次输入您的登录密码">
  <br>
  <a href="#">*</a>证件类型:<select>
    <option value="">居民身份证</option>
    <option value="">中国护照</option>
    <option value="">外国护照</option>

  </select>
  <br>
  <a href="#">*</a>姓名:<input type="text" title="请输入姓名">
  <br>
  <a href="#">*</a>证件号码:<input type="text" title="请输入您的证件号码">
  <br>
  <a href="#">*</a>优惠类型:
  <select>
    <option value="">成人票</option>
    <!-- <option value="">儿童票</option> -->
    <option value="">学生票</option>
  </select>
  <hr>
  <a href="#">*</a>邮箱:<input type="text" title="请正确填写邮箱地址">
  <br>
  <a href="#">*</a>手机号码:<select>
    <option value="">+86</option>
    <option value="">+87</option>
    <option value="">+88</option>
    <option value="">+89</option>

  </select><input type="text" title="手机号码">
  <br>
  <br>
  <input type="radio">我已经阅读并同意申请<font color="blue">《用户注册协议》</font>
  <br>
  <button type="button"><a href="#">提交</a></button>
</body>

</html>
```



以下是用户注册界面的代码实现

```html
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>

<body>
  <h2>用户注册</h2>
  用户名:<input type="text" title="用户名设置成功后不可修改">
  <br>
  密码:<input type="password" title="6-20位字母、数字或符号">
  <br>
  性别:
  <input type="radio" name="gender" id="man"> <label for="man">男</label>
  <label><input type="radio" name="gender"> 女</label>
  <label><input type="radio" name="gender"> 保密</label>
  <br>
  籍贯:
  <select>
    <option value="">山西大同</option>
    <option value="">上海</option>
    <option value="">广州</option>
    <option value="">深圳</option>
    爱好:<input type="checkbox">钓鱼<input type="checkbox">旅游<input type="checkbox">骑行
    <br>
    自我介绍:<textarea></textarea>
    <br>
    简历上传:<input type="file">
    <br>
    <button>提交</button>
</body>

</html>
```

