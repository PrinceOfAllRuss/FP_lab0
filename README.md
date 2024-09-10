# Функциональное программирование. Лабораторная работа 0

- Выбрал функциональный язык **Clojure**. Изучаю Java, поэтому решил, что надо выбрать что-то приближенное к ней.
- Clojure работает на виртуальной машине Java, а значит обладает: сборщиком мусора и портативностью. Также благодаря этому можно использовать и все библиотеки Java. Обладает современными эффективными структурами данных. Обладает новой моделью многопоточного программирования с core.async.
- Также существует ClojureScript, который легко компилируется в JavaScript и запускается в браузере. Он может взаимодействовать с библиотеками JavaScript. Это позволяет использовать один и тот же язык для клиентской и серверной части. На четвертой лабораторной планируется написать клиент-серверное приложение, так что тот факт, что Clojure можно использовать и там, и там – интересно и отчасти удобно.

**Компилятор**: JVM  
**Линтер**: <https://github.com/clj-kondo/clj-kondo>  
**Тесты**: kaocha, <https://github.com/lambdaisland/kaocha>  
**Сборка**: Leiningen, <https://github.com/technomancy/leiningen>  
**Стиль кодирования**: <https://habr.com/ru/companies/otus/articles/725060/>

**Книга**: «Clojure на производстве» Гришаев И.В.
- Книга от русскоговорящего человека, то есть не перевод, а значит и проблем с содержанием быть не должно.
- В книге нет вводной информации, которую можно прочитать в интернете, а присутствуют конкретные примеры разработки, написания тестов и работа с конфигурациями, а также есть обзоры популярных библиотек.

**Статьи**:
- <https://calva.io/getting-started/>
- <https://alexott.net/ru/clojure/ClojureLein.html>
