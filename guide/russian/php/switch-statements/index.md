---
title: Switch Statements
localeTitle: Записи переключателей
---
## Записи переключателей

Операторы switch выполняют блоки кода, основанные на значении условия.

### Синтаксис:

```PHP
switch(x) { 
  case 1: 
    statement1; 
    break; 
   case 2: 
     statement2; 
     break; 
   default: 
     defaultstatement; 
 } 
```

В приведенном выше примере x является условием. Заявления, следующие за случаем совпадения, будут выполнены. Если совпадений нет, будут выполняться инструкции (ы) по умолчанию.

Ключевое слово `break` используется для завершения каждого случая.

### Дополнительная информация:

[Переключатель PHP](http://php.net/manual/en/control-structures.switch.php)