## Laravel + MoonShine starter kit

### Особенности этого стартового набора

- Установлена административная панель [MoonShine](https://getmoonshine.app/docs/);
- установлены и опубликованы русская и английская локализации;
- установлен пакет [laravel-debugbar](https://github.com/barryvdh/laravel-debugbar);
- добавлен базовый layout-компонент вместо файла "welcome.blade.php".

### Установка

Для создания нового проекта, используя установщик Laravel, выполните команду:

```shell
laravel new my-app --using=shevl-dev/laravel-starter
```

Для продолжения работы с административной панелью, необходимо создать [супер-пользователя админ панели](https://getmoonshine.app/ru/docs/3.x/advanced/commands#user):

```shell
php artisan moonshine:user {--u|username=} {--N|name=} {--p|password=}
```
