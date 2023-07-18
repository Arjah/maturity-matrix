# Матрица зрелости команд
Матрица зрелости поможет определить текущий уровень вашей команды относительно модели оценки, принятой в компании. 
Помимо этого, здесь представлены советы по достижению необходимого уровня зрелости вашей команды, при наличии такого желания.

## :wrench: QA
Показатели зрелости команды, связанные с тестированием. 

<table>
    <thead>
        <tr>
            <th>🔆  Уровень 0</th>
            <th>⭐  Уровень 1</th>
            <th>🌟  Уровень 2</th>
            <th>💥  Уровень 3</th>
        </tr>
    </thead>
    <tbody>
      <tr>
          <td colspan=4 align="left"></td>
        </tr>
        <tr>
          <td colspan=4 align="left"><a href="https://github.com/Arjah/maturity-matrix/blob/main/guides/qa.md#%D0%B4%D0%BB%D1%8F-%D0%BA%D0%B0%D0%B6%D0%B4%D0%BE%D0%B9-%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D0%B8-%D0%BF%D1%80%D0%BE%D0%B2%D0%BE%D0%B4%D1%8F%D1%82%D1%81%D1%8F-%D0%B2%D1%81%D0%B5-%D0%B2%D0%B8%D0%B4%D1%8B-%D0%BD%D0%B5%D0%BE%D0%B1%D1%85%D0%BE%D0%B4%D0%B8%D0%BC%D1%8B%D1%85-%D1%82%D0%B5%D1%81%D1%82%D0%BE%D0%B2"><b>1. Для каждой задачи проводятся все виды необходимых тестов</b></a></td>
        </tr>
        <tr>
          <td align="center">На прод могут попадать неоттестированные задачи</td>
          <td align="center">На прод попадают только полностью протестированные задачи. Перед каждым деплоем выполняются все критичные функциональные, контрактные, интеграционные и E2E-тесты.</td>
          <td align="center">На прод попадают только полностью протестированные задачи. Перед каждым деплоем выполняются функциональные, контрактные, интеграционные и E2E-тесты.</td>
          <td align="center">Перед каждым деплоем выполняется "умный регресс" (только то, что могло быть задето доработкой + критичные тесты)</td>
        </tr>
        <tr>
          <td colspan=4 align="left"><a href ="https://github.com/Arjah/maturity-matrix/blob/main/guides/qa.md#%D0%BF%D1%80%D0%B8%D0%BC%D0%B5%D0%BD%D1%8F%D1%8E%D1%82%D1%81%D1%8F-%D0%BF%D1%80%D0%B0%D0%BA%D1%82%D0%B8%D0%BA%D0%B8-shift-left-%D1%82%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F"><b>2. Применяются практики Shift-Left тестирования</b></a></td>
        </tr>
        <tr>
          <td align="center">Тестирования нет</td>
          <td align="center">Тестирование "в хвосте" цикла разработки</td>
          <td align="center">Тестирование идет параллельно разработке</td>
          <td align="center">Тестирование идет на всех этапах SDLC. Тестирование не является "бутылочным горлышком" и не плетется в конце SDLC.</td>
        </tr>
    </tbody>
</table>
