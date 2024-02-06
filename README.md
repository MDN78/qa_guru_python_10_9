## Задание 9

Написать тест на проверку названия Issue в репозитории через Web-интерфейс.

Этот тест представить в трех вариантах:

1. Чистый Selene (без шагов)
2. Лямбда шаги через with allure.step
3. Шаги с декоратором @allure.step
4. Разметку тестов всеми аннотациями


### Установить Scoop
Typical Installation
Run this command from a non-admin PowerShell to install scoop with default configuration, 

scoop will be install to ```C:\Users\<YOUR USERNAME>\scoop```.

```irm get.scoop.sh | iex```

### Открыть PowerShell (не как администратор) и командой установить allure - так установиться последняя версия

```scoop install allure```

далее команда `allure serve allure_results` или с указанием пути где эта папка
