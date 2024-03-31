<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Регистрация</title>
</head>
<body>
    <h1>Регистрация на сайте HiWorld</h1>
    <form action="/submit_registration" method="post">
        <label for="username">Имя пользователя:</label><br>
        <input type="text" id="username" name="username" required><br>
        
        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" required><br>
        
        <label for="password">Пароль:</label><br>
        <input type="password" id="password" name="password" required><br>
        
        <label for="confirm_password">Подтверждение пароля:</label><br>
        <input type="password" id="confirm_password" name="confirm_password" required><br>
        
        <input type="submit" value="Зарегистрироваться">
    </form>
</body>
</html>

