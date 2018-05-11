# meta-carcass

Мета-репо для генераторов CARCASS

## Начало работы

Эти инструкции помогут тебе получить копию проекта на локальную машину для разработки и/или тестирования.

### Необходимые условия окружения

Для запуска проекта в системе должны быть установлены:

- Node.js & NPM
- [Yeoman](http://yeoman.io/)
- [Meta](https://github.com/mateodelnorte/meta)

### Установка

Устанавливаем Meta, клонируем мета-репозиторий, устанавливаем зависимости и линкуем пакеты.

```bash
npm i -g meta meta-npm
meta git clone git@github.com:carcass-yo/meta-carcass.git meta-carcass && cd meta-carcass
meta-npm install
meta-npm link --all
```

