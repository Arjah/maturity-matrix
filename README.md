# Матрица зрелости команд
Матрица зрелости поможет определить текущий уровень вашей команды относительно модели оценки, принятой в компании. 
Помимо этого, здесь представлены советы по достижению необходимого уровня зрелости вашей команды, при наличии такого желания.

## :wrench: QA
Показатели зрелости команды, связанные с тестированием. 

### 1. Для каждой задачи проводятся все виды необходимых тестов
Задачи необходимо тестировать. 

[Как достичь нужного уровня?](https://github.com/Arjah/maturity-matrix/blob/main/guides/qa.md#%D0%B4%D0%BB%D1%8F-%D0%BA%D0%B0%D0%B6%D0%B4%D0%BE%D0%B9-%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D0%B8-%D0%BF%D1%80%D0%BE%D0%B2%D0%BE%D0%B4%D1%8F%D1%82%D1%81%D1%8F-%D0%B2%D1%81%D0%B5-%D0%B2%D0%B8%D0%B4%D1%8B-%D0%BD%D0%B5%D0%BE%D0%B1%D1%85%D0%BE%D0%B4%D0%B8%D0%BC%D1%8B%D1%85-%D1%82%D0%B5%D1%81%D1%82%D0%BE%D0%B2)
| 🔆  Уровень 0| ⭐  Уровень 1| 🌟  Уровень 2| 💥  Уровень 3|
| :------------- | ------------- |------------- |------------- |
|На прод могут попадать неоттестированные задачи | На прод попадают только полностью протестированные задачи. Перед каждым деплоем выполняются все критичные функциональные, контрактные, интеграционные и E2E-тесты. | На прод попадают только полностью протестированные задачи. Перед каждым деплоем выполняются функциональные, контрактные, интеграционные и E2E-тесты. | Перед каждым деплоем выполняется "умный регресс" (только то, что могло быть задето доработкой + критичные тесты) |


### 2. Применяются практики Shift-Left тестирования
Shift-Left тестирование - это такой подход в тестировании, в котором QA погружается в работу на самых ранних стадиях разработки. Другими словами, QA начинает тестировать продукт уже на уровне идеи.

[Как достичь нужного уровня?](https://github.com/Arjah/maturity-matrix/blob/main/guides/qa.md#%D0%BF%D1%80%D0%B8%D0%BC%D0%B5%D0%BD%D1%8F%D1%8E%D1%82%D1%81%D1%8F-%D0%BF%D1%80%D0%B0%D0%BA%D1%82%D0%B8%D0%BA%D0%B8-shift-left-%D1%82%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F)
| 🔆  Уровень 0| ⭐  Уровень 1| 🌟  Уровень 2| 💥  Уровень 3|
| :------------- | ------------- |------------- |------------- |
|Тестирования нет | Тестирование "в хвосте" цикла разработки | Тестирование идет параллельно разработке| Тестирование идет на всех этапах SDLC. Тестирование не является "бутылочным горлышком" и не плетется в конце SDLC. |

