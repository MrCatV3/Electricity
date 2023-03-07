# Electricity
## Discription
  Моей предметной областью является сайт "Управление заказами услуг электрика". Название будет придумано в дальнейшем.
  На сайте будут учетные записи администратора(-ов) и пользователей(заказчиков). Будет производиться учет клиентов, чеков и документации.
  В моей базе данных будут находиться такие таблицы:
    Таблица Admin
      *IDAdmin
      *Name
      *Phone
      *Mail
      *Login
      *Password
    Таблица Users
      *IDUser
      *Name
      *SurName
      *Phone
      *Login
      *Password
    Таблица Check
      *IDCheck
      *IDRequest
      *Cost
    Таблица Request
      *IDRequest
      *IDUser
      *IDAdmin
      *Document
      
