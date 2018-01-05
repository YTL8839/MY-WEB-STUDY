
<!doctype html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>form表单</title>
</head>
<body>
<div>
    <label for="username">姓名:</label>
    <input type="text" id="username" name="username" placeholder="用户名">
</div>
<div>
    <label for="password">密码:</label>
    <input type="password" id="password" name="password" value="123456789">
</div>
<div>
    <label for="">性别:</label>
    <input type="radio" name="sex" value="male" checked>男
    <input type="radio" name="sex" value="female">女
</div>
<div>
    <label for="">取向:</label>
    <input type="radio" name="lover" value="male">男
    <input type="radio" name="lover" value="female" checked>女
</div>
<div>
    <label for="">爱好:</label>
    <input type="checkbox" name="hobby" value="dota">dota
    <input type="checkbox" name="hobby" value="tour" checked>旅游
    <input type="checkbox" name="hobby" value="pet" checked>宠物
</div>
<div>
    <label for="">评论:</label>
    <textarea name="comment" id="comment" cols="30" rows="10">ddd</textarea>
</div>
<div>
    <label for="">我的car:</label>
    <select name="car" id="car">
        <option value="benz">奔驰</option>
        <option value="saab" selected>萨博</option>
        <option value="BMW">宝马</option>
    </select>
    <input type="submit" name="submit" value="提交">
</div>
</body>
</html>
