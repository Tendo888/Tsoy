<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>МойСайт</title>
  <!-- Подключение Bootstrap 5 -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Навигация -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">МойСайт</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link active" href="#">Главная</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Меню</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Контакты</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Контент -->
  <div class="container py-4">
    <div class="row">
      <!-- Таблица -->
      <div class="col-lg-6 mb-4">
        <h2>Таблица данных</h2>
        <table class="table table-bordered table-striped">
          <thead class="table-primary">
            <tr>
              <th>#</th>
              <th>Имя</th>
              <th>Возраст</th>
              <th>Город</th>
            </tr>
          </thead>
          <tbody>
            <tr><td>1</td><td>Владимир</td><td>19</td><td>Асака</td></tr>
            <tr><td>2</td><td>Баглан</td><td>20</td><td>Кибрай</td></tr>
            <tr><td>3</td><td>Абдурасул</td><td>19</td><td>Харезм</td></tr>
          </tbody>
        </table>
      </div>

      <!-- Форма -->
      <div class="col-lg-6 mb-4">
        <h2>Форма обратной связи</h2>
        <form>
          <div class="mb-3">
            <label for="name" class="form-label">Имя</label>
            <input type="text" class="form-control" id="name" placeholder="Имя">
          </div>
          <div class="mb-3">
            <label for="email" class="form-label">Email адрес</label>
            <input type="email" class="form-control" id="email" placeholder="Почта">
          </div>
          <div class="mb-3">
            <label for="message" class="form-label">Сообщение</label>
            <textarea class="form-control" id="message" rows="4" placeholder="Сообщение"></textarea>
          </div>
          <button type="submit" class="btn btn-primary">Отправить</button>
        </form>
      </div>
    </div>

    <!-- Прогресс бар -->
    <div class="row">
      <div class="col-12">
        <h2>Загрузка</h2>
        <div class="progress">
          <div class="progress-bar progress-bar-striped progress-bar-animated bg-primary" 
               role="progressbar" style="width: 70%;">70%</div>
        </div>
      </div>
    </div>
  </div>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
# Tsoy
