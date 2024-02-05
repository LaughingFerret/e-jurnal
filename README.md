<form action="action_page.php">
  <div class="container">
    <h1>Регистрация</h1>
    <p>Заполните данную форму для регистрации</p>
    <hr>

    <label for="email"><b>Email</b></label>
    <input type="text" placeholder="Введите Email" name="email" required>

    <label for="psw"><b>Пароль</b></label>
    <input type="password" placeholder="Введите пароль" name="psw" required>

    <label for="psw-repeat"><b>Подтвердите пароль</b></label>
    <input type="password" placeholder="Подтвердите пароль" name="psw-repeat" required>
    <hr>
    
    <button type="submit" class="registerbtn">Зарегистрироваться</button>
  </div>

  <div class="container signin">
    <p>У вас уже есть аккаунт? <a href="#">Войти</a>.</p>
  </div>
