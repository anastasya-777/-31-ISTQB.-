# 31-ISTQB.
## 1. Основные понятия ISTQB.
### 1.1 ISTQB (International Software Testing Qualification Board)- международная организация, которая занимается вопросами развития сферы тестирования ПО: структура, материалы, правила аккредитации, сертификации и т.п. Основана представителями 8 стран: Австрии, Дании, Финляндии, Германии, Швеции, Швейцарии, Нидерландов и Великобритании.
 -  ISTQB Сертификация Тестировщика – программа, которая позволяет специалистам получать международный сертификат по тестированию.Сертификация ISTQB подтверждает уровень знаний и навыков специалиста в области тестирования, что делает его более привлекательным для работодателей и повышает его профессиональный статус.
### 1.2 ISTQB ставит перед собой 2 задачи:
#### 1. Развитие и стандартизация всех направлений тестирования;
#### 2. Сертификация специалистов по тестированию.
### 1.3 Уровни сертификации ISTQB:
### Основное направление:
 - Foundation Level (базовый уровень) 
 - Advanced Level (продвинутый уровень) 
 - Expert Level (экспертный уровень)
### Agile:
 - Agile Tester (Foundation Level)
### Специалист:
 - Model-based Tester (Foundation Level)
 - Security Tester (Advanced Level)
 - Test Automation Engineer (Advanced Level)
### Продвинутый уровень (Advanced Level) основного направления состоит из трех частей:
 - Руководитель тестирования (Test Manager)
 - Тест-аналитик (Test Analyst)
 - Технический тест-аналитик (Technical Test Analyst)
### 1.4 Чтобы получить сертификат ISTQB  тестировщика ПО необходимо успешно сдать экзамен. Для успешной сдачи экзамена необходимо набрать не менее 65% (26 или более баллов). Для прохождения сертификации ISTQB любого Продвинутого уровня необходимо иметь сертификат Базового уровня. Это дает возможность выбора сертификации в одной специфичной области или сдачи всех трех экзаменов.

## 2. Основные процессы тестирования программного обеспечения.
### 2.1 Основные этапы процесса тестирования программного обеспечения:
#### 1. Работа с требованиями.Знакомство с требованиями заказчика.Обсуждение,что должен представлять из себя итоговый продукт.
#### 2. Разработка стратегии тестирования. Оценка сроков тестирования,выявление среды тестирования,объединение всей информации полученной при работе с требованиями.
#### 3. Создание тестовой документации. Написание сценариев,которые позволят проверить функционал.
#### 4. Тестирование прототипа. Тестирование основного функционала продукта,корректировка целей,добавление фичей.
#### 5. Основное тестирование. Выполнение общей проверки продукта.
#### 6. Стабилизация. На данном этапе происходит работа над устранением багов.
#### 7. Эксплуатация и поддержка. Проводится регресс-тестирование,устранение ошибок, которые нашел конечный пользователь.
### 2.2  Основные группы (виды)тестирования:
 - функциональные (Functional testing)
 - Нефункциональные (Non-functional testing)
 - Связанные с изменениями (New feature testing,Retest, Defect validation, Regression testing)
### Виды функционального тестирования:
 - Функциональное - проверка корректности основного функционала ПО.
 - Графического интерфейса(GUI) - заголовок,шрифт,текст и т.д.
### Виды нефункционального тестирования:
 - Тестирование защищенности (Security testing)
 - Тестирование безопасности (Safety testing)
 - Тестирование производительности (Performance testing) - определить производительность продукта.
 - Нагрузочное тестирование (Load testing) - оценивает поведение системы под увеличивающейся нагрузкой.
 - Стрессовое тестирование (Stress testing) - оценивает систему на граничных значениях нагрузки и за их пределами.
 - Тестирование графического интерфейса (GUI testing) - заголовок,шрифт,текст и т.д.
 - Тестирование удобства использования (Usability testing) - удобство использования.
 - Тестирование доступности (Accessibility testing)
 - Тестирование совместимости (Compatibility testing)- проверка совместной работы с другими сайтами и приложениями.
 - Тестирование кроссбраузерности (Cross browser testing)
 - Тестирование кроссплатформенности (Cross platform testing)
 - Тестирование инсталляции (Installation testing) - чтобы не возникало внутреннего конфликта
 - Тестирование интернационализации (Internationalization testing)- перевод на разные языки
 - Тестирование локализации (Localization testing) - на соответствие языковым требованиям.
### Виды  тестирования по изменениям:
 - Тестирование нового функционала (New feature testing)
 - Перепроверка дефекта (Retest, Defect validation)
 - Регрессионное тестирование (Regression testing)
### 2.3 Методы тестирования:
 - Чёрный ящик (Black-box testing)
 - Белый ящик (White-box testing)
 - Серый ящик (Gray-box testing)
### 2.4 Инструменты для тестирования:
 - TestRail
 - Jira
 - Postman
 - Apache JMeter
 - TestLink 
 - Mantis
## 3. Тест-кейсы.
### 3.1 Тест-кейс - детализированный план того, как проверить определенное требование к программе.
### 3.2 Атрибуты тест-кейса: уникальный идентификатор, название, краткое описание,приоритет, шаги, ожидаемый результат.
### 3.3 Как правильно писать тест-кейсы:
 - Один тест-кейс проверяет одну конкретную функцию или пользовательский сценарий. 
 - Тест-кейс состоит из информации о том, что должно быть проверено, пошаговой инструкции, как это проверить, а также данных и условий, при которых нужно проводить эту проверку. 
 - Описание тест-кейсов излагается простой, общедоступной лексикой.
 - Тест-кейс не содержит никаких зависимостей с другими. По крайне мере, надо стремиться к их минимизации и избегать ссылок на другие тест-кейсы;
 - Тест-кейсы разбивают по назначению на функциональные блоки.
