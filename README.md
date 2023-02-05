# Run all

Данная утилита запускает код программ на разных языках без необходимости устанавливать компиляторы и тулинг для каждой программы.

## Запуск

```bash
./run path/to/source/file.js
```

Можно запустить тесты с простейшими hello world вариантами:
**WARNING!** Будет скачано множество докер образов на каждый язык.
```bash
./test
```

## Требования

- docker

## Ограничения

- Один файл без установки каких либо зависимостей

## Поддерживаемые языки

- JavaScript (Node.js)
- TypeScript (Node.js)
- Golang
- Rust
- Python
- Ruby
- Java
- C/C++
- PHP

## TODO
- Проверка что переданный файл существует и является файлом (а не, например, директорией)
- Работа с относительными и абсолютные путями. В относительных учесть пути "наверх"
- Поддержка других языков
- (?) сlean режим для удаления ненужных образов
- (?) Возможность скачать с github