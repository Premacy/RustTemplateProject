Этот репозиторий содержит шаблон любого другого проекта на Rust, включая в себя:
1) Пример докер файла для кросс компиляции проекта
2) Пример скрипта сборки проекта
3) Пример Cargo.toml файла

Создание контейнера:
docker build . -t rust_cross_compile

Запуск контейнера:
docker run --rm -v ‘your-pwd’:/app rust_cross_compile
