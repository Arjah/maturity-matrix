# Матрица зрелости команд
Матрица зрелости поможет определить текущий уровень вашей команды относительно модели оценки, принятой в компании. 
Помимо этого, здесь представлены советы по достижению необходимого уровня зрелости вашей команды, при наличии такого желания.

## :wrench: QA
Показатели зрелости команды, связанные с тестированием. 

<table>
    <thead>
        <tr>
            <th width=25%>🔆  Уровень 0</th>
            <th width=25%>⭐  Уровень 1</th>
            <th width=25%>🌟  Уровень 2</th>
            <th width=25%>💥  Уровень 3</th>
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
        <tr>
          <td colspan=4 align="left"><a href ="https://github.com/Arjah/maturity-matrix/blob/main/guides/qa.md#%D1%82%D0%B5%D1%81%D1%82%D0%BE%D0%B2%D1%8B%D0%B5-%D1%81%D1%86%D0%B5%D0%BD%D0%B0%D1%80%D0%B8%D0%B8-%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D1%8B-%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D1%8B-%D0%B8%D1%85-%D0%B2%D1%8B%D0%BF%D0%BE%D0%BB%D0%BD%D0%B5%D0%BD%D0%B8%D0%B5-%D0%BE%D1%82%D1%81%D0%BB%D0%B5%D0%B6%D0%B8%D0%B2%D0%B0%D0%B5%D1%82%D1%81%D1%8F-%D1%82%D0%B5%D1%81%D1%82-%D0%BC%D0%B5%D0%BD%D0%B5%D0%B4%D0%B6%D0%BC%D0%B5%D0%BD%D1%82"><b>3. Тестовые сценарии команды определены, их выполнение отслеживается (тест менеджмент)</b></a></td>
        </tr>
        <tr>
          <td align="center">Тест-кейсы не описываются.</td>
          <td align="center">Наборы тест-кейсов определены и покрыто не менее 20% общего покрытия (покрыты основные критичные сценарии) хранятся/заводятся в общем инструменте управления тест-кейсами (Allure).</td>
          <td align="center">Не менее 50% тест-кейсов актуализированны и применяются в тестировании (покрыты все критичные сценарии).</td>
          <td align="center">Не менее 80% тест-кейсов актуализированны и применяются в тестировании.</td>
        </tr>
        <tr>
          <td colspan=4 align="left"><a href ="https://github.com/Arjah/maturity-matrix/blob/main/guides/qa.md#%D0%B8%D0%BD%D1%82%D0%B5%D0%B3%D1%80%D0%B0%D1%86%D0%B8%D1%8F-%D1%82%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-%D0%B2-%D0%BF%D1%80%D0%BE%D1%86%D0%B5%D1%81%D1%81-cicd"><b>4. Интеграция тестирования в процесс CI/CD	</b></a></td>
        </tr>
        <tr>
          <td align="center">Планового покрытия тестами в команде нет.</td>
          <td align="center">Автотесты в команде сущствуют и запускаются вручную.</td>
          <td align="center">Проводится автоматический запуск автотестов при сборке ветки разработчка.</td>
          <td align="center">Вся информация о результатах выполнения тестов выводится на дашборд, весь процесс регрессионного, интеграционного тестирования доступен в одном месте.</td>
        </tr>
        <tr>
          <td colspan=4 align="left"><a href ="https://github.com/Arjah/maturity-matrix/blob/main/guides/qa.md#5-%D0%BF%D1%80%D0%BE%D0%B4%D1%83%D0%BA%D1%82%D1%8B-%D0%BF%D0%BE%D0%BA%D1%80%D1%8B%D1%82%D1%8B-%D0%B0%D0%B2%D1%82%D0%BE%D1%82%D0%B5%D1%81%D1%82%D0%B0%D0%BC%D0%B8"><b>5. Продукты покрыты автотестами	</b></a></td>
        </tr>
        <tr>
          <td align="center">Автотесты не применяются.</td>
          <td align="center">Больше 20% тест-кейсов автоматизированы. Тест-кейсы хранятся/заводятся в общем инструменте управления тест-кейсами(Allure).</td>
          <td align="center">Больше 50% тест-кейсов автоматизированы.</td>
          <td align="center">Больше 80% тест-кейсов автоматизированы.</td>
        </tr>
        <tr>
          <td colspan=4 align="left"><a href ="https://github.com/Arjah/maturity-matrix/blob/main/guides/qa.md#6-%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D0%B0-%D1%83%D0%BC%D0%B5%D0%B5%D1%82-%D0%BE%D1%86%D0%B5%D0%BD%D0%B8%D0%B2%D0%B0%D1%82%D1%8C-%D0%BA%D0%B0%D1%87%D0%B5%D1%81%D1%82%D0%B2%D0%BE-%D1%81%D0%B2%D0%BE%D0%B5%D0%B3%D0%BE-%D0%BF%D1%80%D0%BE%D0%B4%D1%83%D0%BA%D1%82%D0%B0-%D0%B8-%D0%BF%D1%80%D0%BE%D1%86%D0%B5%D1%81%D1%81%D0%BE%D0%B2-%D0%BF%D1%80%D0%B8%D0%BC%D0%B5%D0%BD%D0%B5%D0%BD%D0%B8%D0%B5-dod"><b>6. Команда умеет оценивать качество своего продукта и процессов (применение DoD)</b></a></td>
        </tr>
        <tr>
          <td align="center">Команда не оценивает качество своего продукта, не умеет оценивать.</td>
          <td align="center">Собирает базовые метрики качества, их ревью нерегулярное.</td>
          <td align="center">У команды есть базовые метрики качества продукта, они просматриваются регулярно. Есть расширенные метрики для определения корневых проблем и кастомные метрики под нужны команды.</td>
          <td align="center">Есть процесс пересмотра самих метрик, устанавливаются стандарты качества. Метрики качества постоянно улучшаются.</td>
        </tr>
    </tbody>
