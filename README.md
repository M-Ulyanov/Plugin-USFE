начальное значение текста в поле для имени файлаPlugin-USFE
===========

Плагин для легкой стилизации сложных элементов форм User Style Elements Form.

### Элементы для стилизации

Плагин работает со следующими элементами:
 - input type="text"
 - input type="password"
 - input type="email"
 - input type="file"
 - input type="submit"
 - input type="reset"
 - input type="radio"
 - input type="checkbox"
 - input type="usfe-number";
 - input type="usfe-calendar"
 - button type="submit"
 - button type="reset"
 - button type="button"
 - select
 - textarea

### Использование

Для начала использования необходимо подключить jquery и ниже вызывать плагин:
**$(elem).usfe({})** - вызов плагина без параметров, буду задействованы параметры по умолчанию.
elem -  может быть форма **'form.order-form'**, тогда плагин обработает все дочерние элемент
доступныедля стилизации.
elem - непосредственно элемент который будет обработан **'input[type="radio"]'**

Для плавного изменения цветов у некоторых элементов, необходимо так же 
подключить jquery.color.

## Параметры

Для каждого элемента или группы элементов у параметров есть свой уникальный преффикс.

### input type="file
**f_defaultFileName** | Начальное значение текста в поле для имени файла
--- | ---
**f_defaultFileNameDel** | Значение текста после удаления выбранного файла
--- | ---
**f_defaultButtonName** | Начальный текст кнопки для выбора файла
--- | ---
**f_editButtonName** | Начальное значение текста в поле для имени файла
--- | ---
**f_defaultFileName** | Начальное значение текста в поле для имени файла
--- | ---
**f_charDelete** | Текст или другой html символ для кнопки удаления выбранного файла
--- | ---
**f_bgDelete** | Фон обертки при нажатии на кнопку удаления выбранного файла
--- | ---


##Поддержка атрибутов

##Динамическое изменение

##Кроссбраузерность

##Связаться с автором
