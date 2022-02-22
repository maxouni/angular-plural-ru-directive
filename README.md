# angular-plural-ru-directive

Directive for Angular for numeral ending dependent of value (Russian language)

Директива для Angular, решающая задачу подстановки в русском языке склонения слов, зависящих от переменной количества.

Если вдруг, не хочется делать через ngSwitch

Использование

1) Импортируем директиву в модуль

2) Подставляем в HTML

```angular2html
<span appPluralRu="" [value]="4" [arVariants]="['год', 'года', 'лет']"></span>
```


