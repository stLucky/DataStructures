# asynchrony/immediate

Этот модуль предоставляет 2 функции:
  - `setImmediate` - выполнит код в конце текущего цикла событий. Первым аргументом принимает функцию колбэк, вторым - аргументы которые будут переданы этой функции. Возвращает объект `Immediate`, который можно использовать для отмены запланированной таски;
  - `clearImmediate` - принимает объект `Immediate` и отменяет запланированную таску.