### 3.4 Инструменты для написания тест-кейсов:
## _Microsoft Excel, JIRA, Test IT, Allure TestOps и т.д._
## 4. Тестирование программного обеспечения.
### 1. Планирование тестирования:
-  Планирование тестирования (Test planning)
-  Мониторинг и контроль тестирования (Test monitoring and control)
### 2. Анализ и дизайн тестирования:
-  Анализ тестирования (Test analysis)
-  Дизайн тестирования (Test design)
### 3. Реализация и выполнение тестирования:
-  Реализация тестирования (Test implementation)
-  Выполнение тестирования (Test execution)
### 4. Анализ результатов, репортинг и завершение тестирования:
-  Анализ результатов тестирования и репортинг (Evaluating exit criteria and reporting)
-  Завершение тестирования (Test closure activities)
## 5. Экзамен ISTQB.
### Каждый экзамен состоит из определенных вопросов, нацеленных на проверку профессиональных знаний кандидата по темам, описанным в соответствующей Программе. Программы для Базового и Продвинутого уровней отличаются. Более того, в Продвинутом уровне есть три разных раздела, каждый из которых попадает под определенный сертификат. Так же и Экспертный уровень будет делиться на несколько различных модулей.
### Экзамен Базового уровня не имеет никаких особых предпосылок и не требует специальных знаний или умений. Рекомендуется лишь подготовка на основе программы сертификации (получить такую подготовку можно на специальных курсах, организуемых аккредитованными компаниями, получая профессиональный опыт, и/или изучая предмет самостоятельно).
### Для сдачи экзамена Продвинутого уровня или модулей Специалист вы должны обладать сертификатом Базового уровня; ISTQB также рекомендует иметь практический опыт в тестировании перед прохождением экзамена.Экзамен Экспертного уровня доступен лишь тем, кто обладает сертификатом Продвинутого уровня.
### Главный источник информации, который должен быть обязательно прочитан, а для успешной сдачи экзамена — выучен и понят — это Foundation Level Syllabus. Конспект доступен на официальном сайте, в разделе «Downloads». 
### Также рекомендуется прочесть книги, в которых изучаемые темы освещены более подробно: 
-  Foundations of Software Testing: ISTQB Certification by Rex Black, Dorothy Graham, Erik Van Veenendaal 
-  Software Testing: An ISTQB-ISEB Foundation Guide by Peter Morgan, Angelina Samaroo and Brian Hambling 
-  ISTQB Foundation Exam Preparation Guide — Rex Black.

## 6. ISTQB и получите сертификата.
### 6.1 Чтобы сдать экзамен, нужно выбрать аккредитованную организацию. Список можно найти на сайте ISTQB в разделе Training Exams -> Find an Exam Provider. Попадете сюда. Тут выбираем страну в которой живете, язык на котором хотите сдавать экзамен и какой сертификат хотите получить. Сдавать экзамен можно сдавать двумя способами: в электронном виде и на бумаге в офисе.
### 6.2 За сдачу экзамена в электронном виде сумма будет немного выше (150 евро). Обратите внимание, что если при сдаче экзамена Вы указали, что хотите получить только электронную версию сертификата, а бумажную не хотите ( или наоборот), то ничего доплачивать не придется. Если же Вы хотите получить сертификат и в бумажном и в электронном виде, то нужно будет еще 25 евро заплатить. Хотя можно просто свой электронный распечатать. Сертификат действителен в течение всей вашей жизни.
### 6.3 С точки зрения Qa-специалиста сертификация – это подтверждение квалификации и профпригодности международными экспертами в области тестирования.Повышение конкурентоспособности на рынке труда. Уверенность в завтрашнем дне.Расширение и систематизация знаний в области QA. Сертификация – отличный способ для QA-специалиста нарастить и обогатить знания по тестированию.
## 7. Польза получения сертификата ISTQB.
### Дополнительное конкурентное преимущество на рынке как для себя,так и для компании. 
### Бонус при участии в крупных тендерах: наличие сертифицированных специалистов дает преимущество компаниям при участии в конкурсном отборе применительно к тендерам. 
### Снижение рисков: наличие сертификата говорит о том, что специалисты владеют методологией тестирования, а это снижает риски проведения некачественного тест-анализа и может повысить скорость тестирования за счет оптимизации числа тестовых сценариев. 
### Преимущества на международном рынке при оказании услуг по тестированию ПО, предназначенного для иностранных клиентов и иностранного ПО. Рост компетенций внутри компании за счет наставничества и обучения несертифицированных специалистов признанным международным стандартам в области тестирования.
## 8. Тенденций в области разработки программного обеспечения в 2024 году:
- Интеграция искусственного интеллекта и машинного обучения
- Микросервисы с множественными средами выполнения
- Кибербезопасность
- Дальнейшее внедрение VR и AR
- Устойчивая разработка программного обеспечения
- Внесерверная обработка данных (FaaS)
- Расширение облачных вычислений
- Рост числа пользователей языка Rust
- Рост числа low-code и no-code платформ
- Рост числа прогрессивных веб-приложений (PWA)
- Разработка кросс-платформенных приложений
