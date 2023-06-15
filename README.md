# Electricity
## Discription
  Моей предметной областью является сайт "Управление заказами услуг электрика". Название будет придумано в дальнейшем.
  На сайте будут учетные записи администратора(-ов) и пользователей(заказчиков). Будет производиться учет клиентов, чеков и документации.
  В моей базе данных будут находиться такие таблицы:
    Таблица Admin
      *IDAdmin (PK)
      *Name
      *Phone
      *Mail
      *Login
      *Password
    Таблица Users
      *IDUser (PK)
      *Name
      *SurName
      *Phone
      *Login
      *Password
    Таблица Check
      *IDCheck (PK)
      *IDRequest (FK)
      *IDType (FK)
      *Cost
    Таблица Request
      *IDRequest (PK)
      *IDUser (FK)
      *IDAdmin (FK)
      *IDDocument (FK)
      *Date
    Таблица Document
      *IDDocument (PK)
      *NameDocument
      *DocumentPath
    Таблица TypeOfPayment
      *IDType (PK)
      *TypeName
      
