# Установка через Composer

## composer create-project

Выполните в следующую команду в консоли чтобы установить стабильный релиз:

`composer create-project yupe/yupe your-project --prefer-dist`

Для установки разрабатываемой версии:

`create-project yupe/yupe:dev-dev your-project --prefer-dist`

Если вас интересует конкретный релиз, выполните:

`composer create-project yupe/yupe:0.9.6 your-project --prefer-dist`

## git clone
Клонируем репозиторий

```git clone git@github.com:yupe/yupe.git your-project```
cd your-project

Если нужно переходим на другую ветку или тэг с нужным нам релизом
```git checkout dev```

Устанавливаем зависимости
```composer install --prefer-dist```

# Установка из архива
Просто скачиваем [http://yupe-project.ru/download](http://yupe-project.ru/download) и распаковываем архив.

Полный список релизов доступен по ссылке [https://github.com/yupe/yupe/releases](https://github.com/yupe/yupe/releases).