# ChenYong011.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <script type="text/javascript" src="js/text.js"></script>

</head>
<body>
    <form action="register.jsp" onsubmit="return dataCheck()">
        <table border="1px" width="500px" height="500px">
            <tr>
                <td colspan="2" align="center">注册</td>
            </tr>
            <tr>
                <td align="right">用户名:</td><td align="left"><input type="text" id="userName" onblur="CheckUserName(this)"/>
                <font color="red" id="userNameMessage"></font>
                </td>
            </tr>
            <tr>
                <td align="right">邮箱:</td><td align="left"><input type="text" id="userEmail" onblur="CheckEmail(this)"/>
                <font color="red" id="emailMsg"></font>
                </td>
            </tr>
            <tr>
                <td align="right">密码:</td><td align="left"><input type="password" id="passWord" onblur="CheckPassWord()"/>
                <font color="red" id="passWordMsg"></font>
                </td>
            </tr>
            <tr>
                <td align="right">重复密码</td><td align="left"><input type="password" id="passWord2"/>
                <font color="red" id="rePassWordMsg"></font>
                </td>
            </tr>
            <tr>
                <td colspan="2" align="center"><input type="submit" value="注册"></td>
            </tr>
        </table>
    </form>
</body>
</html>
