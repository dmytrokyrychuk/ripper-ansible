# ripper-ansible

Плейбук для запуску ріпера на віддалених машинах.

Плейбук встановлює докер та запускає https://github.com/nitupkcuf/runner

## Запуск

```
TARGET_HOST=rt.com ansible-playbook playbook.yml -i USER@RUNNER_HOST, -k
```

- TARGET_HOST - хост, який буде атаковано
- RUNNER_HOST - хост, з якого вести атаку
- USER - ім'я користувача на хості атаки
