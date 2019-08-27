# angular-plural-ru-directive

Directive for angular 8 for numeral ending dependent of value

Директива для Angular, решающая задачу подстановки в русском языке окончания числительных, зависящих от переменной количества

Если вдруг, не хочется делать через ngSwitch

Использование

1) Импортируем директиву в модуль

2) Подставляем в HTML

```angular2html
<span appPluralRu="" [value]="4" [arVariants]="['год', 'года', 'лет']"></span>
```


