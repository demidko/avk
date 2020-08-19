## Avk
Утилита анализирует активность ВК в фоновом режиме. 
### Как запускать проект напрямую из исходного кода?
1. Установить [.NET Core SDK](https://dot.net)
2. В директории репозитория выполнить команду:  
`dotnet run -- [login] [password]`  
После этого можно запускать используя кеш предыдущей авторизации:  
`dotnet run`
### Управляющие команды
* Получить статистический отчет по человеку `ls [ссылка]`
* Вывести список учета (по умолчанию все друзья)  `ls`
* Поставить нового человека на учет  `add [ссылка]`
* Снять с учета  `rm [ссылка]`
### TODO
* Алгоритм:  
  ```
  map: friend -> linked list of { timestamp, friends online }
  ```
* PWA
