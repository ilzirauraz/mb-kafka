# Тестовое использование брокера kafka

## Утсановка
Установить зависимости 
```bash
  pip install -r requirements.txt
```
## Запуск

- Запуск сервисов командой
  ```bash
  docer-compose up
  ```

- Запустить consumer
    ```bash
    python consumer.py
  ```

- Запустить producer.py
    ```bash
    python producer.py
  ```
В терминале выведутся сообщения, которые получает consumer