</table>

## ✈️ Надёжность	
Показатели зрелости команды, связанные с надёжностью. 

<table>
    <thead>
        <tr>
            <th width=25%>🔆  Уровень 0</th>
            <th width=25%>⭐  Уровень 1</th>
            <th width=25%>🌟  Уровень 2</th>
            <th width=25%>💥  Уровень 3</th>
        </tr>
    </thead>
    <tbody>
        <tr>
          <td colspan=4 align="left"></td>
        </tr>
        <tr>
          <td colspan=4 align="left"><a href="https://github.com/Arjah/maturity-matrix/blob/main/guides/reliability.md#%D0%BC%D0%BE%D0%BD%D0%B8%D1%82%D0%BE%D1%80%D0%B8%D0%BD%D0%B3-%D1%84%D1%83%D0%BD%D0%BA%D1%86%D0%B8%D0%BE%D0%BD%D0%B0%D0%BB%D1%8C%D0%BD%D0%BE%D1%81%D1%82%D0%B8-%D0%BF%D1%80%D0%BE%D0%B4%D1%83%D0%BA%D1%82%D0%BE%D0%B2-%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D1%8B-%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D1%91%D0%BD-%D0%B8-%D0%BD%D0%B0%D1%81%D1%82%D1%80%D0%BE%D0%B5%D0%BD"><b>1. Мониторинг функциональности продуктов команды определён и настроен</b></a></td>
        </tr>
        <tr>
          <td align="center">Мониторинга функциональности нет.</td>
          <td align="center">Мониторинг функциональности есть только для ключевых сервисов команды. (Метрики размечены `product_id` лейблами.)</td>
          <td align="center">100% P1-P2 проблем видим на мониторинге. Настроены sentry для анализа ошибок в работе сервисов.</td>
          <td align="center">В продуктах команды внедрён сквозной трейсинг(нужно понять, как этого реально достичь. Или пока убрать?). Настроен единый дашборд для мониторинга всех ключевых сервисов команды для понимания общей ситуации в системе по принципу светофора.</td>
        </tr>
        <tr>
          <td colspan=4 aligin="left"><a href="https://github.com/Arjah/maturity-matrix/blob/main/guides/reliability.md#Соблюдается целевой уровень качества продуктов (SLO)"><b>Соблюдается целевой уровень качества продуктов (SLO)</b></a></td>
        </tr>
        <tr>
          <td aligin="center">SLO для продукта не закреплен</td>
          <td aligin="center">Команда умеет определять SLO своих продуктов. У команды есть согласованный уровень SLO по критичным продуктам.</td>
          <td aligin="center">Настроен единый дашборд для мониторинга SLO по всем ключевым бизнес процессам команды. У ключевых сервисов команды показатели Availability and Latency не менее 99.5%.</td>
          <td aligin="center">Все смежные продукты, влияющие на SLO команды известны и команда может отслеживать SLO смежных продуктов.
  SLO для смежных продуктов согласован с вледльцами продуктов.</td>
        </tr>
        <tr>
          <td colspan=4 aligin="left"><a href="https://github.com/Arjah/maturity-matrix/blob/main/guides/reliability.md#Настроен алертинг на случай возникновения сбоев в работе продуктов команды"><b>Настроен алертинг на случай возникновения сбоев в работе продуктов команды</b></a></td>
        </tr>
        <tr>
          <td aligin="center">Алертов и дежурств нет</td>
          <td aligin="center">Настроено уведомление о сбоях в ключевом для продуктов команды слое (backend, middleware, frontend). Уведомления о сбоях отправляются в неструктурированые каналы коммуникации.</td>
          <td aligin="center">Уведомления о сбоях ведутся через корпоративные системы управления инцидентами (IRM) и алертами/коммуникациями (Grafana OnCall).</td>
          <td aligin="center">Поддержка приложений осуществляется непрерывно на основе матрицы эскалации и расписании дежурств.
  100% технических сбоев команда узнаёт от системы алёртинга (не от пользователей).</td>
        </tr>
        <tr>
          <td colspan=4 aligin="left"><a href="https://github.com/Arjah/maturity-matrix/blob/main/guides/reliability.md#Нагрузочное тестирование продуктов"><b>Нагрузочное тестирование продуктов</b></a></td>
        </tr>
        <tr>
          <td aligin="center">Нагрузочного/стресс тестирования нет</td>
          <td aligin="center">Команда понимает риски и принимает осознанное решение не использовать нагрузочное тестирование или нагрузочное тестирование проводится по необходимости для самого важного сервиса команды. Самый важный — это высоконагруженный и/или участвующий в важных для бизнеса сценариях.</td>
          <td aligin="center">Составлен профиль нагрузки максимально приближенный к реальной, проводится нагрузочное тестирование всех важных компонентов продукта команды.
  Проводится сравнительный анализ результатов нагрузочного тестирования.</td>
          <td aligin="center">Профиль нагрузочного тестирования покрывает функционал всех компонентов продукта.
  Профиль нагрузочного тестирования обновляется вместе с появлением нового функционала.
  Нагрузочное тестирование проводится при появлении нового функционала и изменении существующего.
  

  Для frontend и middleware без СУБД проводится стресс тест.</td>
        </tr>
        <tr>
          <td colspan=4 aligin="left"><a href="https://github.com/Arjah/maturity-matrix/blob/main/guides/reliability.md#Логирование"><b>Логирование</b></a></td>
        </tr>
        <tr>
          <td aligin="center">Логирование отсутствует</td>
          <td aligin="center">У приложения есть логи и они попадают в OpenSearch кластер домена/коммунальный.</td>
          <td aligin="center">Логи структурированы и могут корректно обрабатыватся экпортерами логов, что обеспечивает поиск по определенным полям в OpenSearch.</td>
          <td aligin="center">В логах отсутствуют персональные или конфиденциальные данные.</td>
        </tr> 
        <tr>
          <td colspan=4 aligin="left"><a href=""><b>  </b></a></td>
        </tr>
        <tr>
          <td aligin="center"> </td>
          <td aligin="center"> </td>
          <td aligin="center"> </td>
          <td aligin="center"> </td>
        </tr> 
    </tbody>
</table>


## 🔒 Безопасность

Показатели зрелости команды, связанные с безопасностью.


## 🏃 Run

Run показатели зрелости команды.

